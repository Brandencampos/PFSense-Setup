# PFSense-Setup
## Objective
Setting up PFSense to gain experience with this open source firewall. 


### Skills Learned

- Proficiency in configuring and setting up pfSense
- Creation of a private network within Virtualbox for set up


### Tools Used
- PFSense

## Steps 
- Created a new VM for PfSense in Virtual box
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/aea95f83-8761-4150-be35-04dd5583d673)
- Attaching the NAT Network that I created 
![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/f11aa554-c7be-4344-95e7-cc5caf0a603d)
- Once we run the VM we'll hit accept
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/091465ad-c0a6-49ab-b979-8d2b3c308eeb)
- After setting the WAN and Lan pfSense will install and we'll get to this page
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/8f7de0dd-62a1-4484-b90c-3ce9cfadf3c0)
- Going to start our windows 10 vm that is set on the same network as pfSense
- Once the Machine starts we'll double check to see if we need to configure any network settings
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/4046d58b-e970-46b6-89a9-2458e8ea7f81)
- The windows VM was assigned the IP Address 192.168.1.100 and the defualt gateway is the 192.168.1.1 address that pfSense is using
- We should be able to access our pfSense page
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/cca4ba11-d1c2-4eed-b4ad-773962296418)
- Sign in with the default credentials
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/40252eba-7da1-45e9-9be0-adbaf7c8c79c)
- Because we are in a private network in this example we'll be unchecking the box for "block private networks from entering via WAN
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/847da5da-2a6f-4386-8fc9-c0aab5f3fd21)
- After continuing with the configuration page we're now set up
![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/ec503f44-5e24-426a-a8fd-42e7a12d7f61)
- We can now view our WAN and LAN
  ![image](https://github.com/Brandencampos/PFSense-Setup/assets/62733055/12eda71b-8b36-4771-94e7-f9e0ee02b4fc)
