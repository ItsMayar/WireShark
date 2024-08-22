<h1>Computer Security using Wireshark</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Conducted a network security analysis project using Wireshark, a powerful packet sniffing tool, to capture and analyze data communications across FTP, HTTP, and HTTPS protocols. The project focused on intercepting and examining transmitted messages and credentials, such as usernames and passwords, to evaluate the security implications of these protocols. The analysis highlighted the vulnerabilities in unencrypted protocols (FTP, HTTP) and demonstrated the enhanced security provided by HTTPS through encryption, reinforcing the critical need for secure communication channels in protecting sensitive information.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
<b>Ftp Address: ftp.vim.org</b>
<br />
- Login: Anonymous
</br>
- Password: MayaristheProjectLeader(Mayar is the Project Leader)
<br/>
<img src="https://i.imgur.com/jdViqOY.png" height="80%" width="80%" alt="Wireshark"/>
<br />
<br/>
<img src="https://i.imgur.com/cS2Edfk.png" height="80%" width="80%" alt="Wireshark"/>
<br />
<br />
<img src="https://i.imgur.com/niLWPVf.png" height="80%" width="80%" alt="Wireshark"/>
<br />
<br />
<img src="https://i.imgur.com/drfpD1J.png" height="80%" width="80%" alt="Wireshark"/>
<br />
<br />
<img src="https://i.imgur.com/zmpkbJa.png height="80%" width="80%" alt="Wireshark"/>
<br />
<br />
Wireshark analysis exposed significant security vulnerabilities in FTP server communications, where critical information such as usernames, passwords, and the IP address of the connected host are not encrypted, making them vulnerable to interception. FTP commands like ls and cd are also easily captured.
<br />
<br />
<b>HTTP/1.1</b>
<br />
It supports sending multiple requests in a single packet without waiting for server responses, reducing latency and enhancing efficiency. However, the server must return responses in the order received to ensure data integrity.
<br />
<br />
<img src="https://i.imgur.com/OX5Sxff.png" height="80%" width="80%" alt="Wireshark"/>
<br />
<b> Username:‘MAYAR-MMU’ and the Password:‘123MM’. </b>
<br />
Username and password can be seen and therefore it is not secure.
<br />
<br />
<b>HTTPS</b>
<br />
It is much more secure than HTTP. When you connect to an HTTPS-secured server—secure sites like your bank's will automatically redirect you to HTTPS,your web browser checks the website's security certificate and verifies it was issued by a legitimate certificate authority
<br />
<br />
<img src="https://i.imgur.com/Bu9DN87.png" height="80%" width="80%" alt="Wireshark"/>
<br />
In HTTPS, the communication protocol is encrypted using Transport Layer Security (TLS) or, formerly, Secure Sockets Layer (SSL).
<br />



</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
