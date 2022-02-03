**********************************************************************
*                                                                    *
*     Copyright(c) 2022 by Dr.Abdulrakeeb M. Al-Ssulami              *
*                                                                    *
**********************************************************************

**********************************************************************
**********************************************************************
*                                                                    *
*                     Heart disease datasets                         *
*                                                                    *
**********************************************************************
**********************************************************************

- 6 heart datasets were produced by instance duplication using k-nearest neighbor (k-NN), random forests (RF), decision tree (DT), support vector machine (SVM), Gaussian Naive Bayes (GNB), and Adaboost (ADB) classifiers. 
- The datasets are presented in the paper: Abdulrakeeb M. Al-Ssulami, Randh S. Alsorori, and Aqil M. Azmi. 
  Accuracy improvement of heart disease prediction based on instance duplication, 2022.
- We produced these datasets from IEEE-DataPort heart dataset by Manu in 2020 which can be found at https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive
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
	IEEE-1099-11-KNN.csv 	1099		181				599		500		2
	IEEE-1077-11-RF.csv	1077		159				579		498		3
	IEEE-1174-11-DT.csv	1174		256				649		525		2
	IEEE-1114-11-SVM.csv	1114		196				607		507		3
	IEEE-1054-11-GNB.csv	1054		136				580		474		1
	IEEE-1060-11-ADB.csv	1060		142				576		484		2
   -------------------------------------------------------------------------------------------------------------------------------
-Accuracy results of k-NN, RF, DT, SVM, GNB, and ADB are 100%, 98%, 97.7%, 93.5%, 74.6%, and 78.7%, respectively.
