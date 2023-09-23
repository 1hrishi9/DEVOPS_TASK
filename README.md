# DEVOPS_TASK
MIXED task of linux aws and devops in this repo

## task 1 take backup of ami on a daily basis in an interval of 12hr
### APPROACH
-	First, we need to configure aws with that or a different instance (need to keep in mind that user should have full access of ec2 so that he can create Ami at least)
-	 We need to write a script that will take backup of instance (for this we will need instance id  and some knowledge about aws cli command of ec2 ) I am referring this link https://docs.aws.amazon.com/cli/latest/reference/ec2/create-image.html
-	After this we just need to add a crontab job for this .sh file to execute at every 12hr

---
## task 2 script to copy history of every hr in a specific file located in s3 bucket
### APPROACH
-	First, we need to configure aws with that or a different instance (need to keep in mind that the user should have full access of S3 so that he can modify S3 bucket at least)
-	 We need to write a script that will take history and append that to a file in a folder of a specific S3 bucket
-	Then apply crontab job every hour so that this script will be run every hour


---
## task 3 create a backup of the database on every  2nd and 4th Friday of each month 
### APPROACH
-	Need instance which is aws configure and has access of RDS 
-	We need to write a script that will take snapshot of DB instance 
-	After that we have to run that script on every 2nd and 4th Friday of month


----

>for in-depth steps refer word file of each task

