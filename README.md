# 🔑 Identity & Access Management – Mini Company Directory (Entra ID Free Tier)

## 📌 Project - 01 Overview
This project simulates a small company's **Identity & Access Management (IAM)** setup using  
**Microsoft Entra ID Free (Azure for Students)**.  
It demonstrates how to manage identities, enforce RBAC, and export directory data in a cloud environment.

---

## ✅ Features Implemented
- 👤 **Users & Groups**
  - Created users: Alice (HR), Bob (IT), Mike (Finance), Marshall (Dev), D_Admin (Admin).
  - Organized into groups: HR, IT Support, Finance, Developers.
- 🔒 **RBAC Role Assignment**
  - Assigned *Password Administrator* role to D_Admin.
- 📊 **Directory Export**
  - Exported users & groups to CSV via the Entra portal.
- 🔄 **Admin Tasks**
  - Password reset for users.
  - Group membership modifications.
- ⚙️ **App Registration**
  - Registered a demo application and reviewed API permissions.

---

## 📂 Repository Contents
- `EntraID_Portfolio_CaseStudy.docx` → Full case study report with screenshots  
- `exportUsers_*.csv` → User directory export  
- `exportGroup_*.csv` → Group directory export  
- `screenshots/` → Evidence of IAM operations (portal UI)  

---

## ⚠️ Limitations (Free Tier)
- Graph API directory calls (`Get-MgUser`, `Get-MgGroup`) return **403 Forbidden** in free/student tenants.  
- Conditional Access, Identity Protection, and scoped SSPR require **Premium (P1/P2)** licenses.  
- Workaround: exports & role assignments done through the Entra portal.  

---

## 🚀 Future Enhancements
If deployed in an enterprise tenant with P1/P2:
- Automate user/group lifecycle via Microsoft Graph PowerShell
- Enforce MFA via Conditional Access
- Apply group-based licensing & advanced identity protection

---

👤 **Author:** Boyon Dey Shipon  
📅 **Date:** August 2025
