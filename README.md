# :book: Text Translation Glasses
<h2>:memo: Abstract</h2>

This project is an attempt in this direction to build a novel smart glass which has the ability to extract and recognize text captured from an image and convert it to speech. OpenCV is an open source Computer Vision Library in which we can use many image related operations, in this project it is used to capture and modify real-time text from external camera. The text captured and modified is then processed by Tesseract-OCR and Efficient and Accurate Scene Text Detector (EAST) based on Deep Learning techniques to give output as coputer generated text. For actual Translation of text in many different languages is done by Natural Language Processing (NLP) a part of ML in which data sets of different language translations are given to train the model. After all this IoT part kicks in (It consists of a Raspberry Pi Zero microcontroller which processes the image captured from a webcam superimposed on the glasses of the person) as the actual hardware takes care of all the operations and algorithms to perform in small computer and can be wear as regular glasses. The recognized text is further processed by Google's Text to Speech (GTTS) API to convert to an audible signal for the user.   
 
<h2>:computer: Technologies and Hardware we are using</h2>

> **OpenCV  
> Tesseract OCR  
> Natural language Processing (NLP)  
> Raspberry Pi and Pi Cam (IoT)**  

<h2>:mega: Project Updates                                               /github/repo-size/:user/:repo</h2>

>[A Google Colab Link](https://colab.research.google.com/drive/1CXqfqXWVL0yzkF7lYm5rmpzvF4H02M5t?usp=sharing) - Here you can try the code.  

>Tessearact-OCR (Output for a clean image) -  
