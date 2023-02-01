# Nueral_Style_Transform

## About

### Style transfer consists in generating an image with the same "content" as a base image, but with the "style" of a different picture (typically artistic).
### This code provides a TensorFlow implementation and pretrained models for **Artistic Neural Style Transfer**, as described in the paper [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576) by Leon A. Gatys, Alexander S. Ecker, Matthias Bethge.

## Folder Structure:

```bash
.
├── #1report     - report of the implementation
├── #2nueral_style_transform.ipynb                - implentation using pretrainged vgg16 using imagenet
├── #3vgg.ipynb       - implentation using vgg16 trained with your dataset
├── README.md
```
## vgg structure
### VGG16 is a convolution neural net (CNN ) architecture :
1. 2 x convolution layer of 64 channel of 3x3 kernal and same padding
2. 1 x maxpool layer of 2x2 pool size and stride 2x2
3. 2 x convolution layer of 128 channel of 3x3 kernal and same padding
4. 1 x maxpool layer of 2x2 pool size and stride 2x2
5. 3 x convolution layer of 256 channel of 3x3 kernal and same padding
6. 1 x maxpool layer of 2x2 pool size and stride 2x2
7. 3 x convolution layer of 512 channel of 3x3 kernal and same padding
8. 1 x maxpool layer of 2x2 pool size and stride 2x2
9. 1 x Dense layer of 4096 units
10. 1 x Dense layer of 4096 units
11. 1 x Dense Softmax layer of 2 units
<img src="https://miro.medium.com/max/1400/1*NNifzsJ7tD2kAfBXt3AzEg.png" width="500" height="500" />

## dataset:
### dataset it's from kaggle [best artwork all time](https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time=250x250) 
### it contain best artwork of all time from famous artists
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ52aVMnLFT-EF2JZUefZOzdr8p7bIr2eE8s1F3NaRUjkfqTbFnAhMt9BsfhX04eIyH6Ek&usqp=CAU" width="250" height="250" /><img src="https://render.fineartamerica.com/images/rendered/medium/print/8/6.5/break/images/artworkimages/medium/1/the-starry-night-vincent-van-gogh.jpg" width="250" height="250" />
## result
  




