## Jun Seok Kim

MSc student in Artificial Intelligence and Robotics at The Chinese University of Hong Kong, Shenzhen (advisor: Prof. Rui Huang).\
**Research interests:** Uncertainty-aware 3D perception, depth estimation, 3D scene representation, robust perception for robotics.

### Research

**Uncertainty calibration for self-supervised monocular depth estimation** (MSc thesis, Jan 2026 – present)\
Making depth-uncertainty estimates reliable across all distances for trustworthy 3D perception.\
*In preparation for CVPR 2027.*

### Projects

**[LocalAggTR](https://github.com/forestinblue/LocalAggTR)**: Differentiable voxelization for weakly supervised 3D occupancy (Sep 2025 – Dec 2025)\
Replaced GaussTR's heuristic, non-differentiable voxelizer with GaussianFormer's Local Aggregation CUDA operator, making the Gaussian-to-voxel step differentiable.\
→ 7.2× faster inference (4.09 → 0.57 s/sample) at comparable mIoU (0.111 → 0.114) on nuScenes val (same checkpoint and head).

**[Geometric vs. Generative 3D Augmentation](https://github.com/forestinblue/3D-Augmentation-PointNet)**: Low-data point cloud classification (Jan 2025 – May 2025)\
Tested whether Point-E text-to-3D augmentation helps PointNet on ModelNet40 (25 training samples per class) compared with geometric augmentation.\
→ Geometric augmentation raised test accuracy from 66.6% to 73.1%, while Point-E augmentation did not help (65.1%) (1 seed, N = 910). This is a negative result for text-to-3D augmentation at this scale.

**[Point Cloud Density and 3D Object Detection](https://github.com/forestinblue/3D-PointCloud-DownUpSampling)** (Jun 2025 – Jul 2025)\
Measured how a pretrained PointPillars degrades under reduced LiDAR density on nuScenes-mini, and whether simple upsampling recovers it.\
→ In a 2-frame pilot, voxel-grid downsampling to 21% of points preserved mAP (0.229 vs 0.234), and random downsampling to 50% lowered it to 0.216.

### Contact

ijunsuk9797@gmail.com
