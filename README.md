# My Maven Project 🚀

This is a simple Java 21 project managed with Apache Maven. It includes unit testing with JUnit 5 and a Jenkins pipeline for continuous integration.


## 📂 Project Structure

my-maven-project/ │-- src/ │ ├── main/ │ │ ├── java/com/example/app/ │ │ │ ├── App.java # Main application entry point │ ├── test/ │ │ ├── java/com/example/app/ │ │ │ ├── AppTest.java # Unit test file │-- pom.xml # Maven configuration file │-- Jenkinsfile # Jenkins pipeline configuration │-- README.md 

## 🛠 Creating the Folder Structure  

### **On Windows (PowerShell)**
Open PowerShell and run:

- mkdir my-maven-project/src/main/java/com/example/app
- mkdir my-maven-project/src/test/java/com/example/app
- New-Item -ItemType File my-maven-project/src/main/java/com/example/app/App.java
- New-Item -ItemType File my-maven-project/src/test/java/com/example/app/AppTest.java
- New-Item -ItemType File my-maven-project/pom.xml
- New-Item -ItemType File my-maven-project/Jenkinsfile
- New-Item -ItemType File my-maven-project/README.md

# 🔧 Prerequisites

Before you build and run this project, ensure you have the following installed:

- **Java 21**  
- **Apache Maven** (Latest version recommended)  
- **Git**  
- **Jenkins** (Optional, for CI/CD pipeline)  

## 🚀 Getting Started

### **1️⃣ Clone the Repository**
Open a terminal and run:
- git clone https://github.com/Miraaqib786/my-maven-project.git
- cd my-maven-project

### Build the Project
- mvn clean package
- mvn test
- mvn exec:java
