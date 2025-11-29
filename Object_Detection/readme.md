# Object Detection using YOLOv3

This repository contains code for object detection using the YOLOv3 algorithm. YOLOv3 is a popular real-time object detection algorithm known for its speed and accuracy. This implementation focuses on practical deployment and efficient inference.

## Prerequisites

- Python 3
- OpenCV
- NumPy
- Matplotlib

## Download YOLOv3 Weights and Configuration

To run the object detection, you need to download the YOLOv3 pre-trained weights and configuration files. Run the following commands:

download_url = "https://pjreddie.com/media/files/yolov3.weights"
desired_path = "/content/yolov3.weights"
!wget {download_url} -O {desired_path}

download_url = "https://github.com/pjreddie/darknet/raw/master/cfg/yolov3.cfg"
desired_path = "/content/yolov3.cfg"
!wget {download_url} -O {desired_path}

download_url = "https://github.com/pjreddie/darknet/blob/master/data/coco.names"
desired_path = "/content/coco.names"
!wget {download_url} -O {desired_path}

## Results

![Image 1 Image](results/image1.png)

![Image 2 Image](results/image2.png)

![Image 3 Image](results/image3.png)

![Image 4 Image](results/image4.png)

## Customization

You can modify the confidence threshold and Non-Maximum Suppression (NMS) parameters in the code for different detection sensitivity. To detect a different specific object, you can change the class_id according to the COCO labels.

## Maintainer

Arun Kumar Reddy Vemula
AI/ML Engineer
Email: arunkumarreddy952@gmail.com

## About the Developer

I am an AI/ML Engineer with over 5 years of experience building practical machine learning solutions for autonomous vehicles, fraud detection, and industrial IoT. My expertise includes deploying computer vision models that run in real time on edge devices, optimizing cloud inference costs through quantization, and implementing robust CI/CD pipelines for model updates. I specialize in turning complex business problems into functional AI systems that scale.