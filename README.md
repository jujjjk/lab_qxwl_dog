# lab_qxwl_dog

B2 纯四足机器人的 Isaac Lab 强化学习训练工程。

本仓库直接包含两个项目的完整源码和模型：

- `IsaacLab/`：NVIDIA Isaac Lab `v2.3.2`。
- `robot_lab/`：包含 B2 平地、复杂地形训练任务的 `v2.3.2`。

```bash
git clone https://github.com/jujjjk/lab_qxwl_dog.git
cd lab_qxwl_dog
```

Linux 环境安装、训练和回放命令见 [LINUX_B2.txt](LINUX_B2.txt)。
运行组合为 Python 3.11、Isaac Sim 5.1.0、Isaac Lab 2.3.2。

上游来源与提交号见 [sources.json](sources.json)。各项目保留原有许可证。
当前完成源码与模型静态检查，尚未在 Linux 上启动仿真或验证训练效果。
