# Soccer Player Tracking and Team Classification from Broadcast Highlights: A Low-Cost Analytical Pipeline

<img width="1844" height="1034" alt="Player Tracking-Page-2 (4)" src="https://github.com/user-attachments/assets/28172252-38b5-4a2d-a19d-c5bfa5d2ce02" />

# 📝 Overview
This project provides a lightweight, low-cost pipeline for soccer player tracking and team classification using only broadcast highlight videos. The system uses YOLOv8 for player detection, ByteTrack for multi-object tracking, and KMeans clustering on HSV jersey colors with a majority-based correction for team classification. Simple preprocessing steps (i.e., frame skipping, field masking, and session segmentation) enable robust performance even under challenging broadcast conditions.

The entire workflow is designed to be run inside Google Colab, and each notebook already includes an Install Libraries section (**no manual setup or pip install -r requirements.txt is required**).

# 🔍 Key Features
🎥 Input: Broadcast highlight video
🧩 Player Detection: YOLOv8
🔗 Player Tracking: ByteTrack
🎨 Team Classification: KMeans clustering on HSV jersey colors + temporal majority correction
⚽ Analytics Output: Movement patterns, team visibility, coarse movement pattern, average on-screen position


