
# Banking App with Spring Boot - DevOps Pipeline
### This Spring Boot-based banking application allows users to create accounts, transfer money, request loans, view balances, and check transaction history. Admins can manage users and transactions with CRUD operations. 



## Role Features:
#### User
Create account, transfer money, request loans, view balance, and transaction history.

#### Admin 
Manage users, approve/reject loans, and access all transaction history.
### DevOps & CI/CD:
#### 1 ) CI/CD Pipeline: Automated using AWS CodePipeline and CodeDeploy, ensuring continuous integration and deployment.

#### 2 )  AWS Integration: The app is deployed on AWS EC2, with automated build and deployment triggered by GitHub commits.
#### 3 ) Build & Test: Maven is used for build and unit tests during deployment. 
#### 4 ) Automated Deployment: Deployment scripts and hooks handle server setup, permission management, and application startup on EC2.

### Technologies: 
#### 1 ) Spring Boot: Backend framework.
#### 2 ) AWS EC2, CodeDeploy, CodePipeline: For deployment and continuous delivery.
#### 3 ) GitHub: Version control for the project.
