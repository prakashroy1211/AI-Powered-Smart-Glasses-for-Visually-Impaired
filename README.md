# AI-Powered-Smart-Glasses-for-Visually-Impaired
This project enhances independence for visually impaired individuals by using stereo cameras and the StereoBM algorithm for real-time obstacle detection and voice alerts. With a voice command interface, users can access object detection, image captioning, and text recognition, promoting autonomy and inclusion in a visually oriented world.
## Abstract
Visually impaired individuals encounter significant challenges navigating and interacting with their surroundings. Simple tasks, such as safely traversing through crowded
areas or identifying objects, pose considerable difficulties due to the lack of visual cues.
Moreover, the inability to perceive spatial distances increases the risk of collisions
and accidents, limiting their independence and overall quality of life. Traditional
aids, while helpful, often fall short in providing comprehensive solutions, leaving
gaps in essential functionalities like real-time obstacle detection and efficient access
to information.
The system aims to alleviate these challenges by seamlessly integrating cuttingedge technologies. Utilizing stereo cameras and the StereoBM algorithm, the system
accurately estimate distances to detect obstacles, facilitating a voice alert system
for user safety. The intuitive voice command interface empowers users to access
a range of functionalities seamlessly, from object detection to image captioning and
text recognition, providing invaluable assistance in daily tasks and enhancing overall
accessibility and independence. Through the integration of edge AI and innovative
computing, our system endeavors to revolutionize the experience of visually impaired
individuals, fostering greater autonomy and inclusion in a visually oriented world.
## Introduction
The project titled ”AI Powered Smart Glasses for Visually Impaired” represents a
groundbreaking initiative at the intersection of cutting-edge technology and social
impact. This transformative endeavor is driven by the mission to enhance the daily
lives of individuals facing visual impairments by providing them with an innovative
assistive device. At its technological core is the NVIDIA Jetson Nano, a powerful
edge AI chip meticulously chosen to facilitate efficient model deployment. This project
integrates a suite of hardware components, including a stereo camera, microphone, and
earphone strategically combined to create a comprehensive solution.
The smart glasses operate on a robust software foundation that includes BLIP for
real-time object recognition and image captioning, Tesseract OCR for text extraction,
BERT for natural language generation, and a sophisticated voice command interface.
Together, these components empower users with a range of functionalities, from realtime object identification to accurate distance estimation, all delivered through an
accessible text-to-speech format. The overarching goal is to foster independence, accessibility, and inclusivity for visually impaired individuals, showcasing the potential
of technology to address real-world challenges. This introduction sets the stage for a
detailed exploration of the project’s design, implementation, and its societal impact.

Refer [Project_Report](Project_Report.pdf) for more details.

## Python Modules installed
SpeechRecognition <br/>
PyAudio <br/>
Transformers <br/>
gtts <br/>
OpenCV <br/>

## Notebook selection based on environment
This repository contains code for two different environments:
[main.ipynb](main.ipynb): This Jupyter notebook runs on regular systems like laptops and PCs. It does not require any additional hardware such as external cameras or sensors. However, it does utilize the system's built-in camera and microphone.
[jetson_nano.ipynb](jetson_nano.ipynb): This Jupyter notebook is designed to run on the NVIDIA Jetson Nano. It requires a camera and other sensors to be attached for full functionality.<br/>
Make sure to use the appropriate notebook based on your hardware setup.
