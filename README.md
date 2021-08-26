# Setting-up-Maven-in-Jenkins

Steps to setup Maven in Jenkins-

*As Root*
```

1. Open the terminal and go to Jenkins dashboard by typing localhost:8081 in your browser. Click on Manage Jenkins. From the list of options, choose Manage Plugins. Under the Available tab, select Maven Integration. Click on Install without restart and the plugin will be installed.

2. Go to https://maven.apache.org/download.cgi and download the binary zip file

3. Unzip and extract the file and copy the path.
$ cd /home/labsuser/Downloads
$ unzip apache-maven-3.6.3-bin.zip

4. Go to Manage Jenkins from the Jenkins dashboard and select Global Tool Configuration. Scroll down to the Maven section and click on Add Maven. You can choose to install automatically by ticking .the checkbox and specifying the version, or uncheck the box and enter the local path if you want to configure manually. We will install the downloaded file. 

5. Enter a name for the installation (For Example: my_maven). Uncheck the Install automatically checkbox. Paste the path to the Maven file in the MAVEN_HOME field </home/labsuser/Downloads/apache-maven-3.6.3> and click Save. You can now find Maven project as an option under New Item.

6. Go to Manage Jenkins from the Jenkins dashboard and select Global Tool Configuration. Scroll down to the JDK Section and click on Add JDK. You can choose to install automatically by ticking the checkbox and specifying the version. Uncheck the box if you want to enter the JDK path manually. Enter the path to the JDK in the JAVA_HOME field (/usr/lib/jvm/java-8-openjdk-amd64/) and click Save.

```
*As Root*


 




