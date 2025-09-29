
# linux-sysadmin-project-01
# User Management, SSH & Firewall 
##  Overview  
This mini project demonstrates essential Linux administration tasks:  
- Creating and managing users  
- Assigning sudo privileges  
- Setting up project directories  
- Enabling SSH for remote login  
- Configuring firewall (UFW) for security  
- Testing remote access from a MacBook host  

It’s a hands-on exercise designed to practice **junior SysAdmin / DevOps fundamentals**.  

---

## Steps & Screenshots  

### 1. Create Users  
Added two users:  
- user1 (with sudo rights)  
- user2 (no sudo access)  

![Add User1](screenshots/01-adduser1.png)  
![Add User2](screenshots/03-adduser2.png)  

---

### 2. Assign Sudo to `user1`  
Gave user1 administrator privileges.  

![Usermod Sudo](screenshots/02-usermod-sudo.png)  

---

### 3. Verify Groups  
Confirmed group membership for both users.  

![Groups](screenshots/04-groups.png)  

---

### 4. Create Project Directory  
Created /home/user1/projects and set proper permissions.  

![Projects Directory](screenshots/05-projects-dir.png)  

---

### 5. Enable SSH  
Installed and activated SSH server.  

![SSH Service](screenshots/06-ssh-service.png)  

---

### 6. Configure Firewall  
Allowed SSH traffic with UFW.  

![UFW](screenshots/07-ufw.png)  

---

### 7. Get VM IP Address  
Checked the internal IP for remote connection.  

![IP Address](screenshots/08-ip-addr.png)  

---

### 8. Remote SSH Access  
- Connected as user1 → sudo access works  
- Connected as user2 → no sudo rights  


![Sudo User1](screenshots/11-sudo-user1.png)  
![Sudo User2](screenshots/12-sudo-user2.png)  

---

##  Conclusion  
This project shows how to:  
- Manage Linux users and groups  
- Control access with sudo  
- Secure a server with SSH and UFW  
- Connect remotely from another machine  

A small but complete **Linux SysAdmin mini project** to showcase system administration fundamentals.  
