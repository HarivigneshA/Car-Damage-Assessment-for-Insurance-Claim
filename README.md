# Car-Damage-Assessment-for-Insurance-Claim

## Objective:
Using computer vision and deep learning techniques to accurately classify vehicle damage to facilitate
claims triage and assess damage severity by training convolution neural networks.



## Use Case:
The rapidly expanding automobile industry highly backs the equally fast-growing auto insurance market. Although until now this industry has been solely based on traditional ways to make repair claims. In case of an unfortunate accident, the claims for the car damage needs to be filed manually. An inspector is required to physically analyze the vehicles to assess the damage and obtain a cost estimate. In such
situation, there is also the possibility of inaccurate settlements due to human errors. Automating such a
process with the help of deep learning and remote usage would make the process a lot more convenient
for both sides of the damage, increasing productivity of the insurance carrier and satisfaction of the
customer.



## Dataset:

```
http://ai.stanford.edu/~jkrause/cars/car_dataset.html
https://www.kaggle.com/hamzamanssor/car-damage-assessment?select=image
```



## Solution:
The model is required to pass through multiple checks that would first ensure that given image is that of
a car and then to ensure that it is in fact damaged. These are the gate checks before the analysis begins.
Once all the gate checks have been validated, the damage check will commence. The model will predict
the location of the damage as in front, side or rear, and the severity of such a damage as in minor,
moderate or severe.



## The model accepts an input image from the user and processes it across 4 stages:
  1. Validates that given image is of a car.
  2. Validates that the car is damaged.
  3. Finds location of damage as front, rear or side
  4. Determines severity of damage as minor, moderate or severe.



## Different models we are using for training:
  - ResNet50
  - InceptionV3
  - VGG16
  - VGG19

  

