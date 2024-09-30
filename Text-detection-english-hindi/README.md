# Text-detection-using-heroku-english-hindi-marathi


### This repository consists of files required to deploy a Machine Learning Web App created with Flask on Heroku platform.

• __Problem Statement__:
  Detect English, Hindi and text from image. 

• __Dependencies__: <br />
    1.Python - 3.6 <br />
    2.Gunicorn==19.9.0 <br />
    3.Pytesseract <br />
    4.Numpy <br />
    5.Opencv <br />
    6.Flask - 1.1.1 <br />

• __Steps__: <br />
  1. Get input image from html and using OpenCV decode image.<br />
  2. Clean image use dilation and erosion technique. <br />
  3. Pass image to pytesseract. <br />
  4. Return detected text to html page
  
