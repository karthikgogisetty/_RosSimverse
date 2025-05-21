# 🌌 rosSimverse

**rosSimverse** is a focused repository for ROS-based simulations using URDF/XACRO, Gazebo environments, and ROS launch files. All content is centered on ROS 1 (Noetic) workflows and robot modeling using simulation tools.

---

## 🧭 Table of Contents

| Module/Folder     | Description |
|------------------|-------------|
| `GazeboBot/`      | Contains a basic robot model defined using `model.sdf` and `model.config`, suitable for spawning in Gazebo via ROS. |
| `HexaCopter/`     | Simulates a hovering drone using a `firefly_base.xacro` robot model and a ROS launch file for dynamic testing in Gazebo. |

---

## 🤖 Features Covered

- Build robots using URDF/XACRO and ROS integration
- Simulate robot models in Gazebo environments
- Launch robots via `roslaunch` with pre-defined states
- Integrate simple control logic (e.g., hover using MAVROS)

---

## 📚 ROS Learning Resources

### 🚦 ROS Core

- [ROS Wiki (Noetic)](http://wiki.ros.org/noetic)
- [ROS Tutorials](http://wiki.ros.org/ROS/Tutorials)

### 🏗 Robot Modeling

- [URDF & XACRO](http://wiki.ros.org/urdf/Tutorials)
- [Gazebo + ROS Integration](http://wiki.ros.org/gazebo_ros_pkgs)

### 🧰 Useful Packages

- [`robot_state_publisher`](http://wiki.ros.org/robot_state_publisher)
- [`joint_state_publisher`](http://wiki.ros.org/joint_state_publisher)
- [`gazebo_ros`](http://wiki.ros.org/gazebo_ros)
- [`mavros`](https://github.com/mavlink/mavros)

---

## 🛠 Requirements

- ROS 1 (tested on Noetic)
- Gazebo 9 or 11
- `catkin_make` workspace setup
- Optional: RViz, MAVROS tools

---

## 🚀 Quick Start

```bash
cd ~/catkin_ws/src
git clone https://github.com/<your-username>/rosSimverse.git
cd ~/catkin_ws
catkin_make
source devel/setup.bash
```