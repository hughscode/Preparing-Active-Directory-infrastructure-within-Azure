# Preparing-Active-Directory-infrastructure-within-Azure

Here we will be putting together Active Directory infrastructure within Azure 



1. Create and/or login to your Azure account.
   (https://github.com/user-attachments/assets/4332649d-c251-43ac-8203-680febdd9c87)

2. Create a Resource Group
   (https://github.com/user-attachments/assets/2067cea0-6e08-49c5-a4b3-ef5b0de98a4d)

3. Create a Virtual Network and Subnet
(https://github.com/user-attachments/assets/a74f1f7e-7331-4015-b666-845aba07ecc0)

4. Create the Domain Controller VM (Windows Server 2022) named “DC-1”
Username: labuser
Password: Cyberlab123!
(https://github.com/user-attachments/assets/e0049366-15ec-49fc-b841-57a03fb25ab9)


5. Setup Client-1 in Azure
—
Create the Client VM (Windows 10) named “Client-1”
Username: labuser
Password: Cyberlab123!
Attach it to the same region and Virtual Network as DC-1
(https://github.com/user-attachments/assets/29d4d6e6-47ec-4fa0-a4e3-72a623c98583)


6. After VM is created, set Domain Controller’s NIC Private IP address to be static
    (https://github.com/user-attachments/assets/a4f268c9-a9cd-43f1-a81d-991db7a09696)


7. Log into the VM and disable the Windows Firewall (for testing connectivity)
(https://github.com/user-attachments/assets/ed8b417d-6a84-4a24-9283-35e21ac577d5)


8. After VM is created, set Client-1’s DNS settings to DC-1’s Private IP address
(https://github.com/user-attachments/assets/2b678200-2fa9-4842-9b55-859c3eb011a1)


9. From the Azure Portal, restart Client-1
(https://github.com/user-attachments/assets/ea6da31c-b7f3-4124-b734-598c01b65995)


10.Login to Client-1
Attempt to ping DC-1’s private IP address
(https://github.com/user-attachments/assets/55c9b03b-1911-4168-a660-4eaedb14a14b)


11. From Client-1, open PowerShell and run ipconfig /all
The output for the DNS settings should show DC-1’s private IP Address
(https://github.com/user-attachments/assets/9147bfa3-36aa-4d9f-bc24-339484f60d5a)











































