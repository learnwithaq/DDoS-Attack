# DDoS-Attack
DDoS Distributed Denial of Service Attack

# BOTNET - DDoS

Download the netbot from:
<pre>git clone https://github.com/skavngr/netbot.git</pre>

Windows 10 - Victim Web Server - Turn ON web server
<pre>python -m http.server 8080</pre>

Enter the following command in C2 Machine to check the response delay time in seconds<br>
<pre>sudo su</pre>
<pre>for (( ; ; )); do</pre>
for> <pre>curl -o /dev/null -s -w 'Response from victim server: %{time_total} seconds\n' http://192.168.100.121:8080</pre>
for> <pre>sleep 1</pre>
for> <pre>done;</pre>

Visit the website in C2 Machine - Kali Linux
<pre>victimip:8080</pre>
