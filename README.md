# Soccer Player Tracking and Team Classification from Broadcast Highlights: A Low-Cost Analytical Pipeline

<img width="1844" height="1034" alt="Player Tracking-Page-2 (4)" src="https://github.com/user-attachments/assets/28172252-38b5-4a2d-a19d-c5bfa5d2ce02" />

# 📝 Overview
This project provides a lightweight, low-cost pipeline for soccer player tracking and team classification using only broadcast highlight videos. The system uses YOLOv8 for player detection, ByteTrack for multi-object tracking, and KMeans clustering on HSV jersey colors with a majority-based correction for team classification. Simple preprocessing steps (i.e., frame skipping, field masking, and session segmentation) enable robust performance even under challenging broadcast conditions.

The entire workflow is designed to be run inside Google Colab, and each notebook already includes an Install Libraries section (**no manual setup or pip install -r requirements.txt is required**).

# 🔍 Key Features
1. 🎥 Input: Broadcast highlight video (source: https://www.youtube.com/watch?v=ffAYByv2pLc)
2. 🧩 Player Detection: YOLOv8
3. 🔗 Player Tracking: ByteTrack
4. 🎨 Team Classification: KMeans clustering on HSV jersey colors + temporal majority correction
5. ⚽ Analytics Output: Movement patterns, team visibility, coarse movement pattern, average on-screen position

# 🚀 How to Run (Google Collab)
1. Clone the repository (https://github.com/durrotun04/soccer-player-tracking.git)
2. Upload the project folder (soccer-player-tracking) into: My Drive/Colab Notebooks/
3. Make sure your structure looks like this:
  
   <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/b6273f8e-a45b-4205-b262-56c8ecee5b87" />

4. Run all cells

Everything is preconfigured, **so no path editing is required.**

# 📜 Citation
If you use this repository, please cite:

xxx, x., & xxx, x. (2025). 
Soccer Player Tracking and Team Classification from Broadcast Highlights: A Low-Cost Analytical Pipeline.

# 🤝 Contributions
Contributions, pull requests, and discussions are welcome!
Feel free to open issues for bugs, suggestions, or improvements.


