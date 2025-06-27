# PC-SETUP

This repository provides a comprehensive guide to set up your system for the Blazers project. It includes instructions for system partitioning, software installations, ROS2 setup, and library configurations.

---

## **1. System Setup and Partitioning**

### Steps:
1. **Watch Tutorial:** Follow this [YouTube tutorial](https://youtu.be/Z-Hv9hOaKso?si=tka_nrAbiIuYnxvy) for partitioning and installing Ubuntu.
2. **Partitioning:** Configure your laptop for dual-booting with Ubuntu 22.04.
3. **Ubuntu Installation Guide:** Use the [Ubuntu 22.04 Installation Guide](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview) for detailed steps.

---

## **2. Software Setup**

### Steps:
1. **Install Ubuntu 22.04**
   - Ensure Ubuntu 22.04 is installed successfully on your system.

2. **Install Essential Developer Tools:**
   ```bash
   sudo apt update
   sudo apt install build-essential curl git
   ```

---

## **3. ROS2 Humble Installation**

### Steps:
1. **Follow Documentation:** Use the official [ROS2 Humble Installation Guide](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html).
2. **Post-Installation Check:** Verify the installation by running:
   ```bash
   ros2 --version
   ```

---

## **4. Install Libraries and Packages**

### Steps:

### **YOLO (You Only Look Once)**
- **Installation Guide:** Follow the [YOLO GitHub Repository](https://github.com/AlexeyAB/darknet) for installation instructions.

### **OpenCV**
- **Basic Installation:**
  ```bash
  sudo apt install python3-opencv
  ```
- **Advanced Setup:** Refer to the [OpenCV Official Documentation](https://docs.opencv.org/master/df/d65/tutorial_table_of_content_introduction.html).

### **Additional Libraries:**
- **TensorFlow:**
  ```bash
  pip install tensorflow
  ```
- **PyTorch:**
  ```bash
  pip install torch torchvision torchaudio
  ```

---

## **5. Join the Blazers Organization**

1. **Collaboration:** Share repository access with team members.

---

## **6. Validation Checklist**

### Steps:
1. **System Check:**
   - Ensure Ubuntu 22.04 is installed and dual-boot is functional.
2. **ROS2 Verification:**
   - Run the following command to verify ROS2 Humble installation:
     ```bash
     ros2 --version
     ```
3. **Library Tests:**
   - Test YOLO and OpenCV installations with a sample project.
4. **Confirm Dependencies:**
   - Validate TensorFlow and PyTorch installations using test scripts.

---

## **Resources**

- [Ubuntu 22.04 Installation Guide](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)
- [ROS2 Humble Documentation](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)
- [YOLO GitHub Repository](https://github.com/AlexeyAB/darknet)
- [OpenCV Official Documentation](https://docs.opencv.org/master/df/d65/tutorial_table_of_content_introduction.html)

---

For any issues or support, please reach out to the Blazers technical team via the GitHub organization or email.
