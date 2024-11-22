## Setup and Usage 
- The following steps assume you have [Miniconda](https://docs.anaconda.com/miniconda/), [Git](https://git-scm.com/) and [Python](https://www.python.org/) installed already.

### Step 1: Create Environment
- Create a dedicated environment and activate it, using:
  ```bash
  conda create -n yolov8-face python=3.9 -y
  conda activate

### Step 2: Get YOLOv8 Face Model
- To clone the [YOLOv8 face repository](https://github.com/derronqi/yolov8-face.git) and install dependencies, run:
  ```bash
  git clone https://github.com/derronqi/yolov8-face.git
  cd yolov8-face
  pip install -r requirements.txt
  pip install ultralytics

### Step 3: Download Model Weights
- Download the [file containing the weights](https://github.com/jamaoh/anonymize-face-blur/blob/main/yolov8n-face.pt) and place it in your 'yolov8-face' folder.

### Step 4: Adjust and Run the Script
- Correctly specify the path to the video you'd like to blur and run the script. 

