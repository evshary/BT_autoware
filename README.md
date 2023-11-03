# BT on Autoware

Demo how to use behavior tree to control the Autoware.

# Build

* Get the code

```bash
mkdir -p ~/bt_autoware_ws/src
cd ~/bt_autoware_ws/src
git clone https://github.com/evshary/BT_autoware.git
```

* Download dependencies & Build

```bash
source /opt/ros/<ROS2_DISTRO>/setup.bash
cd ~/bt_autoware_ws
# Install dependencies
rosdep install --from-paths src --ignore-src -r -y
# Build
colcon build --symlink-install
```
