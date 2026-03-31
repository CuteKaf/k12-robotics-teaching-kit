# 环境搭建说明

## 推荐环境
- Ubuntu 22.04
- Python 3
- Conda
- RealSense D435
- 机械臂控制环境

## 基础初始化

```bash
cd /home/robot/project/sort_trash
bash environment/setup_grasp_gpu.sh
```

## 基础自检

```bash
conda run -n grasp-gpu python scripts/dev/check_setup.py \
  --config config/sort_trash_pipeline.example.yaml
```

## 课堂建议
- 环境初始化建议老师提前跑通一遍
- 学生上课时优先保证 check_setup 可通过
- 相机与机械臂调试分开进行
- 所有命令准备打印版/任务单版
