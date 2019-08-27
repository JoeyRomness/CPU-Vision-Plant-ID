# Plant Disease Identification

### Problem Statement
- Can an image recognition neural network be developed that looks at photos of crops and identifies whether or not they have a disease/sickness? 
- Further, if this works, could the neural network then be trained to specify what is likely wrong with said crop?

A major problem that farmers are finding themselves forced to cope with as climate change encroaches and herbicides/pesticides get stronger is crop disease. Sudden outbreaks of disease are devastating to any farmer. 99% of the time the crops need to be culled and the farmer ends up losing large amounts of money. Most farmers already exists on the knife’s edge financially, so a bad disease outbreak can spell doom for a farmer. Agriculture as a whole is already benefiting from, and could continue to benefit from the implementation of AI and automation.  Harvesting and planting on a large scale can already be automated, but what about maintenance and ensuring healthy crop yields? use of deep learning, I believe that a tool can be designed that can quickly help farmers identify when their crops are getting sick.

### Short Summary 
- Through the usage of convolutional neural networks I was able to create a high accuracy binary model that can look at images of rice, tomato, potato, and bell-pepper plants and identify whether they are healthy or not.
- I was unable to achieve my secondary goal and create a high accuracy multi-class model. I believe that it is possible to do this, but my own technological limitations hindered me.

### Future Work/ Recommendations 
 - Neural Networks, especially CNNs and anything having to do with computer vision, are very complicated. In the future I have a lot more to learn about implementing them. Specifically, I have a lot more to learn about pooling layers, dropout layers, and batch size. As I come to a better understanding I will be returning to my initial model to improve it more and more over time.
- Computational limitations were perhaps one of the biggest problems I ran into during this project. My home computer was simply not powerful enough to achieve the results I wanted to achieve. I was unable to resize images to the size I wanted, and I was also unable to use tools such as Keras' ImageDataGenerator. If I learn how to use an AWS instance, I can get the computational power I need so that I won't run into problems like this in the future and I'll likely gain the ability to improve my model scores significantly.
- In the future, gathering more data would also serve to help improve this project. If I want to create a model that can identify whether or not a CROP is healthy or not, I will need thousands of different images of hundreds to thousands of different crops. This is a daunting task, but it might be worth it for the amount of good a product like this could achieve for farming communities.





