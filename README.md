# 🔧 **Computer Troubleshoot**

## **Storage Troubleshoot**
### chkdsk
- This command stands for “Check Disk.” It scans the file system and file system metadata of a volume for logical and physical errors. 

#### Here's how to use it:
1. Find the cmd prompt
2. **Run as Administrator** to have the necessary permissions.
3. Type 
chkdsk
 and hit Enter.

![chkdsk command prompt](https://github.com/user-attachments/assets/dc637c62-2731-40dc-93a1-c85d4d24e253)

![374924597-dc637c62-2731-40dc-93a1-c85d4d24e253](https://github.com/user-attachments/assets/60691a44-6a6d-464f-9182-ba10ea4bfc6e)


After checking several minutes and without **Error**, here's what it looks like:

![chkdsk result](https://github.com/user-attachments/assets/47a1f8e5-cb62-4c91-87a8-2b9b90604ab5)

> [!WARNING]
> If the Check Disk Error here's what you need to do.

### **chkdsk /r**
- This variant of the chkdsk command locates bad sectors on the disk and attempts to recover readable information from them.

#### Here's how to use it:
1. Find the cmd prompt
2. **Run as Administrator** to have the necessary permissions.
3. Type 
chkdsk /r
 and hit Enter.

![chkdsk repair result](https://github.com/user-attachments/assets/8fb7e04b-50d8-4b5d-be33-f44ae450d209)

> [!TIP]
> Another tip for troubleshooting using a cmd.

### **sfc /scannow**
- A command that scans all protected system files on a Windows system for integrity violations and repairs any corrupted or missing files automatically.

#### Here's how to use it:
1. Find the cmd prompt.
2. **Run as Administrator** to have the necessary permissions.
3. Type 
sfc /scannow
 and hit Enter.

![sfc scannow result](https://github.com/user-attachments/assets/eed46299-3a98-40ff-884f-a4ebfc002c7c)

## **Network Troubleshoot**

### **ipconfig**
- Displays the current network configuration of your computer, including IP addresses, subnet masks, and default gateways. It’s essential for diagnosing network issues.

#### Here's how to use it:
1. Find the cmd prompt.
2. **Run as Administrator** to have the necessary permissions.
3. Type 
ipconfig
 and hit Enter.

#### **Key Options:**
- **ipconfig /all**: Displays detailed information about all network interfaces.
- **ipconfig /release**: Releases the current IP address.
- **ipconfig /renew**: Renews the IP address from the DHCP server.
- **ipconfig /displaydns**: Displays the contents of DNS cache.
- **ipconfig /flushdns**: Clears the DNS resolver cache.

Using ipconfig, you can quickly identify connectivity problems, ensure your network settings are correct, and refresh your connection.
