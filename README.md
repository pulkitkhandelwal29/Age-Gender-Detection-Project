# Age & Gender Detection Project
The project helps in detecting age & gender of people.

## Installation
1. Clone the repository and change the working directory to Project folder<br>
`https://github.com/pulkitkhandelwal29/Age-Gender-Detection-Project.git`

2. Create a virtual environment inside the project folder<br>
`virtualenv myenv`

3. Activate virtual environment <br>
`myenv\Scripts\Activate`

4. Install the necessary packages in environment <br>
`pip install -r requirements.txt`

## Run the project
1. Age & Gender Detection<br>
`python age_detection.py --image images/adrian.png --face face_detector --age age_detector --gender gender_detector`

2. Age & Gender Video Detection<br>
`python video_age_detection.py --face face_detector --age age_detector --gender gender_detector`

## Libraries
* OpenCV - Standard computer vision/Image processing functions
* Imutils - OpenCV convenience functions
* Numpy - Comprehensive Mathematical Functions

## Pre-trained Caffe Deep Learning Models
* MobileNet SSD (Single Shot Detector)

## Demonstration
![1](https://user-images.githubusercontent.com/67990422/132734554-8f99edcd-768f-4e82-957c-d23274af8efe.PNG)
![2](https://user-images.githubusercontent.com/67990422/132734545-6464fb71-7028-49d5-a298-56e01a884f4e.PNG)
![3](https://user-images.githubusercontent.com/67990422/132734537-8f27940a-220e-406a-976d-1c6a6fc4abff.PNG)
