# 01 - Initial Setup

## Objective

Access the FortiGate web interface and confirm the default gateway IP address

---

## Step 1: Open Command Prompt

Press:

Windows Key + R

Type:

cmd

Press Enter.

<img width="284" height="166" alt="image" src="https://github.com/user-attachments/assets/18a88f79-774d-4850-9f2d-fab22df6b4a5" />

---

## Step 2: Check IP Configuration

In Command Prompt, type:

ipconfig

Press Enter.
---

## Step 3: Find the Default Gateway

Look for:

Default Gateway

Example:

IPv4 Address . . . . . . . . . . : 192.168.xxx.xxx
Subnet Mask . . . . . . . . . . : 255.255.255.0
Default Gateway . . . . . . . . : 192.168.xx.xxx

The Default Gateway is usually the IP address of the FortiGate LAN interface.
<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/a94b7468-3561-488e-9008-b02dd0531a04" />


---

## Step 4: Open FortiGate Web Interface

Open a browser and enter:

Default Gateway IP:
https://192.168.xx.xxx

---

## Step 5: Login

Login with the administrator account.

Default username:

admin

After logging in, change the default password immediately.

<img width="262" height="146" alt="image" src="https://github.com/user-attachments/assets/04b81024-5d1e-41f5-b06d-724955b0922d" />
