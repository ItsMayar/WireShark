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
The analysis using Wireshark revealed significant security vulnerabilities in FTP server communications. When connected to an FTP server, critical information such as usernames and passwords are are not encrypted, making them easily accessible for interception. Additionally, we can also track the IP address that the host is connected to, and the specific FTP commands executed, such as ls (list directory contents) and cd (change directory).
<br />
<br />
<b>HTTP/1.1</b>
<br />
It has the capability for client-server connections, allowing multiple requests to be sent sequentially within the same packet without waiting for individual responses from the server. This approach enhances communication efficiency by reducing latency, particularly during request revalidation. However, the server must return responses in the exact order in which the requests were received, ensuring the integrity and consistency of the data exchange.
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
<img src="https://i.imgur.com/Bu9DN87.png" height="80%" width="80%" alt="Wireshark"/>
<br />
In HTTPS, the communication protocol is encrypted using Transport Layer Security (TLS) or, formerly, Secure Sockets Layer (SSL)
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
