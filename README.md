# Denoiser-Zoom-Data
Use AI to transform a blurry image into a beatiful picture


Script preprocessingPhoto: Create a pixelated version of each picture.
- reduce the dimension of each picture, then resize it again to original dimension.
- All the model of Test1 are trained with pictured reduced with the same ratio.
- All the model of Test2 are trained with pictured reduced with a random ratio.


Script model1:
- Use the first layers of vggnet then deconvolution to recreate the picture

Script model2:
- Add BatchNormalisation after the last VGG16 layer

![alt text](https://github.com/nakmuayFarang/Denoiser-Zoom-Data/blob/master/Test2/comparisonBetweenModel2.png)
