WorkoutDBProj
-----------------------------------------------------------------------------------------------------------
Description: This Project is to store data on workout progress and display it in graph form. 


-----------------------------------------------------------------------------------------------------------


Project Function: 
The Graph data will be submitted to a DynomoDB AWS Database through an Amazon API Gateway via a Lambda function. 

In AWS there will be a Lambda Function running as a cron job to daily create new graph images and save them in S3.
