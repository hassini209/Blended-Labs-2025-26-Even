# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: hassini k
* **Register Number**: 212225040122
* **Date of Submission**: 20:11:2007

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. ---
2. ---
3. ---
4. ---
5. ---

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1257" height="552" alt="image" src="https://github.com/user-attachments/assets/32d62f22-b5b2-4d76-9692-f45787a9455c" />


---

### Screenshot 2: Database Service Running

<img width="1262" height="557" alt="image" src="https://github.com/user-attachments/assets/02ee695b-84a6-426d-9bff-282a53258daf" />
<img width="1267" height="556" alt="image" src="https://github.com/user-attachments/assets/ddf62de4-b856-4d1a-b818-701ec8e5dc2f" />


---

### Screenshot 3: Sample Database and Table

<img width="1130" height="590" alt="image" src="https://github.com/user-attachments/assets/4a579b47-e745-4134-92f5-8e89e141b5c0" />
<img width="1142" height="542" alt="image" src="https://github.com/user-attachments/assets/dbbef9fc-d745-48dd-9531-573d1eba710b" />



---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
