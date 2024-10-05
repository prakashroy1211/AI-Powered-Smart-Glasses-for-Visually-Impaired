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
## Methodology
### 4.1 Image Captioning with BLIP
BLIP, is Bootstrapping Language-Image Pre-training, which is an AI model that excels
at understanding the relationship between images and language. BLIP analyzes images
and generates captions describing their content. This makes it ideal for applications
like your smart glasses for visually impaired users. It combines computer vision and
natural language processing techniques. It can extract visual features from images
and translate them into human-readable language. It can handle noisy web data by
using a bootstrapping technique. This ensures the captions it generates are accurate
and reliable. They can achieve impressive results on image captioning tasks compared
to other models.Overall, BLIP’s ability to bridge the gap between image analysis and
language generation makes it a valuable tool for tasks that require understanding visual
content.Blip architecture includes the following:
• Multimodal Mixture of Encoder-Decoder (MED):This is the core of BLIP’s
architecture. It allows the model to function in three different modes:
Unimodal Encoder: Analyzes images only, extracting visual features.
Image-Grounded Text Encoder: Takes an image and text caption as input, allowing the model to learn the relationship between visual content and language.
Image-Grounded Text Decoder: Takes encoded image features and generates a
textual caption describing the image.
• Vision Encoder:This component, often utilizing a pre-trained Vision Transformer (ViT), processes the input image. ViT breaks the image into smaller
patches and encodes each patch into a vector representation.These embeddings
capture the visual information within each patch.Transformer layers are applied
to these embeddings, enabling the model to learn relationships between different
parts of the image.
• Text Encoder:BLIP can incorporate a pre-trained Transformer-based language
model (like BERT) for this stage. This encoder processes the textual caption and
extracts its meaning representation.
• Fusion Layer:If both a text encoder and image encoder are used, a fusion layer
combines the encoded information from both modalities (image and text).
• Text Decoder:This component leverages a pre-trained Transformer architecture.It takes the encoded image feature as input.The decoder utilizes its knowledge of language to generate a sequence of words, forming the image caption.
BLIP excels at image captioning, making it a valuable tool for your AI-powered
smart glasses for visually impaired users. The different steps include:

