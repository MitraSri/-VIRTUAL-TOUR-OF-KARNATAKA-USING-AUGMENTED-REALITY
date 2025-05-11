# -VIRTUAL-TOUR-OF-KARNATAKA-USING-AUGMENTED-REALITY
This project presents a virtual tour experience of the Indian state of Karnataka using an augmented reality (AR) camera. Karnataka is renowned for its rich cultural heritage, historical monuments, picturesque landscapes, and diverse wildlife. The aim of this virtual tour is to provide users with an immersive and interactive experience, allowing them to explore Karnataka's prominent landmarks and natural beauty from the comfort of their own homes.

The virtual tour also includes interactive features, allowing users to engage with the environment. Users can manipulate the AR camera to change viewpoints, zoom in on specific elements, and interact with virtual objects, enhancing their exploration experience. Moreover, social sharing functionalities enable users to capture and share their virtual tour experiences with others, fostering a sense of community and encouraging further exploration of Karnataka. 

Here the app displays two monuments which are Hampi and Gol Gumbaz on top of the Karnataka Map. There are three buttons respected to each monument which are shown and the third button directs to wikipedia page.
The steps are as follows:

1. Create Image Target
Image targets in augmented reality (AR) refer to real-world images or pictures that act as triggers for displaying virtual content or augmentations. When an AR camera detects an image target, it recognizes the image and overlays digital content onto it, creating an interactive and immersive experience for the user.This is done with the help of vuforia engine. Vuforia is an augmented reality (AR) platform that provides tools and technologies for creating AR experiences. One of the key components of Vuforia is the Target Manager, which is a web-based portal that allows you to create and manage image targets for your AR applications. Thr Karnataka map is used as the image target.
![image](https://github.com/user-attachments/assets/1101a480-e70c-473c-8562-6281067395b1)

2. Importing assests

In order to show the monuments, respective assests are used. These assets were taken from SketchUp which is a website specially for using readymade assets.These are imported in the project done in Unity Editor.

3. C# Script
   
C# is used for the function of the buttons. This is a better option to customize our idea than using available options. Here it is used for the button response to the wikipedia page.
![image](https://github.com/user-attachments/assets/80fca874-decb-4a3a-b761-9fb5285e920b)
This is the code used.

4.Building application

Now we have to add the components in the scene to make them work together. Unity editor is used to add components, buttons, code and building into app. First the assests are placed on top of the image target and all of these are placed above of the canvas as shown in the image.

![image](https://github.com/user-attachments/assets/375f29ec-e43e-47d9-8787-90f0da04338f)


Now the buttons are added next to the image target.

![image](https://github.com/user-attachments/assets/99799992-cf52-4759-be32-d22041d7a536)


Next the text is also added which shows the description of the monument while the button is clicked.

![image](https://github.com/user-attachments/assets/7a6c9284-bb13-4eae-887b-fbcbd06d4c43)


Finally the project is simulated then built into an .apk file which can be installed on mobile devices.

![image](https://github.com/user-attachments/assets/2ae51bfe-413c-475d-895f-52d3a07bca48)







