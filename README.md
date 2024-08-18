# MobileFace_dataset
Our research has been accepted at the ICPR 2024, which work introduces the first large-scale face analysis using the newly proposed MobileFaces dataset. The dataset comprises images and videos captured in real-world, unconstrained environments, featuring varying distances, poses, and resolutions, all recorded using mobile phones.


# Face Verification and Face Attribute Analysis

This folder contains datasets for both face verification and face attribute analysis tasks.

## Folder Structure

- The dataset is organized into three folders, corresponding to three different distances: 2 meters, 5 meters, and 10 meters.
- Each distance folder contains 87 subfolders, representing the total number of subjects. Each subfolder contains the detected probe face images of the subject at the specified distance.

### Statistics:
- **Total number of probe face images used for...**
  - Face verification task: 87 * 22 = 1914 images at each distance
  - Face Attribute Analysis task: 87 * 15 = 1305 images at each distance

### Face Verification/Face Attribute Folders:

- **2M:** 
  - `Subject_ID/`
    - `image_num`
    - `image_num`
    - ...

- **5M:** 
  - `Subject_ID/`
    - `image_num`
    - `image_num`
    - ...

- **10M:** 
  - `Subject_ID/`
    - `image_num`
    - `image_num`
    - ...

## Cropped Front Face

This folder contains gallery images for the face verification task. These are cropped front face images, with the number of images corresponding to the Subject ID.

## Ground Truth Data

### GT_Age_Gender.csv
This file contains ground truth values for the face attribute analysis task. The CSV file has three columns: `Subject ID`, `Age`, and `Gender`.
- **Subject ID:** Contains 87 rows, corresponding to the 87 subjects.
- **Age:** Contains the true age of each subject.
- **Gender:** Contains the gender of each subject, with values either "Man" or "Woman".

## Contact

If you have any questions about this dataset, please contact Udaybhan Rathore at [udayrathore748@gmail.com](mailto:udayrathore748@gmail.com).
