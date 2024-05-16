# fingerprint-recognisation
 implement fingerprint recognisation system using SIFT algorithm . the system aime to match altered or damaged fingerprint images with real fingerprint images to identify and authenticate individuals . 
 
**ABSTRACT**

Fingerprints scanners are security systems of biometrics. Everyone has patterns of frictions ridges on their fingers, and it is this pattern that is called fingerprint. Fingerprints are uniquely detailed, durable over an individual’s lifetime, and difficult to alter. Because there are countless combinations, fingerprints have become an ideal means of identification. They are used in police stations, security industries, Smartphone, and other mobile devices.
 
So, in our project we have two directories inside of the main directory and those contain images of fingerprints now the real directory contains images of actual fingerprint so we can see here always a number then a character representing a gender so the number is the id of the main character is gender and then the name of the fingerprint. For example - left index finger and all the files are real fingerprints without any modifications and then we also have the altered directory and inside of the altered directory we have three sub- directories, easy, medium, hard, then we have data sets then by using an external library open cv in which we take the altered image and then we will find the real fingerprints.

**Tools and Technology Used**

In this project we are going to use python as main language. With the help of some prebuild libraries or python such as cv2 which is open cv in python and os which help us to fetch directory (folder/file location) to get its contents in our code.

OpenCV: OpenCV is a Python open-source library, which is used for computer vision in Artificial intelligence, Machine Learning, face recognition, etc.
In OpenCV, the CV is an abbreviation form of a computer vision, which is defined as a field of study that helps computers to understand the content of the digital images such as photographs and videos. So, import it using the statement before using its functions. 
OS module
import os
The OS module in Python provides functions for creating and removing a directory (folder), fetching its contents, changing and identifying the current directory, etc. first we need to import the os module to interact with the underlying operating system. So, import it using the statement before using its functions.
 
