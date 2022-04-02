# Flower-Recognition

1. Imported data and assigned labels
2. Visualizing some random images
3. Encoding target variable with onehotencoding
4. Spliting data in train and test
5. Data agumentation on training set
    - Rotation
    - Zooming
    - Horizontal Shift
    - Vertical Shift
    - horizontal flip
    - vertical flip
6. Modeling.
    - Custom Implementation
    - VGG16 & Vgg19
    - RESNETs

## Custom CNN model
### Architecture:
![image](https://user-images.githubusercontent.com/22805226/161369392-6793c7ec-433e-4c7b-9ee4-50ab258d7ede.png)

### Result:
#### Achieved maximum accuracy of 79%

> **Correctly classified** </br>
![image](https://user-images.githubusercontent.com/22805226/161369491-371875af-ba1c-4798-96bf-b9ab6879dbc0.png)

> **Error** </br>
![image](https://user-images.githubusercontent.com/22805226/161369613-971e79b0-0573-4395-8774-52c6fa07f386.png)

> **Matrix** </br>
![image](https://user-images.githubusercontent.com/22805226/161369727-a19db62e-1a75-4766-aa02-f7fcf525b950.png)

</br></br>
## VGG16
### Architecture - Used pretrained VGG16 model without top layer
![image](https://user-images.githubusercontent.com/22805226/161371483-0f0c925e-8632-4cf3-a809-5b8d6eb8f11a.png)

### Result
#### Achieved maximum accuracy of 85.76%

## VGG19
### Architecture - Used pretrained VGG19 model without top layer
![image](https://user-images.githubusercontent.com/22805226/161371913-cdd9961c-791b-49b7-b6b8-ca2c17822589.png)

### Result
#### Achieved maximum accuracy of 84.61%


</br></br>
-----------------------------------
## RESNET50-V2
-----------------------------------
### Architecture - Used pretrained RESNET50_v2 model without top layer
![image](https://user-images.githubusercontent.com/22805226/161372058-58929fbe-3ddf-42fe-9989-3150c8f56306.png)

### Result
#### Achieved maximum accuracy of 88.5%

</br></br>
-----------------------------------
## RESNET101-V2
-----------------------------------
### Architecture - Used pretrained RESNET101_v2 model without top layer
![image](https://user-images.githubusercontent.com/22805226/161372198-ed77cf23-9785-459d-9b95-a20b290e28d4.png)

### Result
#### Achieved maximum accuracy of 85.6%

</br></br>
-----------------------------------
## RESNET152-V2
-----------------------------------
### Architecture - Used pretrained RESNET152_v2 model without top layer
![image](https://user-images.githubusercontent.com/22805226/161372257-fab66465-a725-4fd4-9376-f557babd9078.png)

### Result
#### Achieved maximum accuracy of 87.2%


</br></br></br>
# Maximum Accuracy achived is 88.5% using RESNET50
