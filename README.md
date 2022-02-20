# OCR FaceDetection Project


 ##   OCR and Face Detection using Python libraries OpenCV, Pillow and Pytesseract


### Problem Statement : 

Take a file of images and process them. 

    Note : original problem statement contained images in zip file whch were to be read. Not using zip due to uplaod limitations of GitHub.
    
The file containes newspaper images. The task is to write python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if we search for "pizza" it will return a **contact sheet** of all of the faces which were located on the newspaper page which mentions "pizza". We have to use OpenCV to detect faces, use tesseract to do optical character recognition, use PIL to composite images together into contact sheets.

 Each page of the newspapers is saved as a single PNG image in a file called [images](./readonly/images). These newspapers are in english, and contain a variety of stories, advertisements and images. 
Note: This file is fairly large (~200 MB) and may take some time to work with, it is encouraged to use [small_img](./readonly/small_img) for testing.

Here's an example of the output expected. 

    
Using the [small_img](./readonly/small_img) file, if we search for the string "Christopher" we should see the following image:


![Christopher Search](./readonly/small_project.png)


If we are to use the [images](./readonly/images) file and search for "Mark" we should see the following image (note that there are times when there are no faces on a page, but a word is found!):


![Mark Search](./readonly/large_project.png)



## Libraries Used : 
1. OpenCV : For face detection 
2. PyTessaract : for Optical Character Recognition 
3. kraken : 
4. PIL : Python Image Library, for image manipulation using python. OpenCV can deal with PIL image objects and produces a PIL image as output.  


