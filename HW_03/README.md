Pima Indians Diabetes Data Set

2. The content of this dataset is female patients who of are of 
Pima Indian heritage who have been tested for diabetes, and other
general tests. The data has been recorded in this data set. 
There are nine features in this data set which are listed below:

   1. Number of times pregnant
   2. Plasma glucose concentration a 2 hours in an oral glucose tolerance test
   3. Diastolic blood pressure (mm Hg)
   4. Triceps skin fold thickness (mm)
   5. 2-Hour serum insulin (mu U/ml)
   6. Body mass index (weight in kg/(height in m)^2)
   7. Diabetes pedigree function
   8. Age (years)
   9. Class variable (0 or 1) 
   
3.  Hypotheses:
	
	Number of times Pregnant and The Diabetes Pedigree function will be able to 
	predict whether or not a Pima Indian Female has diabetes. 

Notes on Data Set:
   1. Number of times pregnant (changes a woman's body chemistry, weight gain 
   and change in diet. Also can induce lifestyle changes as well)
   2. Plasma glucose concentration a 2 hours in an oral glucose tolerance test
   (measures the efficiency of insulin in a persons body (indicator of diabetes)0)
   3. Diastolic blood pressure (mm Hg) (indicative of general health)
   4. Triceps skin fold thickness (mm) (less personal body fat measurement than stomach fold)
   5. 2-Hour serum insulin (mu U/ml) (similar to number 2)
   6. Body mass index (weight in kg/(height in m)^2) (general measurement of proportions)
   7. Diabetes pedigree function (prediction method for diabetes using relatives and genetics)
   8. Age (years) (has an effect)
   9. Class variable (0 or 1) (0 means no diabetes, 1 means yes diabetes)
   
4. a. There are no NULL values. could impute them using an "if this then that" statement 
	indicating that the value must be replaced with a null value (not zero as that can mess with the array)
	
	b. The features of this data set are all fairly relevant to the 
	topic of women who are diagnosed with diabetes. However, the 
	dataset description does not designate if the women have been 
	diagnosed with type II or type I diabetes, for which there is
	a great difference. Overall this data set is not detailed enough
	to give the prediction power of whether or not a female has diabetes.