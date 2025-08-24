
# Microsoft Intune Endpoint Management & Conditional Access Project

## Overview
This project demonstrates real-world **IT Support / System Administrator tasks** using **Microsoft Intune**, **Entra ID**, and **Azure**.  
The goal is to simulate **user onboarding**, **device management**, **compliance enforcement**, **app deployment**, and **security policy implementation** in a corporate environment.

---

## Project Objectives
- Onboard new users in Microsoft 365 (example: Navya Sruthi).  
- Create and manage groups (e.g., Sales Department).  
- Enroll devices into Intune for endpoint management.  
- Create **compliance policies** and enforce device security.  
- Deploy Microsoft 365 Apps (Teams, Outlook, Word, Excel).  
- Implement **Conditional Access policies** for secure access.  
- Test and validate device compliance and access controls.  

---

## Step-by-Step Process

### 1. User & Group Creation
- Created a user: **Navya Sruthi**.  
- Created a group: **Sales Department**.  
- Added user to group.  
**Screenshot:** `screenshots/User_Group_Creation.png`

### 2. Device Enrollment
- Enrolled Azure VM (Windows 10 Pro) into Intune.  
- Connected the device to **Entra ID** for management.  
**Screenshot:** `screenshots/Device_Enrollment.png`

### 3. Compliance Policies
- Created compliance policy to ensure device security:  
  - Password required  
  - BitLocker encryption  
  - Windows Defender enabled  
- Device status: **Compliant**  
**Screenshot:** `screenshots/Compliance_Policy.png`

### 4. Device Configuration Profiles
- Configured device security and settings:  
  - USB storage blocked  
  - Windows Firewall enabled  
  - Microsoft Defender Application Guard  
- Applied to Sales Department group.  
**Screenshot:** `screenshots/Device_Config.png`

### 5. App Deployment
- Deployed Microsoft 365 Apps to enrolled VM:  
  - Teams, Outlook, Word, Excel  
- Verified installation on VM.  
**Screenshot:** `screenshots/App_Deployment.png`

### 6. Conditional Access Policy
- Enforced **MFA** for Sales Department.  
- Restricted access to Microsoft 365 if device is non-compliant.  
**Screenshot:** `screenshots/Conditional_Access.png`

### 7. Observations & Testing
- Verified compliance status on enrolled devices.  
- Tested access to M365 apps on compliant vs non-compliant devices.  
**Notes:** `notes/Observations.txt`

---

## Real-World Relevance
This project showcases skills that are critical for **IT Support / Systems Administrator roles**:  
- User onboarding & group management  
- Device enrollment & security enforcement  
- App deployment & configuration  
- Conditional Access & MFA setup  
- End-to-end documentation for IT operations  

---

## Folder Structure
IntuneProject/
├─ docs/
│ └─ IntuneProject.md
├─ screenshots/
│ ├─ User_Group_Creation.png
│ ├─ Device_Enrollment.png
│ ├─ Compliance_Policy.png
│ ├─ Device_Config.png
│ ├─ App_Deployment.png
│ └─ Conditional_Access.png
├─ notes/
│ └─ Observations.txt
