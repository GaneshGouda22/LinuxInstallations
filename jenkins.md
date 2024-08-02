## **Introdution of Jenkins** 
Jenkins is an open-source automation tool written in Java that enables continuous integration (CI) and continuous delivery (CD) of software projects.


## Installing Jenkins using `apt`:
Use following commands
`sudo apt update` for updating latest definitions.
To run jenkins ,needs java`sudo apt install openjdk-11-jdk -y`
`java -version`
You need to add the Jenkins repository
`curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee /usr/share/keyrings/jenkins-keyring.asc > /dev/nullecho deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null`
After adding the Jenkins repository, update your package list again:
`sudo apt update`
Now, install Jenkins using the following command:`sudo apt install jenkins -y`
`sudo systemctl start jenkins`
`sudo systemctl enable jenkins`
Adjust Firewall Settings (if applicable)`sudo ufw allow 8080`  
To access Jenkins, open your web browser and navigate to:
`http://your_server_ip:8080` use your vm ipaddress instead of your server ip.