# 🚗💡 Automotive Lighting Remote Testing Platform  
### Final Year Internship Project – Primatec

---

## 📌 Project Overview

This project was developed during my final-year internship at **Primatec**.

I developed a web-based testing platform that allows testers to execute tests on a **physical automotive mock-up** simulating a car’s exterior lighting system (parking, driving, braking, etc.).

The platform supports **three types of testing**:

1. **Manual Testing** – testers execute tests manually by interacting with the mock-up’s buttons.  
2. **Automation Testing** – testers write test cases using **Robot Framework**, which are sent to the mock-up for automatic execution; results are returned directly to the platform.  
3. **Jenkins Pipeline Execution** – testers select a test case from the application; a Jenkins pipeline is automatically triggered, communicates with the mock-up via SSH, executes the test, and returns results to Jenkins, displayed in the application.

Testers can **download logs and reports**. For software bugs, testers can create **Jira tickets** directly from the app. The application is **deployed on a server**, allowing remote, end-to-end testing without local installation.

---

## 🛠️ Technologies Used

 Front-End: 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original.svg" width="30"/> Angular 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="30"/> TypeScript 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain.svg" width="30"/> Bootstrap  

 Back-End: 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/springboot/springboot-original.svg" width="30"/> Spring Boot 
<img src="https://img.icons8.com/ios-filled/50/000000/api-settings.png" width="30"/> REST APIs 
<img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" width="30"/> FastAPI  

Testing & Automation: 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" width="30"/> Jenkins 

 Database: 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="30"/> MySQL  
 DevOps: 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="30"/> Docker & Compose 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="30"/> Git  

 Project Management: 
<img src="https://img.icons8.com/ios-filled/50/000000/scrum.png" width="30"/> Scrum 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jira/jira-original.svg" width="30"/> Jira

---

## 🔌 Hardware Communication

The platform communicates with a **real automotive lighting hardware mock-up**.  
Test cases trigger physical signals on the mock-up, executed and logged in real time, creating a realistic industrial testing environment.

---

## 👥 Team & Methodology

- Developed in a team using **Agile Scrum**  
- **Jira** for task tracking  
- **Git** for version control  

---

## 🎬 Demo

Watch the application demo here:

[![Watch the Demo](Images/demo-SignUp.png)](https://vimeo.com/1165653912)

---

## 📸 Screenshots

### 🔹 SignUp  
![SignUp](Images/SignUp.png)

### 🔹 SignIn  
![SignIn](Images/SignIn.png)

### 🔹 Home Page  
(User selects the type of mock-up: Light mock-up for car lights, Window mock-up for windows, etc.)  
![Home Page](Images/Home-page.png)

### 🔹 User Management  
(Admin can delete, edit, accept/reject users, change roles, and invite to Jira)  
![User Management](Images/User-Manager.png)

### 🔹 File Management  
(Admin can upload Excel files with users; system automatically imports them)  
![File Management](Images/File-Manager.png)

### 🔹 Automation Testing Interface (Git)  
(Test cases synchronized with Git repository)  
![Automation Testing - Git](Images/Automation Testing-Git.png)  
![Git Repository](Images/git repo.png)

### 🔹 Automation Testing Interface (Local)  
(Testers can import test cases from their local machine)  
![Automation Testing - Local](Images/Automation Testing-local.png)

### 🔹 Testing with Jenkins Interface  
![Testing with Jenkins](Images/Testing-with-jenkins.png)

### 🔹 Jenkins Pipeline  
(Jenkins executes test case via SSH, returns results, and sends email notifications)  
![Jenkins Pipeline](Images/jenkins-Pipline.png)

### 🔹 Email Notification  
![Email](Images/Email.png)

### 🔹 Jenkins Results in Application  
![Results in Application](Images/Result-jenkins-in-application.png)

### 🔹 Downloaded Results  
![Downloaded Results](Images/Result-dowloaded.png)

### 🔹 Jira Ticket Interface  
(Synchronized with Jira for bug tracking)  
![Tickets](Images/Tickets.png)  
![Jira Interface](Images/Jira-interface.png)

---

## 🏆 Achievement

🏅 Selected as **Best Final Year Project – ENET’Com Promotion 2025**  
🎓 Presented at the **University Fair 2025 (univExpo2025)**  

### 📸 University Fair Presentation  
![University Fair](Images/university-fair-1.jpg)  
![University Fair](Images/university-fair-2.jpg)
