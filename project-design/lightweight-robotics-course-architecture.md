# 轻量化机器人课程项目架构

## 推荐的 v1 教学项目结构

```text
robotics-course-lite/
├── README.md
├── environment/
│   ├── setup.sh
│   └── check_setup.py
├── vision/
│   ├── view_camera.py
│   ├── detect_2d.py
│   └── detect_xyz.py
├── calibration/
│   ├── capture.py
│   ├── solve.py
│   └── verify.py
├── control/
│   ├── move_pose.py
│   ├── hover_target.py
│   └── fake_grasp.py
├── config/
│   ├── camera.yaml
│   ├── calibration.yaml
│   ├── poses.yaml
│   └── workspace.yaml
├── assets/
│   └── boards/
└── docs/
    ├── quickstart.md
    ├── student-guide.md
    └── teacher-guide.md
```

## 为什么这样更轻

### 1. 目录更少
学生第一次看项目时不会被大量目录淹没。

### 2. 命名更直接
- `vision/` 就是视觉
- `control/` 就是控制
- `calibration/` 就是标定

### 3. 去掉过早的复杂层
第一版先不放：
- webapp
- 大型总控 pipeline
- 多种末端执行器适配
- 与比赛最终版耦合过深的目录

### 4. 文档先服务教学
项目文档先写：
- 学生怎么开始
- 老师怎么带
- 本节成功标准是什么

而不是先写复杂工程背景。

## 推荐的最小可教闭环

### v1 最小闭环
1. 环境初始化成功
2. 相机取流成功
3. 2D 检测成功
4. XYZ 输出成功
5. 机械臂能移动到固定 pose
6. 机械臂能对目标悬停
7. fake grasp 跑通

### v2 再加入
- 更稳的标定流程
- 更完整的任务位姿记录
- 回收点逻辑
- 课程演示级总控脚本

### v3 再加入
- 真实抓取
- Web 控制台
- 更复杂的末端执行器
- 竞赛和展示版增强功能
