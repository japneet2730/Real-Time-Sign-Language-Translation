# Real-Time-Sign-Language-Translation

The objective was to develop a system that would detect sign language gestures in the ASL format, interpret and translate it into text. The converted text is then displayed on the screen as output. 

## Scope: 
The Scope of this project is to develop a cost-effective Translation and interpretation application for the Deaf and Mute to improve communication and accessibility. In possible future aspect, the project can be further developed to recognize entire words and gestures. A more interactive and multipurpose UI to provide spelling correction and suggestions.   

 ## LANGUAGE USED: Python, TensorFlow, Keras, OpenCV, etc.
 - Created a Custom dataset of ASL Characters from A-Z consisting of ~ 30,000 Images with a Split of ~800 Training and ~200 Test Images per Character.
 - Developed a CNN model to Translate ASL characters displayed by user on the camera to text and display.
 - Used Image Processing to Convert Image from 3D RGB Array to 1D Grayscale Array with Gaussian Blur.
 - Achieved 95% Accuracy on character detection
