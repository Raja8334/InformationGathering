# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/e9b073d6-66aa-49d4-9b2a-3a269017dbaf)
## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
# OUTPUT
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/a9c50c36-56ff-4c87-aaea-04910620e7b5)
## Finding Hosting Company
get further detail by using ip2location.com website.
# OUTPUT
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/18301b4e-62b4-48d1-9361-c9f0d0385ecb)
History of the website:
# OUTPUT:
https://web.archive.org/
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/254db008-bec4-4530-8ed8-a56c250e628e)
```
nc 172.17.52.118 80
```
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/3f8d9521-2d8e-47de-87fa-be275243c995)
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/9489eded-e04b-4b21-a386-518d262ad0a1)
# Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
# OUTPUT
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/5fed826f-3935-40c9-8cb6-aa926800c4ff)
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/fcc79539-a1f9-493f-ad2b-7abedfeb2203)
# httprint
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
# OUTPUT
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/60d425cc-5f76-41f7-8634-261b13e42b66)
# Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
# OUTPUT
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/ab14b44a-9bcc-489b-9303-409f0db9ef99)
# UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
# OUTPUT
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/70450572-f131-4a5b-bff5-1d717c216b92)
# ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
# OUTPUT
![image](https://github.com/Raja8334/InformationGathering/assets/120719634/390cf1ef-3f8d-478c-a699-1e82928b0e21)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
