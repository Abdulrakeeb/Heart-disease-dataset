**********************************************************************
**********************************************************************
*                                                                    *
*   Heart disease datasets by Dr.Abdulrakeeb M. Al-Ssulami, 2022     *
*                                                                    *
**********************************************************************
**********************************************************************

- 6 heart datasets were produced by instance duplication using k-nearest neighbor (k-NN), random forests (RF), decision tree (DT), support vector machine (SVM), Gaussian Naive Bayes (GNB), and Adaboost (ADB) classifiers. 
- The datasets are presented in the paper: 
  Al-Ssulami AM, Alsorori RS, Azmi AM, and Aboalsamh H, 2022. Improving the accuracy of heart disease prediction through selective instance duplication.
- We produced these datasets from UCI-1190-11 (IEEE DataPort) heart dataset by Manu in 2020 which can be found at https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive
- All datasets contain 11 features and the target (0=no heart disease, 1= heart disease)
- The features are
   ---------------------------------------------------------------------------------------------------------------------
	No.	feature						code		data type
   ---------------------------------------------------------------------------------------------------------------------
	1	age						age		real number
	2	sex						sex		binary value (1=male, 0=female)
	3	chest pain type					cp		nominal (1=typical angina, 2=atypical angina, 3=non-anginal pain,4=asymptomatic)
	4	resting blood pressure				restbp		real number
	5	serum cholestoral in mg$/$dl			chol		real number
	6	fasting blood sugar $>$ 120 mg$/$dl		fbs		binary (1=true; 0=false)
	7	resting electrocardiographic 			restecg		nominal (0=normal, 1= ST-T wave abnormality, 2= left ventricular hypertrophy)
	8	maximum heart rate achieved			thalach		real number
	9	exercise induced angina				exang		binary (1=yes; 0=no)
	10	ST depression					oldpeak		real number
	11	the slope of the peak exercise ST segment	ST slope	nominal (0=normal,1=upsloping,2=flat,3=downsloping)
      ---------------------------------------------------------------------------------------------------------------------
- Dataset names and information
   -------------------------------------------------------------------------------------------------------------------------------
	Dataset name		# of instances 	# of duplicate instances	# of HD		# of NHD	duplication rounds
   -------------------------------------------------------------------------------------------------------------------------------
	UCI-KNN-1099-11 	1099		181				599		500		2
	UCI-RF-1077-11		1077		159				579		498		3
	UCI-DT-1174-11		1174		256				649		525		2
	UCI-SVM-1114-11		1114		196				607		507		3
	UCI-GNB1054-11		1054		136				580		474		1
	UCI-ADB-1060-11		1060		142				576		484		2
   -------------------------------------------------------------------------------------------------------------------------------
-Leave-one-out cross-validation mean accuracy results of k-NN, RF, DT, SVM, GNB, and ADB are 100%, 98%, 97.7%, 93.5%, 74.6%, and 78.7%, respectively.

- Three heart disease datasets Cleveland-303-10, Hungarian-98-10, and VA-93-10 are curated from UCI repository.
- These three datasets have 10 features (all features in the table above except feature number 6)
- Four classifier-based enhanced datasets are generated from Cleveland-303-10.
- Dataset names and information
   -------------------------------------------------------------------------------------------------------------------------------
	Dataset name		# of instances 	# of duplicate instances	# of HD		# of NHD	duplication rounds
   -------------------------------------------------------------------------------------------------------------------------------
	Cleveland-KNN-387-10 	387		84				184		203		2
	Cleveland-RF-400-10	400		97				192		208		4
	Cleveland-DT-474-10	474		171				218		256		7
	Cleveland-SVM-390-10	390		87				181		209		2
   -------------------------------------------------------------------------------------------------------------------------------
-Leave-one-out cross-validation mean accuracy results of k-NN, RF, DT, and SVM are 100%, 99.5%, 100%, and 94.4%, respectively.
