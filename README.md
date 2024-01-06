# deploy-jenkins
## first install openjdk by using below command
[apt install openjdk-11-jdk
apt-get update]
install jenkins using below command
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian/jenkins.io-2023.key
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins

modify the inbound rule
![image](https://github.com/iam-harendra/deploy-jenkins/assets/96298529/263d6900-027e-40d4-a9ad-e0a3ffa066c1)
access the jenkins and copy /var/lib/jenkins/secrets/initialAdminPassword and paste in cli to get password
![image](https://github.com/iam-harendra/deploy-jenkins/assets/96298529/441a8dc6-e79b-4bcf-babd-e2757e7cbb43)
jenkins is accessed
![image](https://github.com/iam-harendra/deploy-jenkins/assets/96298529/245b7506-236d-436f-baeb-f82beb85f2ac)



