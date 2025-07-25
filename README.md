# 🎯 Industrial Machine Vision – Motion Tracking & Detection

This project showcases multiple computer vision techniques using **OpenCV in Python**, aimed at object tracking, motion detection, and visual analysis. It was developed as part of the ME4650 – *Industrial Machine Vision* module under the BSc. Mechatronics Engineering program at SLIIT.

---

## 🧠 Objectives

- 📌 Track objects using **template matching**
- 📌 Visualize motion using **dense optical flow**
- 📌 Log motion events frame-by-frame
- 📌 Save and annotate frames where motion is detected


---

## 🚦 Part 1: Object Tracking (Template Matching)

- Tracks an object (tennis ball) using `cv2.matchTemplate()`
- Computes and visualizes **trajectory path**
- Saves output as annotated video and image

> ✅ Technologies: `cv2.matchTemplate`, `cv2.VideoWriter`, `cv2.circle`, `cv2.imshow`

---

## 🌈 Part 2: Dense Optical Flow Visualization

- Captures video stream and applies **Farneback Optical Flow**
- Visualizes direction and magnitude using HSV mapping
- Optionally plots motion vectors using line overlays

> ✅ Technologies: `cv2.calcOpticalFlowFarneback`, `cv2.cvtColor`, HSV encoding

---

## 📊 Part 3: Motion Detection with Logging

- Computes motion by analyzing frame-to-frame optical flow magnitude
- Logs motion events in a human-readable format

```txt
Motion detected at frame 45, timestamp: 1715385258.00
Motion detected at frame 102, timestamp: 1715385279.33
...



