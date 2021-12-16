# CICD
# project Diagram:
![](Pics/jenkins/jenk.png)
## Github ssh set up
### Webhooks
![](images/CICD.png)
![](Pics/jenkins/CICD.png)
![](images/cicd_jenkins.png)
![](images/jenkins.png)
# generate SSH:
-       for Github(public_key) to localhost(private_key)
-       for github(pub) to jenkins(privatekey)
>how to generate key:
-       cd .ssh (recomended places to generate and store keys)
-       ssh-keygen -t ed25519 -C "your_email@example.com"

# on github

# Job1 (check if app is good to go):
![](Pics/JB1/1.png)
![](Pics/JB1/2.png)
![](Pics/JB1/3.png)
![](Pics/JB1/4.png)
![](Pics/JB1/5.png)
![](Pics/JB1/6.png)
![](Pics/JB1/7.png)

# Job2 (merge dev branch inot master/main):
![](Pics/JB2/1.png)
![](Pics/JB2/2.png)
![](Pics/JB2/3.png)

![](Pics/JB2/4.png)
![](Pics/JB2/5.png)
![](Pics/JB2/6.png)

# Job3 (launch DB into aws ec2):
![](Pics/JB3/1.png)
![](Pics/JB3/2.png)
![](Pics/JB3/3.png)
![](Pics/JB3/4.png)
![](Pics/JB3/5.png)
![](Pics/JB3/6.png)

# create own jenkins and run:
![](Pics/jenkins.png)

# Job4 (launch app into aws ec2):
![](Pics/JB4/1.png)
![](Pics/JB4/2.png)
![](Pics/JB4/3.png)
![](Pics/JB4/4.png)
![](Pics/JB4/5.png)
![](Pics/JB4/6.png)