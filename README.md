# Object-Detection-with-Trash-images

This project contains my work from my one month internship as a Data Scientist in Koncern IT at Københavns Kommune. During my internship I had the opportunity to participate in a Waste detection project, where I was exposed in the latest techniques in computer vision with python. I had the chance to learn and use libraries such as OpenCv and Pillow, how to do Data Augmentation and create Synthetic data.

---
In this project I have enlarged a dataset of images using different Augmentation techniques such as

- transparent background

![plastic491resized](https://user-images.githubusercontent.com/110908916/183945998-e839e860-fc49-4f9e-bdd4-d67edb3968a5.png)  ![plastic491transparent_background](https://user-images.githubusercontent.com/110908916/183946413-06186662-7865-43b9-9eec-0f08ada312d0.png)

- image sharpening

![plastic287transparent_background](https://user-images.githubusercontent.com/110908916/183970660-ea236313-5075-4e32-bf0d-e12a32314be3.png) ![plastic287transparent_background_sharpened](https://user-images.githubusercontent.com/110908916/183970936-8f34f97b-0ecb-43e7-b1f9-c4083bdd1b50.png)

- rotation

![glass26resizedtransparent_background](https://user-images.githubusercontent.com/110908916/183957692-ee892513-6c9a-4a1d-9194-f297703c699a.png) ![glass26resizedtransparent_backgroundrotate135](https://user-images.githubusercontent.com/110908916/183957883-2dae7a96-a79f-473e-857f-25667669fe25.png)


- perspective transformation

![plastic17resizedtransparent_background](https://user-images.githubusercontent.com/110908916/183968403-d9df29ee-12f5-48cc-8e1b-978bf5bcc8bb.png) ![plastic17transparent_background_Perspective_Transform](https://user-images.githubusercontent.com/110908916/183966285-75ddde10-06ff-4f5a-a7eb-aa04f7d54163.png)



- wave transformation

![plastic489transparent_background](https://user-images.githubusercontent.com/110908916/183955476-9603f05b-9811-461b-a5f5-01278b0b1687.png) ![plastic489transparent_background_wave](https://user-images.githubusercontent.com/110908916/183955787-1382aff6-ca1e-4be6-b275-09c220b4166b.png)

- add different background


![plastic17_mirror_rotate45_backgroundresized](https://user-images.githubusercontent.com/110908916/183963834-a51041fd-d0df-405c-9606-b113056200b7.png) ![plastic17_sharp_rotate90_backgroundresized](https://user-images.githubusercontent.com/110908916/183963952-db18759f-7ab8-49ff-b4a4-6b03687b7015.png) ![plastic14_sharp_rotate0_backgroundresized](https://user-images.githubusercontent.com/110908916/183964250-75ce6371-f9a1-444a-be78-015bd9213b73.png) ![plastic14_mirror_rotate180_backgroundresized](https://user-images.githubusercontent.com/110908916/183964323-dcb60b2c-58d3-4670-9d4a-b59667b68276.png)

---

I used the YOLOv7, which was trained in Google colab, on data that I created using the above data Augmentation techniques and using only 5 categories (plastic, paper, metal, glass, cardboard).

Here are some examples after training the model:

![test_batch2_labels](https://user-images.githubusercontent.com/110908916/183973298-30d9985f-960a-4c30-8a66-f0db9b665b6a.jpg)







