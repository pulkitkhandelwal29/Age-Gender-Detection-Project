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

