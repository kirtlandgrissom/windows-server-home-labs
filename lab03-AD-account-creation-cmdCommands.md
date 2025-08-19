# Lab 03: Active Directory Account Creation & Common CMD Commands  

**Date**: 8/18/2025  

---

### 🎯 Objective  
- Create and manage Active Directory user accounts.  
- Learn to use the **copy method** for faster account creation.  
- Configure a static IP address.  
- Practice essential command-line tools for user and network management.  

---

### 🛠️ Steps Taken  

- Opened **Server Manager Dashboard** → **Tools** → **Active Directory Users and Computers**.  

- Created a new user by right-clicking **Users** → **New** → **User**, then filling out required details.  

- Located users with the **Find** option and expanded searches using **Advanced Features** to view object paths.  

- Used the **Copy User** feature (from Administrator) to create accounts with preconfigured settings.  

- Configured a **Static IP Address** via Control Panel → Network Settings → IPv4 properties.  

---

### 🖼️ Screenshot  

## Add user to AD 
![regular settings](./screenshots/lab03/regular-settings.png)

## Adding user with advance features
![](./screenshots/lab03/advance-features.png)


## Copying user in AD
![](./screenshots/lab03/copyuser1.png)
![](./screenshots/lab03/copyuser2.png)
![Comparing help desk user copy to admin user](./screenshots/lab03/Comparison.png)

## Enabling recycle bi
![Enable recycle bin](./screenshots/lab03/Enable-recycle.png)

## setting up static IP address
![static set up](./screenshots/lab03/Static-IP1.png)
![static set up](./screenshots/lab03/Static-IP2.png)
![static set up](./screenshots/lab03/Static-IP3.png)

### CMD commands

## Ipconfig all

![Ipconfig all](./screenshots/lab03/Ipconfig-all.png)

## Ipconfig

![Ipconfig](./screenshots/lab03/Ipconfig.png)

## net use

![net use](./screenshots/lab03/net-use.png)

## net user

![net user](./screenshots/lab03/net-user.png)

---

### 🧠 What I Learned  

- **Active Directory**  
  - How to create user accounts manually and with the copy method.  
  - Using **Advanced Features** to view object paths and gain more control.  
  - Enabling the **Recycle Bin** for recovery of deleted AD objects.  

- **Networking**  
  - Why static IP addresses are useful for devices like printers (to avoid DHCP reassignment issues).  

- **Command-Line Tools**  
  - `ipconfig` → View current TCP/IP configuration.  
  - `ipconfig /all` → View full details including DHCP server info.  
  - `net use` → Display mapped/shared drives.  
  - `net user <domain\username> /domain` → Check account details (password policies, group membership, expiration).  

---



