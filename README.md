# 🏋️ Squat Counter with Real-Time Pose Estimation using YOLOv8
This project implements a real-time squat counter using YOLOv8 pose estimation to analyze body movements from video input. It tracks key human joints, draws the full skeleton, and intelligently counts squats based on the vertical movement of the hips relative to the knees.

# 🔍 What It Does:
Uses YOLOv8 Pose (Ultralytics) model to detect 17 key body joints.

Analyzes the hip and knee joint positions to detect squatting motion.

Counts a squat when a full down–up cycle is completed.

Overlays real-time feedback with skeleton lines, keypoints, and squat count.

Supports live webcam input or pre-recorded workout videos.

Saves the output video with pose annotations and squat counter.

# 🧠 Technologies Used:
Ultralytics YOLOv8

OpenCV (video processing and visualization)

Python

# 📹 Sample Output:
The model draws keypoints and skeletons on the person performing squats, tracks the movement of hips and knees, and displays the squat count live on the screen. The final annotated video is saved for reference.

# ✅ Future Enhancements:
Add calorie estimation based on reps

Enable rep detection for other workouts (e.g., push-ups, lunges)

Real-time dashboard with performance charts

# 🙌🏻Data Scientist 
Behara Pavan Kumar
