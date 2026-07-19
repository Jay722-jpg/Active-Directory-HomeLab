# Active Directory Home Lab

## Project Overview

This project demonstrates the deployment and administration of a Windows Server Active Directory environment using VirtualBox. The lab simulates common Help Desk and System Administration tasks including user account management, Organizational Units (OUs), security groups, password resets, and account administration.

---

## Scenario

A small business is deploying a Windows Server Active Directory environment to organize employees into departments, manage user accounts, assign security groups, and perform common Help Desk administrative tasks.

---

## Objectives

- Deploy Windows Server 2019
- Configure Active Directory Domain Services
- Create Organizational Units (OUs)
- Create user accounts
- Create security groups
- Assign users to security groups
- Perform password resets
- Simulate common Help Desk tasks

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Hypervisor | VirtualBox |
| Server OS | Windows Server 2019 |
| Client OS | Windows 10 |
| Domain | mydomain.com |
| Tool | Active Directory Users and Computers (ADUC) |

---

## Technologies Used

- Windows Server 2019
- Active Directory Domain Services (AD DS)
- VirtualBox
- Windows 10 Client

---

## Skills Demonstrated

- Creating Organizational Units (OUs)
- Creating User Accounts
- Managing Security Groups
- Assigning Group Memberships
- Password Resets
- User Administration
- Active Directory Users and Computers (ADUC)

---

## Organizational Units Created

- IT
- Human Resources
- Sales
- Finance
- Executive
- Disabled Users

---

## Security Groups

- IT Admins
- HR Staff
- Sales Team
- Finance Team
- Executive Team

---

## Lab Walkthrough

### 1. Organizational Unit Structure

Created Organizational Units for each department to simulate a real enterprise Active Directory environment.

![](images/01-OU-structure.jpg)

---

### 2. Security Groups

Created departmental security groups for permission management.

![](images/02-security-groups.jpg)

---

### 3. Disabled Users Organizational Unit

Created a dedicated OU for disabled user accounts.

![](images/03-disabled-users-OU.jpg)

---

### 4. Executive User Group Membership

Verified that executive users were assigned to the appropriate security groups.

![](images/04-user-group-membership-IT-executive.jpg)

---

### 5. Human Resources User Group Membership

Verified HR user membership within the HR Staff security group.

![](images/05-user-group-membership-HR.jpg)

---

### 6. Creating a New User

Created a new Active Directory user account inside the Human Resources Organizational Unit.

![](images/06-create-new-user.jpg)

---

### 7. User Creation Confirmation

Verified the user account configuration before completing creation.

![](images/07-create-user-confirmation.jpg)

---

### 8. Finance User Group Membership

Verified Finance department user membership.

![](images/08-user-group-membership-finance.jpg)

---

### 9. Password Reset

Performed a password reset for a user account.

![](images/09-password-reset.jpg)

---

### 10. Password Reset Successful

Verified successful password reset confirmation.

![](images/10-password-reset-success.jpg)

---

## What I Learned

During this project I gained hands-on experience with:

- Deploying Active Directory
- Creating Organizational Units
- Managing user accounts
- Assigning security groups
- Resetting passwords
- Performing common Help Desk administrative tasks
- Navigating Active Directory Users and Computers (ADUC)

---

## Future Improvements

- Group Policy Objects (GPOs)
- Shared folders and NTFS permissions
- Domain-joined Windows clients
- PowerShell automation
- Roaming profiles
- Account lockout testing
