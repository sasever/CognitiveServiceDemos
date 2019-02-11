# How to recreate the demo:  
From Azure portal create a Custom Vision service.  
Go to the Custom Vision site:https://customvision.ai/  
Crete a new project *(Be carefull for the 2 projects max limit for free tier)*

## Step 1 ::Data Loading:
Download CustomVisionCarDemoImages.zip from this repository
Load data on dent folder and tag as dent  
Load data  on writeoff folder and tag as write off  

## Step 2 :: train 

## Step 3 :: observe results and test
Show and note the precision and recall  
click to quicktest    
select test folder     
test with car 1   
show the results   
test with car 2  
show the results   
test with car 3
show the results   
ask to the audiance why we obtained this result  

ask whether they see something weird with the training data.  

*Answer: all dents are closeups and all writeoofs are wider pictures with the surrounding enviroment.
mention the importance of having different angles and more training images.*

## Step 4: add new class
Add new tag, nodamage, and add images in the nodamage folder to this tag.  
retrain  
retest  
discuss results

## Step 5: add more data
Add images under nodamage2,dent2 and writoff2 folders respectively to their tags,  
retrain  
retest  
discuss results

