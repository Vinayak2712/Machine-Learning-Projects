# Face_mask_detection
Using computer vision and deep learning, this project detects face masks in real-time, helping enforce safety protocols during COVID-19. 
It analyzes images or live video feeds, identifying whether individuals are wearing masks or not, promoting public health and responsible behaviour.

# Face Mask Detection Project

Hello there! Welcome to my Face Mask Detection project repository. I'm excited to share with you the amazing work I've done in leveraging 
computer vision and deep learning techniques to develop a smart system that can detect whether individuals are wearing face masks or not, 
all in real-time. This project holds great significance in supporting public health efforts during the ongoing COVID-19 pandemic, promoting safety 
and responsible behaviour in public spaces.

## Embracing the Power of Data

To ensure the accuracy and reliability of my system, I began by importing a top-notch dataset directly from Kaggle.
Thanks to the remarkable `opendatasets` library and the Kaggle API, I effortlessly acquired a diverse collection of labelled images. 
These images play a crucial role in training my model to accurately recognize the presence or absence of face masks.

## Unleashing the Magic of Image Processing

Now, let's talk about the magic behind the scenes—image processing! I employed a range of image-processing techniques to whip my dataset into shape before training. 
I performed operations such as resizing, normalization, and even data augmentation to enhance the richness and robustness of my data. Through these transformations,
I unlocked hidden patterns and details, enabling my model to perform at its absolute best.


## The Art of Training

With a prepared dataset in hand, I delved into the exciting realm of training my model. I opted for the powerful Convolutional Neural Network (CNN) architecture, 
which excels in understanding and analyzing images. By feeding my lovingly converted numpy arrays into this network, I taught my model to distinguish between 
faces adorned with masks and those without.

## A Visionary Predictive System

Now, let's bring this project to life with a visionary predictive system. My system has the remarkable ability to process live video feeds or static images, 
making it a real-time hero. It swiftly detects faces with an impressive level of precision. By applying my trained CNN model to these detected faces, 
I can confidently determine whether an individual is wearing a face mask or not. Visual cues and feedback are then provided, empowering individuals and communities to make 
informed decisions and stay safe.


## Getting Started on Your Own Journey

Are you ready to embark on your own face mask detection adventure? Fantastic! Here's a quick guide to get you started:

1. Clone this repository to your local machine and navigate to the project directory.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the preprocessing script to unleash the magic of image processing and prepare your dataset.
4. Train the CNN model using the preprocessed dataset, empowering it to recognize face masks.
5. Launch the predictive system and witness the power of computer vision as it detects face masks in real-time or on static images.

## Let's Make a Difference Together

I strongly believe in the power of collaboration and community. If you have any suggestions, improvements, or bug fixes, I warmly welcome your contributions. Let's work together to enhance the accuracy and effectiveness of the Face Mask Detection system.

