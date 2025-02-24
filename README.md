# 🔧 **Computer Troubleshoot**

## **Storage Troubleshoot**
### chkdsk
- This command stands for “Check Disk.” It scans the file system and file system metadata of a volume for logical and physical errors. 

#### Here's how to use it:
1. Find the cmd prompt
2. **Run as Administrator** to have the necessary permissions.
3. Type ```chkdsk``` and hit Enter.

![374924597-dc637c62-2731-40dc-93a1-c85d4d24e253](https://github.com/user-attachments/assets/60691a44-6a6d-464f-9182-ba10ea4bfc6e)

After checking several minutes and without **Error**, here's what it looks like:

![374925612-47a1f8e5-cb62-4c91-87a8-2b9b90604ab5](https://github.com/user-attachments/assets/81e9c92b-9165-4855-892f-79a31c8d5459)

> [!TIP]
> There are 3 types of way to use it.

> [!WARNING]
> If the Check Disk Error here's what you need to do.

## 1. **chkdsk /r**
- This variant of the chkdsk command locates bad sectors on the disk and attempts to recover readable information from them.

#### Here's how to use it:
1. Find the cmd prompt
2. **Run as Administrator** to have the necessary permissions.
3. Type ```chkdsk /r``` and hit Enter.
4. Type ```Y``` (Yes) and hit Enter.

![374927523-8fb7e04b-50d8-4b5d-be33-f44ae450d209](https://github.com/user-attachments/assets/111b644c-b8b9-429f-b859-f518b806745a)

Then wait for a several minutes for automatic repairing your storage.

> [!TIP]
> Another tip for troubleshooting using a cmd.

### **sfc /scannow**
- A command that scans all protected system files on a Windows system for integrity violations and repairs any corrupted or missing files automatically.

#### Here's how to use it:
1. Find the cmd prompt.
2. **Run as Administrator** to have the necessary permissions.
3. Type ```sfc /scannow``` and hit Enter.

![374935622-eed46299-3a98-40ff-884f-a4ebfc002c7c](https://github.com/user-attachments/assets/27ff3372-c616-45d8-b119-cc9aa32a54f8)

### **clean (DiskPart)**
- The _**clean**_ command in DiskPart is used to remove all partitions and volumes from the selected disk. This effectively wipes the disk, making it appear as if it were new and uninitialized.

> [!WARNING]
> Make sure that it is backed up before you **clean** the partitions.
  
#### Here's how to use it:
1. Find the cmd prompt.
2. **Run as Administrator** to have the necessary permissions.
3. Type ```Diskpart```and hit Enter.
4. Type ```List Disk```and hit Enter.
5. Type ```Select Disk 0,1,2,3...``` (which disk number you want to work with) and hit Enter.
6. Type ```Clean```and hit Enter.
7. Exit

![diskpart](https://github.com/user-attachments/assets/85bb08af-a463-4e70-89ea-5fdc8d17f8f2)

## **Network Troubleshoot**

### **ipconfig**
- Displays the current network configuration of your computer, including IP addresses, subnet masks, and default gateways. It’s essential for diagnosing network issues.

#### Here's how to use it:
1. Find the cmd prompt.
2. **Run as Administrator** to have the necessary permissions.
3. Type ```ipconfig``` and hit Enter.

#### **Key Options:**
- **ipconfig /all**: Displays detailed information about all network interfaces.
- **ipconfig /release**: Releases the current IP address.
- **ipconfig /renew**: Renews the IP address from the DHCP server.
- **ipconfig /displaydns**: Displays the contents of DNS cache, it holds all the recently domain names and their IP Addresses.
- **ipconfig /flushdns**: Clears the DNS resolver cache, which can help with connectivity issues.


Using ipconfig, you can quickly identify connectivity problems, ensure your network settings are correct, and refresh your connection.
