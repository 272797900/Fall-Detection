# Fall-Detection

Introduction
------------
Elderly people tend to slip and fall in homes and remain unattended for a long time. 
If the affected person is not treated immediately, serious health issues including brain injuries occur. 
The proposed solution automatically detects humans falling, through cameras installed in homes, and sends notification to family members.

Requirements
------------
MATLAB R2013a

Usage 
-----
MATLAB command line
```matlab
falldetection <video_name>;
```
####Example
```matlab
falldetection video.mp4;
```
####Note
The video should be saved in '..\Fall-Detection\Video' folder.

Output
------
####Original video frame
[![original.png](https://s3.postimg.org/esn2yx6eb/original.png)](https://postimg.org/image/5kuui7zbz/)

####Human segemented image
[![mask.png](https://s3.postimg.org/3m989kdgz/mask.png)](https://postimg.org/image/yt7vdh1db/)

####Motion History Image (MHI)
[![mhi.png](https://s3.postimg.org/vqsn37f1v/mhi.png)](https://postimg.org/image/rhnx11bsf/)

####Human shape
[![shape.png](https://s4.postimg.org/576uymvyl/shape.png)](https://postimg.org/image/xk2cp3hop/)

####When fall is detected
[![fall.jpg](https://s3.postimg.org/6aagwho5f/fall.jpg)](https://postimg.org/image/tbr228nsv/)

YouTube Demo Video Link
------------------
Demo of the project

<a href="http://www.youtube.com/watch?feature=player_embedded&v=LdoLniUSOaA
" target="_blank"><img src="http://img.youtube.com/vi/LdoLniUSOaA/0.jpg" 
alt="Youtube Video: Human Fall Detection" width="240" height="180" border="10" /></a>

Flowchart
---------
[![Page-4-Image-27.png](https://s4.postimg.org/lfue0o4fh/Page_4_Image_27.png)](https://postimg.org/image/8og7u5und/)

Algorithm
---------

Note
----
* Live transmission from the camera to the software is not supported. Instead, the data from the camera is first stored and then processed.
* The notification is sent to the user through an app installed on the phone. The apk file is not included in this repository.

Reference Paper
---------------
C.Rougier,J.MeunierFall,A.Arnaud and J.Rousseau. Detection from Human Shape and Motion History using Video Surveillance. *Proceedings of the 21st International Conference on Advanced Information Networking and Applications Workshops*,2007. 





