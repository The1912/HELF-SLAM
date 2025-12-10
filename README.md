# HELF-SLAM


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
