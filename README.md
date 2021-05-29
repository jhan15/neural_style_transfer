[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jhan15/neural_style_transfer/blob/master/neural_style_transfer.ipynb)

# neural_style_transfer

Transfer a content image into the style of a style image.

- A pre-trained VGG19 model is employed as feature extactor of content and style of an image.

- A weighted loss function of content loss, style loss, and total variation loss is used as the optimization objective.

- Visualize the feature maps to choose content and style layers.

- Adam optimizer is used for training.

## Usage

Try the code in google colab if you are interested in. However, you need to prepare some images youselves. I did it by copying the images stored in my google drive.

## Style transfer

### Visualize feature maps

Only the first 10 feature maps of each conv layer are displayed.

#### Content

![kth1](https://user-images.githubusercontent.com/62132206/120085684-7861a200-c0da-11eb-9e4d-ce051af57419.png)

#### Style

![kth2](https://user-images.githubusercontent.com/62132206/120085688-80b9dd00-c0da-11eb-871b-ec50131c1791.png)
![kth3](https://user-images.githubusercontent.com/62132206/120085689-81527380-c0da-11eb-9dcf-469625659e0f.png)
![kth4](https://user-images.githubusercontent.com/62132206/120085690-81eb0a00-c0da-11eb-8ac7-dae0f85379e8.png)
![kth5](https://user-images.githubusercontent.com/62132206/120085691-8283a080-c0da-11eb-8d9e-8d87cc8569ce.png)
![kth6](https://user-images.githubusercontent.com/62132206/120085692-8283a080-c0da-11eb-8652-37e9814b699e.png)

### Transfer results

![kth](https://user-images.githubusercontent.com/62132206/120085694-87485480-c0da-11eb-8f77-b5c686517310.png)

![kth](https://user-images.githubusercontent.com/62132206/120085704-9929f780-c0da-11eb-9d00-3c298bbc8eb5.gif)
