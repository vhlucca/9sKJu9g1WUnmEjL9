# MonReader

## Background:

Our company develops innovative Artificial Intelligence and Computer Vision solutions that revolutionize industries. Machines that can see: We pack our solutions in small yet intelligent devices that can be easily integrated to your existing data flow. Computer vision for everyone: Our devices can recognize faces, estimate age and gender, classify clothing types and colors, identify everyday objects and detect motion. Technical consultancy: We help you identify use cases of artificial intelligence and computer vision in your industry. Artificial intelligence is the technology of today, not the future.

MonReader is a new mobile document digitization experience for the blind, for researchers and for everyone else in need for fully automatic, highly fast and high-quality document scanning in bulk. It is composed of a mobile app and all the user needs to do is flip pages and everything is handled by MonReader: it detects page flips from low-resolution camera preview and takes a high-resolution picture of the document, recognizing its corners and crops it accordingly, and it dewarps the cropped document to obtain a bird's eye view, sharpens the contrast between the text and the background and finally recognizes the text with formatting kept intact, being further corrected by MonReader's ML powered redactor.

![image](https://github.com/vhlucca/9sKJu9g1WUnmEjL9/assets/36247133/6efc3b0f-b70a-4376-ac48-49eaa6455190)

![image](https://github.com/vhlucca/9sKJu9g1WUnmEjL9/assets/36247133/10a0832c-8d3e-4996-81c4-6a183f0c876e)

## Data Description:

We collected page flipping video from smart phones and labelled them as flipping and not flipping.

We clipped the videos as short videos and labelled them as flipping or not flipping. The extracted frames are then saved to disk in a sequential order with the following naming structure: VideoID_FrameNumber

## Goal(s):

Predict if the page is being flipped using a single image.

## Success Metrics::

Evaluate model performance based on F1 score, the higher the better.

## Bonus(es):

Predict if a given sequence of images contains an action of flipping.
