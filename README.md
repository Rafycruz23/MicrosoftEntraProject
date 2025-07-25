# Identity & Access Management with Microsoft Entra




Welcome to this project on **Identity and Access Management (IAM)** using **Microsoft Entra**. This guide walks you through the process of managing users and access within a Microsoft 365 cloud environment.

<img width="400" height="700" alt="1" src="https://github.com/user-attachments/assets/a0bbfa07-c248-4687-9325-95ece32d4bc5" />

---

## 📘 Overview

This hands-on walkthrough demonstrates how to:

- Navigate the Microsoft Entra Admin Center
- Create internal and external users
- Assign roles and manage permissions
- Enhance security using modern identity tools

---

## 🔹 Step-by-Step Instructions

### Step 1: Access Microsoft Entra Admin Center

<img width="400" height="700" alt="2" src="https://github.com/user-attachments/assets/5c89999b-6407-4052-8a60-08e2470e2e97" />


Begin by logging into the [Microsoft Entra Admin Center](https://entra.microsoft.com) and selecting **Users** from the left panel. This is where all identity and access tasks begin.

---

### Step 2: Create a New User

<img width="400" height="700" alt="3" src="https://github.com/user-attachments/assets/6341358a-73e7-4fbb-83f3-7089724db88f" />

Click on **New user** to begin creating an internal user. Enter details such as name, username, and location. Set a temporary password if needed.

---

### Step 3: Fill in User Details and Assign Roles

<img width="400" height="700" alt="4" src="https://github.com/user-attachments/assets/a220935a-9b14-4af4-8018-340cf74e795a" />

Provided the new hire its approiate roles. 

---

### Step 4: Assign license

<img width="400" height="700" alt="5" src="https://github.com/user-attachments/assets/147190e8-1740-487d-a5c6-776e977087ab" />


Assign the new user to the Microsoft Office License. In this case MSOffice E5.

---

### Step 5: Create Groups in Entra

<img width="400" height="700" alt="6" src="https://github.com/user-attachments/assets/929ce69e-a604-4ac7-815d-782f129ab61d" />

Created a "Security" Group for provisioning permissions. Also configured the Dynamic membership rule to automatically assign this group if new user meets criteria.

---

### Step 6: Add an Owner to the Group

<img width="400" height="700" alt="7" src="https://github.com/user-attachments/assets/90794c58-3971-4ea4-b351-ee7e9719b9c4" />


Confirm the Security Group was added and that Rafael is the owner.
---

### Step 7: Confirm Dynamic Rules in effect

<img width="400" height="700" alt="8" src="https://github.com/user-attachments/assets/2bd4135a-6663-4473-8178-f84f7c363762" />


Here we can confirm that the Dynamic Rules are working effectively. 
---

### Step 8: Configure MFA

<img width="400" height="700" alt="9" src="https://github.com/user-attachments/assets/466c4265-326d-4a6f-90bf-cefbd6c3af25" />


In this step we enable and enforce MFA for the users. This ensures another layer of security. 

---

### Step 9: Configure MFA (Continued)

<img width="400" height="700" alt="10" src="https://github.com/user-attachments/assets/e35581e0-2d02-470c-84d0-430a75711c11" />


Create a MFA Policy for conditional access requiring the usage of MFA for authentication. 

---

## 👨‍🏫 Presented By

**Rafael Omar Cruz**  
ROC TECH

---

## 🛠️ Technologies Used

- Microsoft Entra (Azure Active Directory)
- Microsoft 365 Admin Center
- IAM Best Practices
