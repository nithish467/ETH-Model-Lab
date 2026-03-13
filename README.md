# ETH-Model-Lab

# InformationGathering
Information Gathering Techiques

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

http://www.whois.com/whois website

## OUTPUT:

<img width="1919" height="929" alt="image" src="https://github.com/user-attachments/assets/76df4227-73bf-4f94-b4dd-de86cc7da06d" />



## Finding IP address:
ping.sony.com
##output 

<img width="696" height="131" alt="image" src="https://github.com/user-attachments/assets/8884399b-d5a0-4972-bd81-2e417cbe26b0" />




## Finding Hosting Company
get further detail by using ip2location.com website.
## output
<img width="1232" height="886" alt="image" src="https://github.com/user-attachments/assets/688016b9-7dbe-43c1-b09b-d21afae8a27c" />



## History of the website:
## output
https://web.archive.org/
<img width="1919" height="824" alt="image" src="https://github.com/user-attachments/assets/08d8c8e2-26c9-4f5d-bac5-12a415c289a4" />

<img width="1919" height="928" alt="image" src="https://github.com/user-attachments/assets/d0b6a4d4-3c13-42cd-8420-0a5f10fb0080" />


# Webserver Fingerprinting:

## Netcat:
sudo nc sony.com 80 443

<img width="681" height="125" alt="image" src="https://github.com/user-attachments/assets/219c8455-b513-4d0d-a6cc-1ae7ad402c65" />




## nmap:
### output
<img width="760" height="239" alt="image" src="https://github.com/user-attachments/assets/1fa2d65d-8d8a-45fb-819e-5c730233eb16" />


## Whatweb
### output
<img width="945" height="182" alt="image" src="https://github.com/user-attachments/assets/18726752-9758-4dc7-9210-061f371be1ba" />


## httprint
### output

<img width="924" height="832" alt="image" src="https://github.com/user-attachments/assets/ee60ea68-d3e0-4ee6-8155-47b931df7196" />



# Tracing the Location
TCP Traceroute:
sudo traceroute -T sony.com
## output
<img width="840" height="116" alt="image" src="https://github.com/user-attachments/assets/987792af-35d1-4125-b04d-7866e9882e50" />


## UDP Traceroute:
sudo traceroute -U sony.com
## output
<img width="667" height="614" alt="image" src="https://github.com/user-attachments/assets/e8180819-cd8f-48a4-b6fc-4f7c8076d0ba" />



## ICMP Traceroute:
sudo traceroute sony.com
## output

<img width="712" height="624" alt="image" src="https://github.com/user-attachments/assets/10195612-9d63-433b-ae76-c3f8c9489bc1" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
