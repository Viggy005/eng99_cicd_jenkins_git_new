# CICD
## Github ssh set up
### Webhooks
![](images/CICD.png)
![](pics/cicd_app.png)
![](images/cicd_jenkins.png)
![](images/jenkins.png)
# generate SSH:
-       for Github(public_key) to localhost(private_key)
-       for github(pub) to jenkins(privatekey)
>how to generate key:
-       cd .ssh (recomended places to generate and store keys)
-       ssh-keygen -t ed25519 -C "your_email@example.com"

# Job1 (check if app is good to go):
![](Pics/JOB1/1.png)
![](Pics/JOB1/2.png)
![](Pics/JOB1/3.png)
![](Pics/JOB1/4.png)
![](Pics/JOB1/5.png)
![](Pics/JOB1/6.png)
![](Pics/JOB1/7.png)

# Job2 (merge dev branch inot master/main):
![](Pics/JOB2/1.png)
![](Pics/JOB2/2.png)
![](Pics/JOB2/3.png)
# need to add build trigger
![](Pics/JOB2/4.png)
![](Pics/JOB2/5.png)
![](Pics/JOB2/6.png)

# Job3 (launch into aws ec2):
![](Pics/JOB3/1.png)
![](Pics/JOB3/2.png)
![](Pics/JOB3/3.png)
![](Pics/JOB3/4.png)
![](Pics/JOB3/5.png)
![](Pics/JOB3/6.png)