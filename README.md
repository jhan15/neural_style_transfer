[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jhan15/neural_style_transfer/blob/master/neural_style_transfer.ipynb)

# neural_style_transfer

Transfer a content image into the style of a style image.

- A pre-trained VGG19 model is employed as feature extactor of content and style of an image.

- A weighted loss function of content loss, style loss, and total variation loss is used as the optimization objective.

- Adam optimizer is used for training.

## Usage

Try the code in google colab if you are interested in.

## Style transfer

### Visualize feature maps

#### Content

![t1](https://user-images.githubusercontent.com/62132206/120069394-18d9a700-c086-11eb-9716-ad4273b5f88c.png)

#### Style

![t2](https://user-images.githubusercontent.com/62132206/120069401-28f18680-c086-11eb-9bc6-d6ae725b7709.png)
![t3](https://user-images.githubusercontent.com/62132206/120069403-2a22b380-c086-11eb-9ad6-4d268188b203.png)
![t4](https://user-images.githubusercontent.com/62132206/120069404-2abb4a00-c086-11eb-8849-7cbaeabc7bf4.png)

### Results

![t5](https://user-images.githubusercontent.com/62132206/120069364-e9c33580-c085-11eb-9525-c26fe5a1d25c.png)

