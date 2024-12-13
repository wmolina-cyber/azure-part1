# Azure Computing and Networking Lab - Part 1
![image](https://github.com/user-attachments/assets/73a77ce4-ce4f-44c6-99c0-25e5da4c90e7)

## Overview
This lab is the first part of a series focusing on Azure computing and networking. In this part, I learned how to:

- Create a Resource Group
- Deploy two Virtual Machines (VMs): one Windows 10 and one Linux (Ubuntu)
- Configure the VMs within the same Virtual Network and Subnet

## Objectives
1. Create a Resource Group.
2. Deploy a Windows 10 Virtual Machine (VM).
3. Deploy a Linux (Ubuntu) VM.
4. Configure both VMs to be in the same Virtual Network and Subnet.

---

## Steps

### 1. Created a Resource Group
1. Logged in to the [Azure Portal](https://portal.azure.com/).
2. Navigated to **Resource Groups** and clicked **+ Create**.
3. Provided a name for the Resource Group (e.g., `RGNetworkActivities`).
4. Selected a region and clicked **Review + Create**.

![5](https://github.com/user-attachments/assets/53c78ff0-0a4a-44de-a0fa-cddc05b87b05)

---

### 2. Created a Windows 10 Virtual Machine
1. Navigated to **Virtual Machines** and clicked **+ Create** > **Azure Virtual Machine**.
2. Selected the previously created Resource Group.
3. Chose **Windows 10 Pro** as the image.
4. Allowed Azure to create a new **Virtual Network (Vnet)** and **Subnet**.
5. Completed the VM creation process.

![10](https://github.com/user-attachments/assets/1c3ebbb3-4299-40d1-99ec-fd19f1cab830)

---

### 3. Created a Linux (Ubuntu) Virtual Machine
1. Navigated to **Virtual Machines** and clicked **+ Create** > **Azure Virtual Machine**.
2. Selected the same Resource Group created earlier.
3. Chose **Ubuntu Server 22.04 LTS** as the image.
4. Ensured the VM is connected to the same **Virtual Network** and **Subnet** as the Windows 10 VM.
5. Set the authentication type to **Username/Password** and completed the creation process.

![21](https://github.com/user-attachments/assets/6d6a0b22-16bd-45e0-a848-8440601cf117)

---

### 4. Verified Configuration
1. Verified that both VMs are deployed and running.
2. Checked the **Networking** tab for each VM to confirm they are in the same Virtual Network and Subnet.

![26](https://github.com/user-attachments/assets/d7ebe323-c14d-4781-b4aa-4296461c6983)

---

## Future Parts
This is Part 1 of a multi-part lab. In Part 2, we will focus on connecting and configuring these VMs for communication and further tasks.

---
