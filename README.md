# Packet Capture
Internet packet sniffing, analysis and injection
 <h1 align='center'>Overview</h1>
 <p>- Utilizing Wireshark and Burp Suite to capture, analyze or inject packets<br>
- With a Windows VM as the host machine, random searches are made using the internet browser available to generate traffic for capture.</p>

<h2 align='center'>Tools used</h2>
<p>Wireshark: A network analyzer to capture packets.<br>
Burp Suite: A web application security testing platform.</p>

<h2 align='center'>Intercepting packets</h2>
<p>Made several request to a Linux server, such as importing text files and pings, to generate traffic and analyze it using wireshark.<br>
  Analyzed the packets to identify any issues, such as high latency or poor connections  
</p>

<h2 align='center'>Packet Injection</h2>
<p>Using Burp Suite and its proxy, I was able to intercept a GET request from a webserver and edit it using repeater.</p>
