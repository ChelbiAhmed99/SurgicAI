# An Introduction to AI in Surgery
Artificial intelligence is accelerating the development of novel solutions to enduring challenges in surgery. The complex, nonlinear nature of human disease is accurately represented by machine learning algorithms. Emerging robotic and microrobitic surgical platforms enhance surgical training and technical performance. Large, interoperable medical datasets and electronic health records offer new opportunities to leverage data in designing and implementing smarter health care systems. Yet, many obstacles prevent full realization of the advangates that could be gained by leveraging artificial intelligence techniques and technologies to improve surgical care. 
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
