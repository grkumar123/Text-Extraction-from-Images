# Text-Extraction-from-Images
<!-- ![Figure 1](https://github.com/grkumar123/Text-Extraction-from-Images/blob/main/Sample/image1.jpg | width=100) -->

<!-- ![Figure 2](https://github.com/grkumar123/Text-Extraction-from-Images/blob/main/Sample/image2.jpg | width=100) -->

<!-- ![](https://github.com/grkumar123/Text-Extraction-from-Images/blob/main/Sample/image1.jpg = 250*250) -->

<img src="https://github.com/grkumar123/Text-Extraction-from-Images/blob/main/Sample/image1.jpg?raw=true" width="250" height="250">  <img src="https://github.com/grkumar123/Text-Extraction-from-Images/blob/main/Sample/image2.jpg?raw=true" width="250" height="250">

Text extraction from image is a challenging task. However, we have already some softwares like Tesseract, Easy OCR etc. It is difficult to do it manually to extract exact text and crop that text as image. I have used **OpenCV** to do this task.

I have already a **.json** file in which "Bounding-box" for each word coordinates was already given.

The json file is a list containg dictionary and many sub-dictionaries. For example:
 
[{'text':'ABC', 'polygon':{'x0':100, 'y0':200', 'x1':50, 'y1':60, 'x2':100, 'y2':100, 'x3':400, 'y3':400}}, {{'text':'ABC', 'polygon':{'x0':100, 'y0':200', 'x1':50, 'y1':60, 'x2':100, 'y2':100, 'x3':400, 'y3':400}}]
