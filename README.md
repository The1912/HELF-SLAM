# HELF-SLAM
<img width="691" height="452" alt="image" src="https://github.com/user-attachments/assets/644e5864-5ddf-4eb7-bc62-2822d2b32a5a" />
<img width="635" height="385" alt="image" src="https://github.com/user-attachments/assets/dd5ac606-fc14-4ae7-8b17-49249a27c911" />
<img width="820" height="393" alt="image" src="https://github.com/user-attachments/assets/890b62ca-2a4a-4f84-8446-5853b8d95ee6" />


HELF-SLAM is a lightweight and efficient visual SLAM system that combines a hybrid learned frontend with a classical optimization backend.  
It achieves real-time performance on a single GPU with low memory usage while maintaining robustness under challenging conditions such as low texture, illumination changes, and motion blur.

## Key Features
- Real-time SLAM with an efficient learned frontend  
- Robust tracking using adaptive keypoint sampling and learned features  
- Low GPU memory usage (~3 GB), suitable for mobile or edge devices  
- Optimized backend with bundle adjustment  
- Supports standard benchmarks such as TUM, EuRoC, and KITTI  

## Performance
- Runs at 30 FPS on a laptop GPU  
