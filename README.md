# Qualcomm QCS610 Edge AI Smart Camera

## Advantages of QCS610

1.  QCS610 can provide up to 1.5 TOPS of AI computing power and supports GPU and DSP accelerated computing

2.  The Qualcomm Neural Processing (SNPE) SDK and the Qualcomm AI Engine Direct (QNN) can optimize the performance of trained neural networks

3.  It supports Yocto for AI development



## Performance Metrics

- **AI Model**:
- AI Model: YOLOv5

## Hardware

- **Platform**: QCS610
- **Cameras**:  USB Camera × 1

## Software & Toolkit

- **AI SDK (SNPE) SDK**： v1.55
- **System:** Yocto

## Background & Solution

### Motivation:

- Traditional conference systems lack the ability to identify speakers and meeting interactions in real time. The remote participants would miss important visual context. Most systems still rely on manual camera control which may reduce meeting efficiency and interrupting collaboration

### Solution:

- Our smart camera system performs real-time computer vision inference to detect participants' positions, body poses, and hand gestures. It automatically controls the PTZ (Pan-Tilt-Zoom) camera for intelligent tracking and view switching to provide smarter and more natural collaboration experience

## Architecture Diagram:

The camera captures video streams and processes the image data on the QCS610 edge device.  
YOLOv5 is used for real-time detection of participants' positions, body poses, and hand gestures, driving the PTZ camera for intelligent tracking and view switching.

All processing takes place on the edge device, ensuring better privacy and data protection

<img src="QCS610 Edge AI Smart Camera.assets/media/image1.png" style="width:5.76806in;height:2.14861in" />

### Demo:



