# configure-ad

![Image](https://github.com/user-attachments/assets/d010fef4-3330-440b-9b7a-d0b9f017b761)

Created the resource group in Azure needed to run Active Directory and Client VMs

![Image](https://github.com/user-attachments/assets/b58d96eb-4ccb-4f6a-8d8b-ce6ab226fb3e)
![Image](https://github.com/user-attachments/assets/88287a14-0130-4358-9ec9-6b3ef4040094)
![Image](https://github.com/user-attachments/assets/114ba820-f944-4d82-95e1-18b5e5d89b8a)

Created VM to host as Active Directory and Domain Controller(dc-1) that the client VM will connect to. And successfully deployed VM.

![Image](https://github.com/user-attachments/assets/baa04a66-ec35-43e0-9384-16112a7b8636)

Configured the dc-1 VM's private ip address to be static so that the client's VM can connect to the hosted dc-1's network.

![Image](https://github.com/user-attachments/assets/4ec22ab0-b582-48c0-bce4-4f08b6f8250d)
![Image](https://github.com/user-attachments/assets/3afe11f7-224b-45a1-9bb6-d226b8dafa8f)

Created the clients VM(client-1) and connected clients ip to dc-1 private ip. Successfully deployed.

![Image](https://github.com/user-attachments/assets/c7c3683a-1da3-474d-a5f2-80ee344a5b89)

Dc-1 and Client-1 VMs successfully created and now running.

![Image](https://github.com/user-attachments/assets/2de57424-8ce8-4f51-bf95-4a48971dd87b)

Successfully pinged the dc-1's VM private ip address through the Clients VM in Power Shell

![Image](https://github.com/user-attachments/assets/d052c6e4-4d46-449b-b09b-5698ac650d61)

Ran ipconfig in Power Shell through Client's VM to show that the client's DNS is successfully connected to dc-1's Private ip and network.



