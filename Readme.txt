
Face_verification and Face_Attribute Analysis:
	* The folder is composed of three folders namely of three distances 2 meters, 5 meters, and 10 meters. Each distance folder consist a 87 subfolders equal to the total number of subjects. And each subfolder containing detected probe face images of subject as subfolder and at distance of folder name.
	* Total number of probe face image used for face verification task is 87*22 at each distance = 1914
	* Total number of probe face image used for face verification task is 87*15 at each distance = 1305

	Face_verification/Face_Attribute:

		2M: 
			Subject_ID:
					image_num
					image_num
					...
	
		5M: 
			Subject ID:
					image_num
					image_num
					...
				
		10M: 
			Subject ID:
					image_num
					image_num
					...


Cropped_front_face: 
	Consists of gallery images for face verification task, i.e cropped front face images and number of the images is same as Subject ID.

GT_Age_Gender.csv:
	This file contains ground truth values for face attribute analysis task. CSV file contain three columns: Subject ID, age, and gender. The Subject ID column contains 87 rows, while the age and gender columns contain the subject's true age and gender, respectively. The gender column can take the values "Man" or "Woman".
	
	
Contact:
If you have any questions about this dataset, please contact Udaybhan Rathore at udayrathore748@gmail.com
	