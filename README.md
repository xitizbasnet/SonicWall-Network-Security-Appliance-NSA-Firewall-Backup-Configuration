# 🔥 Firewall Information

## 1.1 SonicWall Network Security Appliance (NSA) Firewall – Configuration Backup Manual

### 📘 Overview

This document defines the **standard operating procedure (SOP)** for performing a configuration backup of the **SonicWall Network Security Appliance (NSA) Firewall**. Maintaining up-to-date firewall configuration backups is critical for **business continuity, disaster recovery, compliance audits, and rapid restoration** in the event of system failure or misconfiguration.

---

### 🎯 Objective

* Ensure secure and consistent backup of firewall configurations
* Enable fast recovery during incidents or hardware replacement
* Maintain version-controlled configuration records

---

## 🛠️ Step 1: Access the Firewall Web Interface

1. Open a supported web browser (Chrome, Edge, or Firefox).

2. Navigate to the SonicWall firewall management interface using the following URL:

   ```
   https://192.168.100.1/auth.html
   ```

3. Enter the required administrative credentials on the login screen:

   | Parameter | Value                                                              |
   | --------- | ------------------------------------------------------------------ |
   | URL       | [https://192.168.100.1/auth.html](https://192.168.100.1/auth.html) |
   | Username  | admin                                                              |
   | Password  | **************                                                     |

4. Click **Login** to access the firewall dashboard.

---

## ⚙️ Step 2: Navigate to System Settings

1. From the left-hand navigation panel, select **System**.
2. Click **Settings** under the System menu to access system-level configuration options.

---

## 📤 Step 3: Export Firewall Configuration

1. Locate and click the **Export Settings** option.
2. A new browser window or pop-up dialog will appear displaying export options.
3. Click **Export** to initiate the configuration backup process.
4. The firewall configuration file will be automatically downloaded and saved to the system’s default **Downloads** directory.

---

## 🔐 Step 4: Secure and Store the Backup

1. Navigate to the **Downloads** folder on your local workstation.
2. Verify that the configuration file has been successfully downloaded.
3. Move or copy the backup file to the designated directory on the **centralized backup server** or secure storage location.

> **Best Practice:**
> Always use a standardized naming convention to maintain proper version control and traceability.
>
> **Example:**
>
> ```
> SonicWall_Backup_YYYY-MM-DD.exp
> ```

---

## 🚪 Step 5: Logout from the Firewall

1. Click the **Logout** option located in the top-right corner of the SonicWall web interface.
2. Confirm logout to securely terminate the administrative session.

---

### 📌 Notes & Recommendations

* Perform configuration backups **after every major change**.
* Store backup files in **restricted-access locations only**.
* Periodically validate backup files by test restoration (where applicable).
* Do not share firewall credentials outside the IT Security Team.

---
