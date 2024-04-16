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
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/b250bd8e-98b7-439f-b97f-37d28e9be72a)

Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in

```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/06fe8112-b975-406b-913d-8bc02fea3460)

Finding Hosting Company:
```
get further detail by using ip2location.com website.
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/21cf8284-daf8-4d8c-8b3d-e21089676ed2)

History of the website:

![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/863e589b-2953-4774-9b57-61971b9ca3b4)

Webserver Fingerprinting:
Netcat:
```
nc 172.17.52.118 80
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/728a90e6-aaa6-41d9-83d1-7e62a8b0b2fc)

nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/76ac44f9-659f-407d-9bd0-da836b13420d)

Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/28313eb7-a7b0-4a14-a810-4bdea5a9a12f)

httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/f3502b29-af1e-4984-9ad8-4014b4e077d2)

Tracing the Location:
TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/8ef84ef5-0624-4135-a0b4-5f15b59aa8f8)

UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/d3847857-dd72-49bb-974c-99866ad9ecfc)

ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
![image](https://github.com/gowriganeshns/InformationGathering/assets/118644502/36898d21-0a4b-4ea9-96c2-bd174c930993)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
