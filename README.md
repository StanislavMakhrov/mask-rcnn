#Installation

1. Clone this repository.

2. Install python 3.8.7:
For Windows:
   https://www.python.org/ftp/python/3.8.7/python-3.8.7-amd64.exe
   
For Debian Linux:

    apt install python3

For Ubuntu Linux:

    sudo add-apt-repository ppa:deadsnakes/ppa
    sudo apt update
    apt install python3.8

For Linux via PyEnv:

    apt install pyenv
    pyenv install -v 3.8.7
    pyenv global 3.8.7

3. Enter to the folder of cloned repository on your local PC and install python packges from requirements.txt:
   
        pip install -r requirements.txt

#Running

Switch on your webcam and run the following command:

    python mask_rcnn_video.py --mask-rcnn mask-rcnn-coco