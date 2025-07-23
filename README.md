# Real-Time-Human-Detection-Pose-Estimation-with-Entry-Exit-Counting

This project explores how computer vision can be used to detect, track, and count humans in real time using standard webcams or video footage, all while keeping the system fast enough for practical use on a standard CPU. It also includes pose estimation of the hand using MediaPipe, making this a lightweight human activity analyzer you can run with minimal hardware.

> Project Summary
The repository consists of two main notebooks:

human_count.ipynb – Detects people, tracks individuals with unique IDs, visualizes their movement paths, and counts how many enter and exit through a virtual line.

human_pose_estimation.ipynb – Detects human pose landmarks, especially hand poses, in real time using MediaPipe's hand tracking solution.

Both notebooks are fully open-source and optimized to run on a local machine without the need for a GPU.

> Objectives
* Detect humans using classical and modern vision techniques

* Track individuals across frames using advanced OpenCV trackers

* Count how many enter and exit a specific zone

* Perform real-time hand pose estimation

* Optimize FPS to make detection smooth on mid-range CPUs

> Tech Stack
Language: Python 3.x

Libraries:

* OpenCV (opencv-contrib-python)

* NumPy

* imutils

* MediaPipe

* Runtime: Jupyter Notebook (.ipynb)

* Hardware: Works on standard laptops (no GPU required)

> Clone the repository:

bash
git clone https://github.com/yourusername/human-analytics.git
cd human-analytics



Install dependencies:

bash
pip install -r requirements.txt
Run the notebooks in Jupyter or VS Code:

Launch human_count.ipynb to try human detection and tracking.

Launch human_pose_estimation.ipynb to test hand landmark detection.

Make sure your webcam is enabled and accessible if you're using it as the source.

⚙️ Features
✔️ Real-time human detection using HOG/MediaPipe
✔️ Multiple person tracking with bounding boxes and IDs
✔️ Entry/Exit zone counter with virtual line
✔️ Hand pose recognition (21-point detection)
✔️ Smooth and optimized FPS for lower-spec systems
✔️ Supports video input or webcam

✅ What's New / Novelty
* Optimized detection FPS via strategic frame skipping and resizing

* Accurate Entry–Exit counting

* Pose estimation focused on hands, making it useful for gesture-based applications.

* CSRT/MOSSE-based tracking, faster than deep learning detectors but still reliable.


> Potential Applications

* Smart entrance/exit counters

* Public safety monitoring

* Interactive installations or exhibitions

* Retail analytics / foot traffic estimation

> Author & Credits
👤 Deep Khimani
📧 deepkhimani@gmail.com


This project was built as part of an exploration into real-time computer vision on resource-constrained systems. Thanks to the OpenCV and MediaPipe teams for their excellent libraries.

📄 License
This project is open-source for educational and non-commercial use. If you plan to use it commercially, please get in touch.
