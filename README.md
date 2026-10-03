## Jun Seok Kim

### About

I am an MSc student in Artificial Intelligence and Robotics at The Chinese University of Hong Kong, Shenzhen, advised by Prof. Rui Huang. I work on 3D perception that robots can rely on. My thesis studies uncertainty calibration for self-supervised monocular depth, and my capstone made Gaussian-based 3D occupancy differentiable and 7.2× faster.

Going forward, I want to build 3D scene representations that stay fast under limited compute, and perception that knows when it should not be trusted. I am applying to PhD programs for Fall 2027.

[Homepage](https://forestinblue.github.io) · [CV](https://forestinblue.github.io/media/CV.pdf) · ijunsuk9797@gmail.com

### Research

**Range-aware uncertainty calibration in self-supervised monocular depth** (MSc thesis, Jan 2026 – present)\
*Manuscript in preparation.*

### Projects

**[LocalAggTR](https://github.com/forestinblue/LocalAggTR)**: Differentiable voxelization for weakly supervised 3D occupancy (Sep 2025 – Dec 2025)\
Replaced GaussTR's heuristic, non-differentiable voxelizer with GaussianFormer's Local Aggregation CUDA operator, making the Gaussian-to-voxel step differentiable.\
→ 7.2× faster inference at comparable mIoU on nuScenes val, with the same checkpoint and head. Adopted by [the lab](https://myweb.cuhk.edu.cn/ruihuang)'s 3D Gaussian Splatting project for semi-supervised fine-tuning.

**[Geometric vs. Generative 3D Augmentation](https://github.com/forestinblue/3D-Augmentation-PointNet)**: Low-data point cloud classification (Jan 2025 – May 2025)\
Tested whether Point-E text-to-3D augmentation helps PointNet on ModelNet40 compared with geometric augmentation.\
→ Geometric augmentation raised accuracy by 6.5 points, while text-to-3D generative augmentation did not help.

**[Point Cloud Density and 3D Object Detection](https://github.com/forestinblue/3D-PointCloud-DownUpSampling)** (Jun 2025 – Jul 2025)\
Measured how a pretrained PointPillars degrades under reduced LiDAR density on nuScenes-mini, and whether simple upsampling recovers it.\
→ Voxel-grid thinning to one fifth of the points cost 2.1% of mAP, while random thinning to half cost about 4× more.
