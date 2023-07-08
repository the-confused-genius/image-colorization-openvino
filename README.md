# Image Colorization using Intel's OpenVINO toolkit
This program aims to convert gray scale (black and white) image to colorized image using the intel's openVINO toolkit. 
## About OpenVINO
OpenVINO stands for Open Visual Inference and Neural network Optimization. It is bundle of pretrained neural network, with optimization and anlysis tools. They provided the developer tools to build vast neural networks without training them. Saving time and optimizing preformance. 

## Building the Application
1. Install the requirements:
    ```bash
    pip install -r requirements.txt
    ```
2. Create the optimized model by running the notebook cells at `convert.ipynb` to convert the model to OpenVINO format. **(IMPORTANT)**
2. Run the demo:
    ```bash
    python demo.py
    ```
    **OR** You can run the notebook version of the demo from `demo.ipynb` file.
    
_Note: Demo won't work without creating the optimized model._

## Demo (CPU)
![demo2](demoImages/demo2.png)
![demo1](demoImages/demo1.png)
![demo1](demoImages/demo3.png)
![demo1](demoImages/demo4.png)
