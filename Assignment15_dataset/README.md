# Dataset
- drive link https://drive.google.com/file/d/1jJHcRoUUz-UVcgdFKibnwfa-5cZWwY5W/view?usp=sharing

### The original dataset was created by EVA5 group which is used for object recognition task using YOLO.

- The actual dataset is in the file called Images.zip
- All the images in the Images.zip were inferenced using MiDaS model https://github.com/intel-isl/MiDaS for ```Robust Monocular Depth Estimation``` and stored in a file called MiDaS_images.zip
- All the images in the Images.zip were inferenced using planercnn model https://github.com/NVlabs/planercnn ```3D Plane   Detection and Reconstruction from a Single Image``` and stored in a file called MiDaS_images.zip
- The bounding boxes for the original `Images.zip` file are there in Labels.zip file and there are other useful files too in the drive essentially train.txt and test.txt which have the 90-10 split of the entire dataset.