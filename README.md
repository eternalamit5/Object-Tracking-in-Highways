# Object Tracking in Highways with Opencv and Python

Object tracking: It does frame-by-frame tracking but keeps the history of where the object is at a time after time

## Steps:

-  Creation of a mask in highway.mp4 file

![image](https://user-images.githubusercontent.com/44448083/135055887-5816552e-b2b0-4c81-a20b-d08bed6c2970.png)

- Focusing the attention on objects that are larger than a certain area

- Drawing the contours with OpenCV’s cv2.drawContours function

![image](https://user-images.githubusercontent.com/44448083/135056094-a80e4626-c8c1-4fb4-b424-3132426a627e.png)


- Defining a region of interest ROI and apply the mask only in this area

![image](https://user-images.githubusercontent.com/44448083/135056316-b9ee9c65-fbd4-4a7f-97b7-c5043bc5b120.png)

- Drawing the box around the object

![image](https://user-images.githubusercontent.com/44448083/135056437-db217c10-d42b-4b16-8565-7b8601032a47.png)

- Integrate the tracking functions and associate unique ID to the object

- Below image shows the result:

![image](https://user-images.githubusercontent.com/44448083/135056795-8f2b9261-9348-4c2f-8d60-c593528d41af.png)

