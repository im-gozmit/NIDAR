# Project Title

NIDAR - Automatic Threat Detection

## Theme Choosen

Artificial Intelligence in Defense

## Project Description

Public Safety is a major concern in today's society. Modern weaponry and firearms pose serious threat to the safety and security of the everyday people. An integrated system that process video data and detect presence of a firearm or other weaponry when used in a threatning or dangerous manner and inform the Police or the concerned authority. We have used Cascade Classifier for detection of guns in a real time footage. For detection of human beings, we are using R-CNN model in real time and then we are combining both the records to predict whether the situation is threatning or not. 
As most of the Indian cities are moving towards SMART cities and have hardware sensors like camera, raspberry pi already deployed so we will take the raw data from these cameras and will process that.

### Prerequisites

All the prerequisite are present in the requirements.txt file which can be install by

```
pip3 install -r requirements.txt
```

### Installing

A step by step series of examples that tell you how to get a development env running

To run the model of detecting weapons:
```
git clone https://github.com/im-gozmit/NIDAR.git
```

```
cd haarclassifier
```

```
python video_recognition.py
```

To run the model of Human Detection:

```
run the HumanDetection.ipynb
```

## Running the tests

For running some test data for detecting guns, put the images/video in the 
``` 
/haarclassifier/data/
```
and then run the command

```
python video_recognition.py
```

For running some test data for detecting Humans, put the images/video in the 
``` 
/Mask_RCNN/videos/
```
and then run the commands followed in the Collab notebook 
``` 
HumanDetection.ipynb 
```

## Future Work:

* Using Pose Estimation models to get all the threatning poses.
* If someone do a threat then we can trace the person by training a separate model for facial recognition.

## Screenshots:
![Gun Detection](https://github.com/im-gozmit/NIDAR/blob/master/Screenshots_videos/gun_1.png)
![Gun Detection](https://github.com/im-gozmit/NIDAR/blob/master/Screenshots_videos/gun_2.png)
![Person Detection](https://github.com/im-gozmit/NIDAR/blob/master/Screenshots_videos/person_1.png)
![Person Detection](https://github.com/im-gozmit/NIDAR/blob/master/Screenshots_videos/person_2.png)

## Built With

* [Python](https://www.python.org/) - The programming langauge used

## Versioning

Version : 0.1

## Authors

* **Mayank** - *Initial work* - [im-gozmit](https://github.com/im-gozmit)
* **Mayank Mishra** - *Initial work* - [june12mayank](https://github.com/june12mayank)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* To all the organizing members of Women Techmakers BVP and Developer Student Clubs - BVP
* To the mentors : Uday Upreti, Arpan Garg and Nakul Garg for the valuable feedback. 
* To Google for always being ready to get anything we searched.