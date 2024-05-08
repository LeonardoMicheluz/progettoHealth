# UCLA Stress Echocardiography Data
The following description comes from the UCLA Statistics Web Site.

Data Provided By: Alan Garfinkel, PhD, UCLA, Department of Physiology

## General Explanation of the Study
This data is from a study that was trying to determine if a drug called "dobutamine" could be used effectively in a test for measuring a patient's risk of having a heart attack, or "cardiac event." 
For younger patients, a typical test of this risk is called "Stress Echocardiography." 
It involves raising the patient's heart rate by exercise--often by having the patient run on a treadmill--and then taking various measurements, such as heart rate and blood pressure, as well as more complicated measurements of the heart. 
The problem with this test is that it often cannot be used on older patients whose bodies can't take the stress of hard exercise. 
The key to assessing risk, however, is putting stress on the heart before taking the relevant measurements. While exercise can't be used to create this stress for older patients, the drug dobutamine can. 
This study, then, was partly an attempt to see if the stress echocardiography test was still effective in predicting cardiac events when the stress on the heart was produced by dobutamine instead of exercise. 
More specifically, though, the study sought to pinpoint which measurements taken during the stress echocardiography test were most helpful in predicting whether or not a patient suffered a cardiac event over the next year.

## Brief Description of the Data
The accompanying data file contains the complete data for the final study population, which included 220 men and 338 women. The data collected on each subject is explained below.
## Variables
For the purposes of the study, the "cardiac events" that the "Dobutamine Stress Echocardiography" was attempting to predict were broken down into four categories:

* myocardial infarction (MI)

* revascularization by percutaneous transluminal coronary angioplasty (PTCA)

* coronary artery bypass grafting surgery (CABG)

* cardiac death

If you're not familiar with medical jargon, you can simply think of these as four things that can go wrong with your heart, and that the test was trying to predict. 
In the datafile you can see whether or not a patient suffered one of these cardiac events in the year following the patient's test by looking in the columns marked "newMI", "newPTCA", "newCABG", and "death". 
Note that, contrary to statistical convention, a "0" means that the patient DID NOT suffer the corresponding cardiac event, and a "1" means that he DID. The other variables are explained below.

## Explanation of Data Measurement Abbreviations in the Data File
* bhr:	basal heart rate

* basebp:	 basal blood pressure

* basedp:	 basal double product (= bhr x basebp)

* pkhr:	 peak heart rate

* sbp:  systolic blood pressure

* dp:  double product (= pkhr x sbp)

* dose:  dose of dobutamine given

* maxhr:  maximum heart rate

* pctMphr:  % of maximum predicted heart rate achieved

* mbp:  maximum blood pressure

* dpmaxdo:	double product on maximum dobutamine dose

* dobdose:	dobutamine dose at which maximum double product occured

* age:	age

* gender:  gender 

* baseEF:  baseline cardiac ejection fraction (a measure of the heart's pumping efficiency)

* dobEF:	ejection fraction on dobutamine

* chestpain:	1 means experienced chest pain

* restwma:	cardiologist sees wall motion anamoly on echocardiogram (1 = yes)

* posSE:	stress echocardiogram was positive (1 = yes)

* newMI:	new myocardial infarction, or heart attack (1 = yes)

* newPTCA:	recent angioplasty (1 = yes)

* newCABG:	recent bypass surgery (1 = yes)

* death:	died (1 = yes)

* hxofHT:  history of hypertension (1 = yes)

* hxoDM:  history of diabetes (1 = yes)

* hxofCig:  history of smoking (1 = yes)

* hxofMI:  history of heart attack (1 = yes)

* hxofPTCA:  history of angioplasty (1 = yes)

* hxofCABG:  history of bypass surgery (1 = yes)

* any.event:	outcome variable, defined as "death or newmi or newptca or newcabg". if any of these variables is positive (= 1) then "any event" is also postive (= 1).

* ecg:	signs of heart attack on ecg
