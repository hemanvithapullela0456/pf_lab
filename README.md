# Smart Traffic Management System

📌 Overview
This project proposes an intelligent traffic management system designed to combat congestion in metropolitan areas. By leveraging computer vision (YOLOv3) and real-time data processing, the system dynamically adjusts traffic signal durations based on congestion levels. It integrates Here Maps API for geospatial tracking and provides a Tkinter-based UI for centralized traffic monitoring and control.

🎯 Key Features
✔ Real-time congestion detection using YOLOv3 object detection
✔ Dynamic traffic signal adjustment based on vehicle density
✔ Graph-based node representation of city intersections
✔ Centralized admin dashboard for monitoring and control
✔ Geospatial visualization using Here Maps API

🛠 Tools & Technologies
YOLOv3 – Real-time vehicle detection

OpenCV – Image processing

Here Maps API – Geospatial mapping

Tkinter – Python-based GUI

Python – Core logic & integration

⚙️ Workflow
Traffic Node Definition – City intersections are modeled as nodes in a graph.

Congestion Detection – YOLOv3 detects & counts vehicles from images.

Signal Adjustment – Red light durations are increased at neighboring nodes if congestion is detected.

UI Dashboard – Displays live traffic status and signal timings.
1.YOLO Version3 for Object Detection

2.Here Maps API

3.Tkinter(Python) for UI

📊 Results
✅ Accurate congestion detection under good lighting conditions
✅ Dynamic signal control improves traffic flow
⚠ Challenges: Low-resolution cameras, weather effects, real-time processing delays

🔮 Future Enhancements
Real-time video processing (instead of static images)

ML-based traffic prediction for proactive signal control

Priority routing for emergency vehicles

Scalability for larger city networks

📜 References
YOLOv3

OpenCV

Here Maps API

Tkinter Docs
