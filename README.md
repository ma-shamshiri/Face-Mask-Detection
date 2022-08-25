<h1 align="left"> Face-Mask-Detection </h1>
<!-- <img src="images/Animation.gif" align="left" width="99%" height="99%"> -->

![Realtime](https://user-images.githubusercontent.com/49322948/159162779-30679424-991e-4088-a56d-333399887281.gif)

<p align="justify"> 
The main objective of this project is to detect discriminating features in an image and find the best matching features in other images. Because features should be reasonably invariant to translation, rotation, and illumination.
</p>

<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> Table of Contents</h2>
  <ol>
    <li><a href="#prerequisites"> Prerequisites </a></li>
    <li><a href="#HowToUse"> How to Use </a></li>
    <li><a href="#results"> Results </a></li>
    <li><a href="#reference"> Reference </a></li>
    <li><a href="#credits"> Credits </a></li>
  </ol>

<!-- <img src="images/animation.gif" align="left" width="99%" height="150px"> -->

<!-- PREREQUISITES -->
<h2 id="prerequisites">Prerequisites</h2>

<p align="center">
  <a href="https://www.microsoft.com/en-ca/software-download/windows10">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="60px"/>
  </a>
  <a href="https://www.tensorflow.org/">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="60px"/>
  </a>
  <a href="https://www.anaconda.com/">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/anaconda/anaconda-original.svg" width="60px"/>
  </a>
  <a href="https://www.python.org">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="70px"/>
  </a>
  <a href="https://opencv.org/" target="_blank">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original-wordmark.svg" width="70px"/>
  </a>
<P/>

 1. Open a `Command Prompt` (NOT `Windows PowerShell`) or a `Terminal`
 2. Create a conda environment `conda create -n is python=3.6.6 -y`
 3. Activate this environment `activate is` (Windows) or `source activate is` (Linux/macOS)
 4. Install the following packages `tensorflow`, `keras`, `opencv`, `matplotlib`, `numpy`, `pandas`, `scikit-learn`, and `notebook`:       </br></br>
      * <a href="https://www.python.org/" target="_blank">Python (3.6)</a>
      * <a href="https://www.tensorflow.org/" target="_blank">TensorFlow (2.3.2)</a> - `pip install tensorflow==2.3.2`
      * <a href="https://keras.io/" target="_blank">Keras (2.1.6)</a> - `pip install keras==2.1.6`
      * <a href="https://opencv.org/" target="_blank">OpenCV (4.4.0)</a> - `pip install opencv==4.0.0`
      * <a href="https://matplotlib.org/" target="_blank">Matplotlib (3.5.1)</a> - `pip install matplotlib==3.5.1`
      * <a href="https://scikit-learn.org/stable/" target="_blank">Sklearn (0.23.2)</a> - `pip install scikit-learn==0.23.2`
      * <a href="https://jupyter.org/" target="_blank">Jupyter (4.7.1)</a> - `pip install notebook`


<!-- How to Use -->
<h2 id="HowToUse"> How to Use </h2>

<p align="justify">
      * Step 1. Download Code as Zip OR <br> 

```
git clone https://github.com/ma-shamshiri/Face-Mask-Detection.git
```

<b>Step 2.</b> Create a new virtual environment
```
python -m venv tfod #window
virtualenv tfod #Linux
```

<b>Step 3.</b> Activate your virtual environment
```
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
```

<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
```
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
```

<b>Step 5.</b> Collect images and ensure you change the kernel to the virtual environment.

<b>Step 6.</b> Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders. <br>
```
workspace\images\train
workspace\images\test
```

<b>Step 7.</b> Begin training process by opening 2. Training and Detection.ipynb, this notebook will walk you through installing Tensorflow Object Detection, making detections, saving and exporting your model.

<b>Step 8.</b> During this process the Notebook will install Tensorflow Object Detection. You should ideally receive a notification indicating that the API has installed successfully at Step 8 with the last line stating OK.
</p> 


<!-- Results -->
<h2 id="Results"> Results </h2>


<!-- REFERENCES -->
<h2 id="reference"> References</h2>


<!-- CREDITS -->
<h2 id="credits"> Credits</h2>

Mohammad Amin Shamshiri

[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ma-shamshiri)
[![Twitter Badge](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ma_shamshiri)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ma-shamshiri)
