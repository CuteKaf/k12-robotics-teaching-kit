# K12 Robotics Teaching Kit

一个面向 **线下授课** 的机器人课程教学仓库。视频不是主课本体，而是服务于线下课堂的教辅系统。

## 定位

本仓库用于组织一整套与机器人项目教学相关的内容：

- 线下主课程设计
- 辅助视频脚本与清单
- 学生任务单
- 教师讲义
- 家长/招生说明材料
- 课程项目轻量化设计与迭代方案
- 视频制作方法论与执行模板

## 教学理念

这套课程采用：

- **小步验证**：先环境，再视觉，再相机，再标定，再机械臂，再流程闭环
- **线下主导**：高价值部分在线下完成，例如装配、调试、排错、理解工程逻辑
- **视频辅助**：视频负责标准化讲解、课前预习、课后复盘、漏课补看
- **项目驱动**：以真实机器人项目为载体，强调“能跑通、能解释、能展示”
- **先轻后重**：先做适合教学的轻量版，再逐步走向复杂闭环

## 仓库结构

```text
k12-robotics-teaching-kit/
├── README.md
├── curriculum/
│   ├── course-outline.md
│   ├── offline-teaching-package-v1.md
│   └── lesson-plans/
├── handouts/
│   ├── student-task-sheets/
│   ├── teacher-notes/
│   └── parent-facing/
├── videos/
│   ├── preclass/
│   ├── inclass-support/
│   └── review/
├── video-production/
│   ├── README.md
│   ├── why-video-is-supporting-not-main.md
│   ├── what-to-film-and-what-not-to-film.md
│   ├── video-types-for-offline-robotics-course.md
│   ├── recording-workflow.md
│   ├── editing-workflow.md
│   └── template-for-each-video.md
├── project-design/
│   ├── lightweight-project-principles.md
│   └── lightweight-robotics-course-architecture.md
├── assets/
└── slides/
```

## 推荐使用方式

### 对老师
- 先看 `curriculum/course-outline.md`
- 再看 `curriculum/offline-teaching-package-v1.md`
- 再看 `video-production/` 理清视频策略
- 再看 `project-design/` 里的轻量化方案
- 每次备课参考 `handouts/teacher-notes/`

### 对学生
- 上课前看 `videos/preclass/` 对应视频提纲
- 课堂中按 `handouts/student-task-sheets/` 完成任务
- 课后看 `videos/review/` 复盘

### 对家长/招生
- 看 `handouts/parent-facing/course-intro.md`

## 当前版本

- v0.3：课程框架、线下教学包、轻量化方向说明、视频制作专区、基础任务单模板


