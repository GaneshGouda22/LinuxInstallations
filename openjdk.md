## **Introduction of Openjdk:**
OpenJDK is a free version of Java that anyone can use and improve. It has all the important parts of Java, like the compiler, runtime, and virtual machine.
## Versions of openjdk:
Openjdk 8
Openjdk 11
Openjdk 17
Openjdk 21

## Installing Openjdk 17 using tar file:

Ensure that you have a running ubuntu *Virtual Machine* in your system.
[Refer here](https://jdk.java.net/) for copying the openjdk 17 url.
use following commands
`cd /tmp/`
`wget https://download.java.net/openjdk/jdk17.0.0.1/rinjdk-/ope17.0.0.1+2_linux-x64_bin.tar.gz`
 For unzip use this command `tar xvzf pe17.0.0.1+2_linux-x64_bin.tar.gz`
 To permanently add a directory to the PATH environment variable type folling commands
 ` sudo mv jdk.17.0.1 /opt`
 `nano ~/.bashrc`
 `export PATH="$PATH:/opt/jdk.17.0.1/bin"`
 `source ~/.bashrc`
 `echo $PATH`
 To verify installation use `java --version` command.