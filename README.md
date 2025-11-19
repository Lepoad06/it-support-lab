# 🖥️ IT Support Home Lab Portfolio

Welcome to my IT Support Home Lab project.  
This repository documents everything I’ve built, configured, and troubleshot while learning practical IT support, systems administration, and networking skills.

The lab is running on two laptops (Omarach Linux) with several VirtualBox VMs including Ubuntu Server, Windows 11, and Windows Server 2022.

---

## 🚀 Lab Summary

**Technologies Used**
- Windows Server 2022 (Active Directory, DNS, DHCP, GPOs)
- Windows 11 Client
- Ubuntu Linux Server
- VirtualBox virtualization
- SSH, RDP, X2Go remote access
- Bash & PowerShell scripting
- Networking (IP addressing, NAT, Bridged, port forwarding)
- File sharing (SMB, NFS, Samba)
- Web services (Apache)

**Core Skills Practiced**
- Installing and configuring operating systems
- Joining Windows devices to a domain
- Creating and managing users, OUs, and Group Policies
- Managing file permissions and shared drives
- Resolving real-world IT support tickets
- Configuring network settings and troubleshooting connectivity
- Deploying Linux services (SSH, Apache, Samba)
- Writing useful automation scripts

---

## 📁 Repository Structure

### **/vm-setups**  
Step-by-step build notes for every VM in the lab.

### **/active-directory**  
Domain creation, user management, GPOs, and shared folder permissions.

### **/linux**  
Linux server configurations, troubleshooting logs, and service installs.

### **/networking**  
How the lab is networked (VirtualBox configs, IP layout, tools).

### **/tickets**  
Realistic troubleshooting cases logged in IT helpdesk format.

### **/scripts**  
Small Bash and PowerShell scripts used in the lab.

---

## 📘 Highlight Projects

### **1. Active Directory Domain Build (Windows Server 2022)**
- Created a domain: `company.local`
- Added OUs for Departments (IT, HR, Finance, Sales)
- Applied Group Policies:
  - Password policy
  - Mapped drives
  - Desktop restrictions
- Joined Windows 11 client to the domain

### **2. Linux Remote Access & Web Server**
- Installed and configured OpenSSH
- Hosted a simple webpage on Apache
- Set up Samba share with permissions
- Fixed common Linux troubleshooting issues

### **3. Helpdesk Ticket Log**
Real-world style tickets with:
- Symptoms  
- Diagnosis  
- Root cause  
- Fix  
- Verification  

(Located in `/tickets`)

---

## 📸 Screenshots & Diagrams
A visual record of:
- AD Users & Computers  
- Group Policies  
- Ubuntu server terminal  
- Network diagram  
- Troubleshooting results  

Add screenshots to `images/` or embed them inside Markdown files.

---

## 📞 Why This Lab Exists
This project shows my hands-on experience with:
- IT support  
- System administration  
- Troubleshooting  
- Networking  
- Documentation  
- Real IT workflows  

It acts as a public portfolio for employers and demonstrates how I approach real technical work.

---

## 📬 Contact
Feel free to reach out for collaboration or job opportunities.
