<h1>Network Setup</h1>
<h2>Now that we're in the virtual machine (VM), we need to configure the networks for the Active Directory/Domain Controller (AD/DC) environment.</h2>

1. First, let's access our network settings by clicking on "Change Adapter Options."
<img src="https://i.imgur.com/zbSrFEj.png" height="80%" width="80%"/>

2. You'll see two network connections, and our task is to identify which one is for the internet and which one is for our internal network.
<img src="" height="80%" width="80%"/>

3. To do this, right-click on either of the connections and select "Status," then click on "Details."
<img src="https://i.imgur.com/EuE3GZI.png" height="80%" width="80%"/>

3A. You will notice that one of these connections will display your Internet Service Provider (ISP) name on the first line, along with an IP address likely in the format of 10.0.XX.XX. This is your external connection. The other connection will serve as the internal network for future users.
<img src="https://i.imgur.com/vFMbX3z.png" height="80%" width="80%"/>

4. To distinguish between them, let's rename these connections. Right-click on each and select "Rename."
<img src="https://i.imgur.com/FFukFCi.png" height="80%" width="80%"/>

5. Now, let's assign an IP address to our internal Network Interface Card (NIC). Right-click on the internal NIC and choose "Properties."
<img src="" height="80%" width="80%"/>

5A. Double-click on the IPv4 option.
<img src="https://i.imgur.com/JqniNH0.png" height="80%" width="80%"/>

5B. Select "Use the following IP address."
<img src="https://i.imgur.com/fvXzhDc.png" height="80%" width="80%"/>

5C. Enter a private IP address such as (192.168.0.1), Subnet Mask (255.255.255.0), Default Gateway (none), and DNS (127.0.0.1, the loopback address).
<img src="https://i.imgur.com/YJT7sTU.png" height="80%" width="80%"/>

<h3>With this, the foundation of our network is set up. Let's proceed to configure the domain.</h3>





