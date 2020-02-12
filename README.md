# NeuralStyleTransfer
<br>

- <b>This project experiments with the choice of Style Image for effective Neural Style Transfer.</b>

- <b>The results show that the Content and Style Images need to be semantically similar for the pre-trained weights to effectively generate a style transferred image.</b>

- <b>Webinar explaining this:</b> https://youtu.be/PqBhVeCGTYE 

### 1. What if Picasso painted me

#### Style Image:
![picasso_small](https://user-images.githubusercontent.com/26281528/50651607-e78a4900-0fa9-11e9-9315-80dcd2d1bad5.jpg)

#### Stylised Image:
![picasso](https://user-images.githubusercontent.com/26281528/50650922-d4767980-0fa7-11e9-94d8-a959bc2e0c5d.png)


#### Observation:
The Style Image is an abstract painting where, the facial features are not explicit. Hence, the color/style bleeds around the face in the content image. 

### 2. What if Hockney painted me

#### Style Image:
![hockney](https://user-images.githubusercontent.com/26281528/50651253-cbd27300-0fa8-11e9-8c70-aa3fee123883.jpg)

#### Stylised Image:
![hockney_art](https://user-images.githubusercontent.com/26281528/50650975-f1ab4800-0fa7-11e9-89a8-ba5d3a3f9bb6.jpg)

#### Observation:
The Style Image has only the sky and the landscape. Those features are mapped correctly to the content image. However, since there is no human in the style image, the stylization looks odd.

### 3. Some examples of Stylization with semantically similar Content and Style Images:

![image](https://user-images.githubusercontent.com/26281528/74373516-a4341800-4e02-11ea-8a30-9c1d3f06f9e4.png)

![image](https://user-images.githubusercontent.com/26281528/74373572-c168e680-4e02-11ea-9ce9-263b1cb3d877.png)
