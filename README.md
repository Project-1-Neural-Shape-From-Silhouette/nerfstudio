# Adapting Neural Radiance Fields for Shape-from-Silhouette Reconstruction
## Contribution
### Yuhan Liu
1. Modified the traditional NeRF pipeline to adapt it for binary data, including changes to the neural network, adaptations to the renderer, and modifications to the exporter.
2. Optimized the generated meshes to capture finer details.
3. Utilized Blender to enhance mesh visualization by applying various textures.

### Chuyingjia Feng
1. Image Segmentation: Developed scripts for image segmentation using UNet, Otsu's Thresholding, and GrabCut algorithms to effectively extract regions of interest from images. https://github.com/Project-1-Neural-Shape-From-Silhouette/Image-Segmentation
2. Extracted Camera Parameters Using COLMAP: Utilized binary masks from GrabCut with COLMAP to enhance 3D reconstruction by focusing on relevant image areas, improving feature matching and camera pose estimation.
3. Modified Loss Functions: Assessed six different loss functions (L1, MSE, Smooth L1, Dice, Custom BCE, Charbonnier) to optimize model training.
   
### Ruqing Zhu
1.Installation of Nerfstudio and related Python libraries, analyzed and compared various traditional NeRF methods to select the final approach.
2.Modification of the traditional NeRF pipeline: changed the exporter to enable output conversion from RGB to binary format.
3.Optimization of mesh export parameters: Selected three sets of top-performing parameters for TSDF results.
