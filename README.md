```bash
echo "deb [trusted=yes] https://github.com/Lemvos/test_ros_DevOps/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/Lemvos_test_ros_DevOps.list
echo "yaml https://github.com/Lemvos/test_ros_DevOps/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-Lemvos_test_ros_DevOps.list
```
