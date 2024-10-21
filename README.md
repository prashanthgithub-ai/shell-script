# To access S3 from by using shell script
# step 1
. start the instance
. Connect the instance
. create s3 buckets
# step 2 
. go to IAM user
. create one user
. Give AWS S3 full access permissions
. Create access key and secret key in user
# step 3
.create a file with .sh like vi file1.sh
. Give executable permissions to the file shellscript.sh
. Chmod 777 shellscript.sh  it can provide complete permissions
to the file read ,write execte
![Screenshot 2024-10-21 192415](https://github.com/user-attachments/assets/93bb2739-f92b-4a5d-8af1-7685f9272e36)
IN the above image i have wrote the commands to confgiure s3 access
#!/bin/bash = write script
aws configure = provides keys
aws s3 ls = list the buckets
free = check memory space
nproc = check CPUs in server
ps -ef = check CPU processor
to save the file we use command :wq!
![Screenshot 2024-10-21 192601](https://github.com/user-attachments/assets/114d03d0-f90b-4781-a35d-67fad1246713)
to execte we use command ./file1.sh
The file can execute all the steps automatically by shell script as the above image
