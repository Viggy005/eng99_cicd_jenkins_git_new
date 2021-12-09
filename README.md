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
![](pics/JOB1/1.png)
![](pics/JOB1/2.png)
![](pics/JOB1/3.png)
![](pics/JOB1/4.png)
![](pics/JOB1/5.png)
![](pics/JOB1/6.png)
![](pics/JOB1/7.png)

# Job2 (merge dev branch inot master/main):
![](pics/JOB2/1.png)
![](pics/JOB2/2.png)
![](pics/JOB2/3.png)
![](pics/JOB2/4.png)
![](pics/JOB2/5.png)
![](pics/JOB2/6.png)

# Job3 (launch into aws ec2):
![](pics/JOB3/1.png)
![](pics/JOB3/2.png)
![](pics/JOB3/3.png)
![](pics/JOB3/4.png)
![](pics/JOB3/5.png)
![](pics/JOB3/6.png)