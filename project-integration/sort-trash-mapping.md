# 项目映射：sort_trash 到课程模块

## 项目教学映射

### M1 机器人与编程基础
- `environment/setup_grasp_gpu.sh`
- `scripts/dev/check_setup.py`
- `config/sort_trash_pipeline.example.yaml`

### M2 机械系统与 DIY 装配
- SO-ARM100 结构件打印与装配
- `pyAgxArm/`
- 末端执行器与控制板连接

### M3 机器视觉
- `scripts/vision/view_realsense_stream.py`
- `scripts/vision/detect_realsense_yolo_2d.py`
- `scripts/vision/detect_realsense_yolo_xyz.py`

### M4 运动学与位姿
- `config/task_poses.yaml`
- `config/drop_poses.yaml`
- `scripts/control/record_task_poses.py`
- `scripts/control/record_drop_poses.py`

### M5 系统集成与闭环
- `scripts/calibration/capture_eye_to_hand.py`
- `scripts/calibration/solve_eye_to_hand.py`
- `scripts/calibration/verify_eye_to_hand.py`
- `scripts/control/hover_detected_target.py`
- `scripts/control/run_fake_grasp_cycle.py`

### M6 进阶与扩展
- `webapp/`
- `scripts/control/run_sort_trash_pipeline.py`
- 竞赛与论文转化

## 课程提醒
- 不要按仓库目录顺序讲课，要按学生认知路径讲
- 不要一上来追求整套抓取闭环
- 优先让学生看到反馈，再进入工程抽象
