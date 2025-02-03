# NEURAL-STYLE-TRANSFER

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: RUSHI PRAKASH SHINDE

*INTERN ID*: CT08LJW

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: Neural Style Transfer Using TensorFlow and Gradio
Introduction
Neural Style Transfer (NST) is a deep learning technique that applies the artistic style of one image to another while preserving the content of the original image. This task involves implementing an NST model using a pretrained deep learning model from TensorFlow Hub and integrating it with an interactive UI using Gradio. The goal is to create an application that allows users to upload a content image and a style image, process them through a neural network, and generate a stylized image that blends both inputs.

This implementation is designed to be user-friendly, efficient, and interactive, making it suitable for anyone interested in image processing, artificial intelligence, or creative applications of deep learning. The use of Google Colab ensures that the model runs on cloud-based GPUs, making computations faster without requiring high-end hardware.

Understanding Neural Style Transfer
NST works by leveraging Convolutional Neural Networks (CNNs) to extract and manipulate features from images. The technique, originally introduced by Gatys et al. (2015), involves three main components:

Content Image – This is the image that retains its structure, shapes, and objects.
Style Image – This is the image that provides the artistic look, such as brush strokes, textures, and colors.
Generated Image – The output image is created by blending the content of the first image with the style of the second image.
The NST model extracts content features and style features from deep layers of a CNN and recombines them to create a new artistic output.

Key Features of This Implementation
This project utilizes a pretrained model available on TensorFlow Hub, making it easy to apply neural style transfer without the need for extensive training. Below are the key features:

✅ Pretrained Model from TensorFlow Hub – The model is pre-trained on large datasets, ensuring high-quality style transfer with minimal computation.
✅ User-Friendly Interface with Gradio – The interface allows users to easily upload images and view real-time results.
✅ Real-Time Image Processing – The model processes images instantly, allowing users to experiment with different styles quickly.
✅ Cloud-Based Execution in Google Colab – Ensures fast computation using cloud GPUs.
✅ Automatic Image Resizing – The script ensures that all images are resized to 256x256 pixels for consistency.
✅ Fully Interactive UI – Allows users to select different images and generate stylized results with a single click.

Technologies Used
This implementation leverages several libraries and frameworks to ensure a smooth experience:

TensorFlow & TensorFlow Hub – Used for loading and executing the neural style transfer model.
NumPy & OpenCV – Used for processing and manipulating images.
PIL (Pillow) – Helps in handling and converting images between different formats.
Gradio – Provides a simple web-based UI for uploading images and viewing results interactively.
Google Colab – Enables cloud-based execution without requiring high-end local hardware.
How the Code Works
The code follows a structured approach to process and stylize images:

Installing Dependencies – Ensures all required libraries are installed using pip install gradio.
Loading the Pretrained Model – The script loads the Magenta Arbitrary Image Stylization model from TensorFlow Hub.
Processing the Images – Converts images to RGB format, normalizes pixel values, and resizes them to 256x256.
Applying Neural Style Transfer – The processed content and style images are passed to the model, which generates the stylized output.
Displaying the UI – Gradio provides an interactive interface where users can upload images and view results.
Launching the Application – The script runs the UI, allowing users to perform style transfer easily.
Step-by-Step Instructions for Users
To use this neural style transfer tool, follow these steps:

1. Upload a Content Image
Select an image that serves as the base of the final output.
This image will retain its structure, shapes, and objects.
2. Upload a Style Image
Select an image that contains the artistic style you want to apply.
This image provides textures, brush strokes, and colors for the final result.
3. Click the "Generate" Button
The model will process both images and apply style transfer.
It will output a stylized version of the content image with the characteristics of the style image.
4. View and Download the Result
The output image is displayed on the screen.
Users can download the image for future use.
Practical Applications of Neural Style Transfer
NST has a wide range of real-world applications, including:

✅ Artistic Image Generation – Transform photos into paintings resembling Van Gogh, Picasso, or Monet.
✅ Photo Editing & Filters – Apply artistic effects to images, similar to apps like Prisma.
✅ Video Style Transfer – Extend the concept to video processing for creative effects.
✅ Game Graphics Enhancement – Use NST for texture transfer in video games.
✅ AI-Generated Content – Assist designers and artists in creating unique digital artworks.

Why Use Gradio for UI?
Gradio is chosen for its simplicity and flexibility. It allows users to:

🎨 Upload images easily via drag-and-drop or file selection.
⚡ See real-time results without complicated installations.
🌐 Run on Google Colab without needing a local setup.
📁 Download the output in just one click.

Conclusion
This project provides an interactive and efficient implementation of Neural Style Transfer using TensorFlow, TensorFlow Hub, and Gradio. With a simple UI, users can upload content and style images to generate stunning artistic outputs instantly. The use of a pretrained model ensures high-quality results without requiring deep learning expertise.

By leveraging cloud-based execution in Google Colab, users can run this application on any device, making AI-powered creativity accessible to everyone. Whether you're an artist, developer, or AI enthusiast, this project is a great way to explore the power of deep learning in image processing. 🚀

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/d470cd6c-9552-4022-9391-11de2f46dacf)
![Image](https://github.com/user-attachments/assets/c069808f-d456-4158-8ded-dc8706c95996)

