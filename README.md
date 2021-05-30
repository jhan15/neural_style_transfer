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

#### Content feature maps

![car1](https://user-images.githubusercontent.com/62132206/120101413-471ebb80-c146-11eb-8730-213aa1e9a168.png)

#### Style feature maps

![car2](https://user-images.githubusercontent.com/62132206/120101417-4d149c80-c146-11eb-8cf3-a3fd3bfb852c.png)
![car3](https://user-images.githubusercontent.com/62132206/120101420-4dad3300-c146-11eb-96fd-45c17436f379.png)
![car4](https://user-images.githubusercontent.com/62132206/120101421-4e45c980-c146-11eb-836b-91ca4dbaa937.png)
![car5](https://user-images.githubusercontent.com/62132206/120101422-4ede6000-c146-11eb-969c-6a9edfcf1613.png)
![car6](https://user-images.githubusercontent.com/62132206/120101423-4ede6000-c146-11eb-8bc3-6b16a64e672c.png)

### Transfer results

![ car](https://user-images.githubusercontent.com/62132206/120101427-543baa80-c146-11eb-9e55-a0d306473799.png)

### One to Many

![one_to_many](https://user-images.githubusercontent.com/62132206/120101446-6a496b00-c146-11eb-8299-a2b190437476.png)

### Many to one

![many_to_one](https://user-images.githubusercontent.com/62132206/120102504-a9c68600-c14b-11eb-90b4-a94c014dae01.png)
