# Creating an EC2 instance on AWS 

1: Start by logging into AWS and making sure to select the region you wish to use

2: Go on the search bar and search for ec2 as shown below:

<img width="651" alt="image" src="https://user-images.githubusercontent.com/129381619/231813278-f4ce6831-be36-40ab-a919-365aec210cdd.png">

Now click on launch instance

<img width="260" alt="image" src="https://user-images.githubusercontent.com/129381619/231813665-326c04e6-f42e-42a2-a500-25be3e303197.png">

Now type in a name

<img width="551" alt="image" src="https://user-images.githubusercontent.com/129381619/231814010-48e1a059-a177-4514-8438-e27fd4380b8f.png">

Choose an AMI, we opted for Ubuntu

<img width="501" alt="image" src="https://user-images.githubusercontent.com/129381619/231814208-3e9cd53a-6d7b-4778-8238-257004cb1982.png">

Select a key a pair or feel free to create one

Now under the Network settings, make sure to change the 'Allow SSH Traffic from' Anywhere to 'My Ip'

Now you can launch instance

<img width="167" alt="image" src="https://user-images.githubusercontent.com/129381619/231822299-468a444a-f1ee-41a9-a4d8-b93563f5d205.png">

You should see something like this

<img width="448" alt="image" src="https://user-images.githubusercontent.com/129381619/231822423-14e54527-6033-49fc-826e-0c0e7398ec87.png">

<img width="388" alt="image" src="https://user-images.githubusercontent.com/129381619/231822729-bbb789bc-cfb3-4cbc-8007-fb1bd64d76f4.png">

Make sure to click connect and head to the SSH client tab before going to git bash

Once in Git Bash, use the command ```cd .sh``` to go the ssh directory

Now you can follow the instructions below which are found in the SSH client tab of aws

<img width="602" alt="image" src="https://user-images.githubusercontent.com/129381619/231824377-2fc44cee-a29e-4979-be7d-4b53798c894a.png">
