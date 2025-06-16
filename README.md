# 🛑 Sleepy Alert ROS Node

A ROS node that plays a clear voice message **"Are you okay, driver?"** to alert sleepy drivers.  
Ideal for integrating into human-robot interaction systems involving driver drowsiness detection.

---

## 🚗 Features

- 🎙️ Plays high-quality MP3 voice alert
- 🧠 Designed to integrate with fatigue detection systems
- 🔁 Periodic or conditional playback (via ROS)
- 🐍 Written in Python 3 for ROS Noetic

---

## 🛠 Requirements

Make sure you are running this on a ROS Noetic system with Ubuntu 20.04.

### 📦 System dependencies

Install these if not already installed:

```bash
sudo apt update
sudo apt install ros-noetic-rospy mpg123
