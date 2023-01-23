# An Introduction to AI in Surgery
Artificial intelligence is accelerating the development of new solutions solutions to ongoing challenges in surgery. Machine learning algorithms accurately represent the complex, non-linear nature of human disease. Emerging robotic and microrobitic surgical platforms enhance surgical training and technical performance. Large, interoperable medical datasets and electronic health records provide new opportunities to use data in the design and implementation of smarter healthcare systems. Yet, many obstacles prevent full realization of the advangates that could be gained by leveraging artificial intelligence techniques and technologies to improve surgical care. 
To move forward, we must understand these obstacles and address them by collaborating across clinical domains and scientific disciplines.
# SurgicAI
In this notebook we will develop and train a simple NN (Neural Network) for surgical tool detection in laparoscopic images with the advent of high-level deep learning software libraries like tensorflow, many of the steps involved in working with neural networks are abstracted away, making the process much simpler. 
To use Notepad, you must first be signed in to your Google Account.

The neural network will take an input image containing the tip of a surgical tool and classify that image as showing Grasper, Hooks, Clipper, and scissors. 
For this, we will use Cholec-tinytools, a surgical tool tip image dataset generated from Cholec80. Cholec80 is a widely used dataset containing 80 laparoscopic cholecystectomy videos annotated with surgical steps and tools published by Kaggle and the CAMMA research group (University of Strasbourg, France).


<img src="https://github.com/ChelbiAhmed99/SurgicalIA/blob/main/dataset.png" width="700" heigh="700">

# Dependency
The model depends on the following libraries:  

Tensorflow (1.3 < tf < 2.0)   
Opencv   
imageio   
imageio-ffmpeg   
matplotlib   
Python >= 2.7
# System Requirements:

The code has been test on Windows operating system. It runs on both CPU and GPU. Equivalence of basic OS commands such as unzip, cd, wget, etc. will be needed to run in Linux or Mac OS.
# Result  
<img src="https://github.com/ChelbiAhmed99/SurgicalIA/blob/main/result.png" width="700" heigh="700">  

# Dataset  

You can find the dataset here https://drive.google.com/drive/u/0/folders/1WlnSAFUtRiHcX48nr1PGS3lAiIAXXLQT
