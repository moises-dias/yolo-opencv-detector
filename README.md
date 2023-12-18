# Object Detection Using YOLO Tutorial

Welcome to my Object Detection Using YOLO Tutorial! In this tutorial, 
you'll learn how to create your own object detection system that can be applied to any game 
by following a few steps. 

I've provided detailed instructions in the Jupyter notebooks. 
However, if you'd like a step-by-step video tutorial, please check out the video below. 


This video will not only walk you through each step of the process but also includes a real-time execution using Diablo 2 as an example.

[![Watch the video](https://img.youtube.com/vi/RSXgyDf2ALo/maxresdefault.jpg)](https://youtu.be/RSXgyDf2ALo)



## Practical Applications

With this project, you'll obtain a Python code that can detect objects, providing their coordinates and class in a list format, similar to the example below:

```python
[    
    {"x": 100, "y": 200, "w": 100, "h": 50, "class": "Slime"},    
    {"x": 600, "y": 150, "w": 90, "h": 110, "class": "Orc"},    
    {"x": 350, "y": 400, "w": 180, "h": 20, "class": "Zombie"}
]
```

With the data above, you can create your own logic for automating character actions. You can use libraries like [**pynput**](https://pypi.org/project/pynput/) to control your mouse or keyboard based on the detections.

In this video below I demonstrate how you can use the model predictions with pynput to automate actions in a game.

[![Watch the video](https://img.youtube.com/vi/gdIVHdRbhOs/maxresdefault.jpg)](https://youtu.be/gdIVHdRbhOs)

## Getting Started

To get started with this tutorial, follow these steps:

1. Clone this repository.

2. Open a command line in the repository folder.

3. Install the required dependencies by running:

```pip install -r requirements.txt```

4. Launch Jupyter Notebook by executing:

```jupyter notebook .```

5. Execute the step-by-step instructions provided in the Jupyter notebooks.

## References

This guide would not be possible without other great tutorials that I used as references:

1. [**OpenCV Object Detection in Games** - Learn Code by Gaming](https://www.youtube.com/playlist?list=PL1m2M8LQlzfKtkKq2lK5xko4X-8EZzFPI)
    - In this tutorial, you will learn how to use OpenCV for object detection in images using Template matching. It's a great tutorial, very well explained and I highly recommend watching it and also the channel other playlists to learn more about OpenCV.

2. [**YOLO Object Detection with OpenCV** - PyImageSearch](https://pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/)
    - If you want to dive deeper into using YOLO for object detection in images or video streams using Python, I recommend reading this article for more details on this topic.

3. [**TRAIN A YOLOv4 DETECTOR USING GOOGLE COLAB** - Techzizou](https://medium.com/analytics-vidhya/train-a-custom-yolov4-tiny-object-detector-using-google-colab-b58be08c9593)
    - In this tutorial, you can find instructions on running the detector in a live video and also obtaining metrics for your trained model performance. If you want more details about the training process, I recommend reading his Medium article.



## Contact

If you have any questions or want to share your projects based on this tutorial, please find me on [LinkedIn](https://www.linkedin.com/in/moisesdias/). I'd love to see your results.

