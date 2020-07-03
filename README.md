# OpenSprayerSegDataset
A dataset for semantic segmentation created using overlapping docks from the Open Sprayer Dataset. It consists of 4172 RGB images containing weeds from the Open Sprayer Dataset with size (256,256,3), and their corresponding binary masks with size (256,256,1) where '0' corresponds to pixels for the crop, and '1' corresponds to pixels for the weeds. The Open Sprayer Dataset contains only 1173 images containing weeds, thus these images and their masks were augmented by horizontal flipping, vertical flipping, and rotation to reach the 4172 samples. These masks were created using Gimp - a free and open-source image manipulation program. 

[Download the Dataset](https://drive.google.com/file/d/14Dwe2y0qjXB8cAwRO14ifwfPWZ4pP_K8/view?usp=sharing)

## Samples from the created dataset.
![fig6a](https://user-images.githubusercontent.com/29514438/86437885-1a3e0a80-bd23-11ea-9d7e-73de0eabf982.jpg)
![Sample1Mask](https://user-images.githubusercontent.com/29514438/86437890-1ca06480-bd23-11ea-98cf-e498a0bb0b96.jpg)
![Sample2](https://user-images.githubusercontent.com/29514438/86437894-1d38fb00-bd23-11ea-8ead-78dbcd738e09.jpg)
![Sample2Mask](https://user-images.githubusercontent.com/29514438/86437900-1f02be80-bd23-11ea-90bf-a09ec7bd7c8d.jpg)
![Sample3](https://user-images.githubusercontent.com/29514438/86437901-1f9b5500-bd23-11ea-86e9-df0cfab58584.jpg)
![Sample3Mask](https://user-images.githubusercontent.com/29514438/86437906-21651880-bd23-11ea-87c3-b333660ceb86.jpg)
