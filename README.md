# # MYSQL CRUD Operations Using  Node.js and React. CRUD Real-world Project from scratch. Create,Read,Update and Delete data using a MYSQL database.Development Workflow Automation with React, Node.js, SonarQube, Jenkins, and GitHub.
![image1](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/a292fad4-5a68-4f2f-9e74-dbc042f8ccde)


## Overview
The primary objective of the project is to enhance the efficiency, quality, and reliability of software development through automation and standardization of key processes

**Get The Challenge here**


## Prerequisites

- React Application Development in Visual Studio Code:     Installation of Node.js and npm (Node Package Manager)
- Node.js Backend Application Development in Visual Studio Code:  Installation of Node.js and npm.
- Configuration of SonarQube for Code Quality Checking:  Access to a SonarQube server (either self-hosted or cloud-based), Installation of SonarQube Scanner.
- figuration of Jenkins for Continuous Integration:  Access to a Jenkins server (either self-hosted or cloud-based), Understanding of continuous integration (CI) 
  concepts.
- GitHub Repositories Creation for Project Source Code: Access to a GitHub account.
- Automated Deployment to Development Environment on Successful Check-Ins: Understanding of deployment processes and environments.


## Challenge Steps
- Integration Complexity: Integrating multiple tools and technologies like React, Node.js, SonarQube, Jenkins, and GitHub can be complex. Ensuring seamless communication and data flow between these tools may pose a challenge.

- Tool Configuration: Configuring SonarQube, Jenkins, and other tools to fit the project's specific requirements can be challenging, especially if there are dependencies or conflicting configurations.

- Continuous Integration Pipeline: Setting up a robust continuous integration pipeline with Jenkins, including automated testing, code analysis, and deployment, requires careful planning and configuration.

- Code Quality Standards: Defining and enforcing code quality standards across the development team may face resistance or require adjustments to the existing development practices.

- Version Control: Managing version control, branching, and merging in a collaborative environment with GitHub can be challenging, especially when multiple developers are working on different features simultaneously.


## Application Code
The `Application-Code` directory contains the source code for the Three-Tier Web Application. Dive into this directory to explore the frontend and backend implementations.

## Jenkins Pipeline Code
In the `Jenkins-Pipeline-Code` directory, you'll find Jenkins pipeline scripts. These scripts automate the CI/CD process, ensuring smooth integration and deployment of your application.


## Project Details
🛠️ **Tools Explored:**
- React
- Node.js
- SonarQube
- Jenkins
- GitHub




## Getting Started


### Step 1: Frontend Development with React:

- Create a new React application:
  ``` shell
  npx create-react-app .
  ```
![pro0 11](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/810962a0-a4c6-401c-a7d1-1868622743b2)
  
- Navigate into the project directory:
 ``` shell
 cd my-react-app
  ```
- start the development server: 
 ``` shell
  npm start
  ```
  ![project0 12](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/11b28bf3-5348-474b-bff8-6725acada12f)

 ### Step 2: Backend Development with Node.js:
 - Initialize a new Node.js project:
  ``` shell
 npm init -y
  ```
 ![project1](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/bec60da5-ff9a-462e-9a97-fc474026fd8f)

-Install necessary dependencies (e.g., Express for creating a web server):
 ``` shell
 npm install express
  ```
![project2](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/f2b84381-956d-41a6-90cc-f96e0a8dbf30)


### Step 3: Configure SonarQube to Check Code Quality: Install SonarQube on your system and start the server.
      Configure SonarQube for your projects. You'll need to set up a sonar-project.properties file in your project directory to define properties for SonarQube analysis.

![sonarqube](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/ada8de59-e6d5-46a7-ac0d-3d7dc8c921f2)

![sonarqube1](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/7e2fecb6-182c-4fe8-8074-17c3ac0c267c)

![sonarqube2](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/afc2bb34-329d-4bf8-9fcf-d2edf432b07d)



![sonarqube3](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/55312d57-8f60-479a-8fd5-310bc0b6b4bd)


![sonarqube4](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/f763e118-e439-44fb-ae85-609d437f095c)

![sonarqube5](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/93ed4606-a64d-47f4-be8a-f0601fe1e518)



### Step 4: configure the jenkins 
 - Insatll jenkins on your server or local machinne
 - Access the Jenkins Dasboard.
 -  insall Required pugins
 -  configure Global Tools
 -  Create a new Jenkins job
 -  configure source code management
 -  configure build triggers


![jenkins1](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/a880bb7f-86dc-4dfe-9293-e0185eab0413)


![jenkins4](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/2b90d9a6-0594-4cbd-8490-e2ad354041e4)


![jenkins5](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/38c8cd29-0540-4637-ae8d-d2ab3d0ad56f)



![jenkins6](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/0de2faa8-3bbc-4bef-bb55-cfb790c0a41b)



![jenkins7](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/bd83795d-ec93-406a-b5ac-0ed7f99903f0)

![jenkins8](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/17a575ef-d1ac-41f9-92a2-94b40e475a9a)


![jenkins9](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/7a029f4f-bfd9-420f-8d0f-927fdb60dc53)

![jenkins10](https://github.com/SachinBhatt12/React-Node-Project/assets/109944791/d2591a75-c8be-4ae7-8512-d9aa4b388df5)


   
### Step 5: you can create a repository on GitHub for your React application using commands:
``` shell
# Navigate to your React project directory
cd my-react-app

# Initialize a Git repository
git init

# Add all files to the repository
git add .

# Commit the changes
git commit -m "Initial commit"

# Add the remote GitHub repository
git remote add origin <repository_url>

# Push the code to the remote repository (replace `<branch_name>` with your branch name, e.g., `main` or `dev`)
git push -u origin <branch_name>
Replace <repository_url> with the URL of your GitHub repository and <branch_name> with the name of your branch (e.g., main or dev).

```

### Step 5: To automate deployment to the development environment on successful check-ins to the dev branch, you can use Jenkins pipelines
``` shell

    
pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout your project from version control
                git "https://github.com/SachinBhatt12/React-Node-Project.git", branch:"main"
            }
        }
        
        stage('Install Dependencies') {
            steps {
                // Install Node.js dependencies
                sh 'npm install'
            }
        }
        
        stage('Build') {
            steps {
                // Build your React app
                sh 'npm run build'
            }
        }
        
        stage('Test') {
            steps {
                // Run tests (if applicable)
                sh 'npm test'
            }
        }
        
        stage('Deploy') {
            steps {
                // Example deployment step, replace with your deployment script or commands
                sh 'npm run deploy'
            }
        }
    }
    
    post {
        success {
            // If the pipeline successfully completes
            echo 'Pipeline completed successfully!'
            // You might trigger notifications or other post-build actions here
        }
        failure {
            // If the pipeline fails
            echo 'Pipeline failed!'
            // You might trigger notifications or other post-build actions here
        }
    }
}


```

### Step 6: Automate Deployment to Dev Environment on Successful Check-in
   . Create a Jenkins pipeline in your GitHub repository.
   
   .  Configure the pipeline to trigger on successful check-ins to the dev branch.
   
   . Define stages in the pipeline:
   
      (1) Checkout: Retrieve the code from the dev branch.
      
      (2) Build: Build the React application.
      
      (3) Deploy to Dev: Deploy the application to the development environment.

      
  . Use post-actions to update the version number in package.json and push changes to the dev branch.



## Support
For any queries or issues, please open an issue in the repository.

---
Happy Learning! 🚀👨‍💻👩‍💻
