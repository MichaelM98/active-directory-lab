<p align="center">
  <img src="https://github.com/user-attachments/assets/1675c958-b951-421f-99b8-e492f7771a17" alt="Active Directory Logo" width="300"/>
</p>

# **Active Directory Deployment and Configuration**

This repository demonstrates my ability to deploy and configure **Active Directory Domain Services (AD DS)** in a Microsoft Azure environment. It highlights my skills in domain setup, user management, and network configuration.

---

## **Skills Demonstrated**
- Deploying virtual machines in Microsoft Azure.  
- Configuring Active Directory Domain Services (AD DS).  
- Managing Organizational Units (OUs) and user permissions.  
- Automating user account creation with PowerShell.  
- Setting up and testing Remote Desktop access.  

---

## **Environment**
- **Cloud Platform:** Microsoft Azure  
- **Virtual Machines:** Windows Server 2022 (DC-1), Windows 10 (Client-1)  
- **Domain Name:** `mydomain.com`  
- **Tools Used:** Active Directory Users and Computers (ADUC), PowerShell, Remote Desktop  

---

## **Key Milestones**

### **1. Configuring a Static IP for DC-1**  
- Assigned a **static IP address** to ensure consistent communication with clients.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/74e32f97-90c3-4747-ae7e-d3d0e5fa8e27" alt="Setting DC1 Private IP to Static" width="400"/>
</p>

---

### **2. Promoting the Domain Controller**  
- Set up a new Active Directory forest named **mydomain.com**.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/715197df-bb7b-45e0-af0f-4cbcc7606158" alt="Promoting DC" width="600"/>
</p>

---

### **3. Creating Organizational Units (OUs)**  
- Organized the domain structure with the following OUs:  
   - **_ADMINS** for administrative users.  
   - **_EMPLOYEES** for standard users.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/ec83f1d6-cc3b-4009-a6e1-ad1896ea6c82" alt="Adding Users" width="800"/>
</p>

---

### **4. Assigning Admin Permissions**  
- Assigned the user **jane_admin** to the **Domain Admins** group for administrative privileges.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/3d33b30e-a2e5-48b6-8646-e27ded6b49f7" alt="Setting Jane to Admin" width="400"/>
</p>

---

### **5. Automating User Account Creation**  
- Used **PowerShell** to automate the creation of user accounts in the **_EMPLOYEES** OU.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/75b54abe-0b00-497b-8fe9-94639b013bd2" alt="All Employees Added" width="900"/>
</p>

---

### **6. Configuring DNS and Verifying Client-1**  
- Configured **Client-1** to use DC-1 as its DNS server.  
- Verified proper DNS resolution and domain connectivity using `ipconfig /all`.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/2b9590a1-9a11-46f0-b388-4c59a0a6f206" alt="ipconfig all Output on Client-1" width="800"/>
</p>

---

### **7. Enabling Remote Desktop for Domain Users**  
- Allowed **Domain Users** to access **Client-1** via Remote Desktop.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/b947252a-1144-48bb-a6a4-a8f59fa524c7" alt="Screenshot 2024-12-16 163513" width="400"/>
</p>

---

## **Reflection**  
Through this project, I demonstrated my ability to:  
- Deploy and configure Active Directory in a cloud environment.  
- Manage user roles, permissions, and domain structure effectively.  
- Use automation (PowerShell) to streamline user account creation.  
- Configure network settings for domain connectivity.
