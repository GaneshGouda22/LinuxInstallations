## **Introduction of Maven:**
Maven is a powerful build automation and project management tool primarily used for Java-based projects. It simplifies the build process and helps manage various aspects of a project's lifecycle
### Key Features of Maven
*Simplifies the build process*: Maven shields developers from many build-related details, making the process easier.
*Provides a uniform build system*: Once you familiarize yourself with one Maven project, you know how all Maven projects build, saving time when navigating many projects.
*Manages project dependencies*: Maven automatically downloads required libraries and manages their versions, eliminating the need to manually visit websites to obtain dependencies.
## Installing Maven using tar file:

use folling commands
`sudo apt update`
`sudo apt install openjdk-17-jdk`
[Refer here](https://maven.apache.org/download.cgi) for copying maven url.
`wget https://dlcdn.apache.org/maven/maven-3/3.9.8/binaries/apache-maven-3.9.8-bin.tar.gz
--2024-08-02 11:53:12--  https://dlcdn.apache.org/maven/maven-3/3.9.8/binaries/apache-maven-3.9.8-bin.tar.gz`
For unzip use this`tar xvzf apache-maven-3.9.8-bin.tar.gz`
`ls -l`
 `mv apache-maven-3.9.8 /opt/`
 `nano ~/.bashrc`
 `export PATH="$PATH:/opt/maven-3.9.8/bin"`
 `source ~/.bashrc`
 `echo $PATH`
 To verify installation use `mvn --version` command.
