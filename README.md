# Malicious and Benign Webistes
Malicious webiste is of great concern due it is a problem to analyze one by one and to index each URL in a black list. Malicous website prediction model could help protect internet users from being attacked and getting security issues.

### Logistic Regression
A statistical model uses logistic function to model a binary dependent variable. Logistic regression could be used to predict the risk based on observed characteristics which were provided.

### Data Description
URL: it is the anonimous identification of the URL analyzed in the study

URL_LENGTH: it is the number of characters in the URL 

NUMBERSPECIALCHARACTERS: it is number of special characters identified in the URL, such as, “/”, “%”, “#”, “&”, “. “, “=”

CHARSET: it is a categorical value and its meaning is the character encoding standard (also called character set).

SERVER: it is a categorical value and its meaning is the operative system of the server got from the packet response.

CONTENT_LENGTH: it represents the content size of the HTTP header.

WHOIS_COUNTRY: it is a categorical variable, its values are the countries we got from the server response (specifically, our script used the API of Whois).

WHOIS_STATEPRO: it is a categorical variable, its values are the states we got from the server response (specifically, our script used the API of Whois).

WHOIS_REGDATE: Whois provides the server registration date, so, this variable has date values with format DD/MM/YYY HH:MM

WHOISUPDATEDDATE: Through the Whois we got the last update date from the server analyzed

TCPCONVERSATIONEXCHANGE: This variable is the number of TCP packets exchanged between the server and our honeypot client

DISTREMOTETCP_PORT: it is the number of the ports detected and different to TCP

REMOTE_IPS: this variable has the total number of IPs connected to the honeypot

APP_BYTES: this is the number of bytes transfered

SOURCEAPPPACKETS: packets sent from the honeypot to the server 

REMOTEAPPPACKETS: packets received from the server

APP_PACKETS: this is the total number of IP packets generated during the communication between the honeypot and the server

DNSQUERYTIMES: this is the number of DNS packets generated during the communication between the honeypot and the server

TYPE: this is a categorical variable, its values represent the type of web page analyzed, specifically, 1 is for malicious websites and 0 is for benign websites

### Dataset
Source: https://www.kaggle.com/xwolf12/malicious-and-benign-websites
