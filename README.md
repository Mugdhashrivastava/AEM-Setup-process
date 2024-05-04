# AEM-Setup-process
# How to set AEM 6.5 with the project (Unity Water)

Hi! I'm Mugdha Shrivastava and in this article, I am going to tell you how to set AEM, that is Adobe Experience Manager step by step. Here I am downloading the 6.5 version and taking the project of my own for example that is Unity Water project


## Download pre-requisites for aem

1. Maven-3: It is necessary to download Maven with version 3 check out this article
 [How to install maven in the system](https://phoenixnap.com/kb/install-maven-windows)

2. Java-11:Download the java-11 in the system
[How to install java 11](https://phoenixnap.com/kb/install-java-windows)

 the downloaded file [Downloaded file to use directly](https://drive.google.com/file/d/1QlwGHV3z_lFKXVz7r50yV03dccQ7z-AG/view?usp=drive_link)


## Download aem from the zip file 


## Download packages of project
For example, I took a package of unity water from my manager and uploaded it in crx of AEM
CRX stands for content repository extreme where you can find all the repositories of your file and folder, upload packages, create package

## Download VS Code
To write code if you haven't already (I am assuming you are a beginner heh)

## Download node
We need node js in the system and npm to run our project so download it from any browser and check in a terminal by typing " npm --version" or "node version"
Since I am a Mac user I do not need to do so but you have to keep the settings updated in your environment variable which is found just by typing environment variable

## Download necessary vs code extension
### AEM VScode Sync 
The AEM Sync extension in vs code will help you to easily export/import your code from aem to vs Code 
- In my project Unity Water of Homsglen or I-blog of IndusInd Bank I only coded in VS Code and then exported the code to Aem
- How to export? Just write your code in vs code and in side bar right click on the folder you want to export and have made changes into click on export to AEM and boom your code is available in AEM too


## Set your project code base in VS code 
### Download GitHub desktop or you can use commands too
Clone the git repository from the main branch of the project and open that folder in vs code 

# Running commands 
In your project type this command 
```bash
mvn clean install -PautoInstallSinglePackage
```




