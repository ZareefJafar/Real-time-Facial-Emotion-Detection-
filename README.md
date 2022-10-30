# Real-time-Facial-Emotion-Detection

Implemented a Real-Time emotion recognition system using facial Expressions based on [**DeepFace**](https://ieeexplore.ieee.org/document/9259802) framework. 

Deepface is a lightweight facial analysis framework including face recognition and demography (age, gender, emotion and race) for Python.



## Dependencies

* numpy>=1.14.0
* pandas>=0.23.4
* gdown>=3.10.1
* tqdm>=4.30.0
* Pillow>=5.2.0
* opencv-python>=4.5.5.64
* opencv-contrib-python>=4.3.0.36
* tensorflow>=1.9.0
* keras>=2.2.0
* Flask>=1.1.2
* mtcnn>=0.1.0
* lightgbm>=2.3.1
* dlib>=19.20.0
* retina-face>=0.0.1
* mediapipe>=0.8.7.3
* fire>=0.4.0

Install deepface from [`PyPI`](https://pypi.org/project/deepface/). 

```shell
$ pip install deepface
```

DeepFace framework wraps following face recognition models:
```python
models = [
  "VGG-Face", 
  "Facenet", 
  "Facenet512", 
  "OpenFace", 
  "DeepFace", 
  "DeepID", 
  "ArcFace", 
  "Dlib", 
  "SFace",
]
```

<!-- USAGE EXAMPLES -->
## Demo



<p align="right">(<a href="#top">back to top</a>)</p>

This demo showcases my real time facial expression recognition from webcam. 
<img src="emotions.gif"  align="center">