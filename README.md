# Ethical_ex-02_InformationGatherirng
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
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
## OUTPUT:
![Screenshot 2025-03-07 133027](https://github.com/user-attachments/assets/a701278f-d23f-4b34-9258-5042ca93e46a)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of .

```
 ping -w 20 saveetha.ac.in
```
### Output: 
<img width="398" alt="image" src="https://github.com/user-attachments/assets/04fbf9fe-16f5-48cb-964d-0e2baa80b7cb" />

## Finding Hosting Company
get further detail by using ip2location.com website.
## Output:
![Screenshot 2025-03-10 105148](https://github.com/user-attachments/assets/c3b9e7a5-75dd-4cef-a48b-d8e3ab5da4bf)
## History of the website:
## Output:
![Screenshot 2025-03-07 134157](https://github.com/user-attachments/assets/a212c033-d354-4a47-adbf-c1eb4a0c33f1)

## Webserver Fingerprinting:
## Netcat:
```
nc example.com 80
```
### Output:
<img width="437" alt="image" src="https://github.com/user-attachments/assets/e8836f88-f0f1-4ba4-a068-dab3758c816d" />

## nmap:

```
nmap -V -Pn 192.160.1.100 
```
### Output:
![Screenshot 2025-03-07 143445](https://github.com/user-attachments/assets/337ac9dd-3c30-46ed-be63-3de84c01b900)

## whatweb:
```
whatweb infosys.com
whatweb zoho.com
```
### Output:
![Screenshot 2025-03-10 113342](https://github.com/user-attachments/assets/a6a99a80-a6ab-40b2-a5d7-2f39229e3934)

## Httprint:
```
httprint -h 172.17.62.86 -s
```
### Output:
![Screenshot 2025-03-14 142523](https://github.com/user-attachments/assets/18345e2b-2a2d-422f-8099-1ae8c24d2914)

![Screenshot 2025-03-14 142450](https://github.com/user-attachments/assets/f829810a-239b-4dbd-b789-f43e6be4794e)




## Tracing the Location
### TCP Traceroute:
```
sudo traceroute -T saveetha.ac.in
```
### Output:
![Screenshot 2025-03-10 115433](https://github.com/user-attachments/assets/7144f56a-a361-43b6-ae8e-cb121c6cc956)

```
traceroute -U saveetha.ac.in
```
### Output:
<img width="470" alt="image" src="https://github.com/user-attachments/assets/92fd6d7f-3e45-4599-855d-09998383aa07" />

```
traceroute saveetha.ac.in

```
### Output:
<img width="471" alt="image" src="https://github.com/user-attachments/assets/33334fe2-7a69-47fc-b529-53d5c03026eb" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
