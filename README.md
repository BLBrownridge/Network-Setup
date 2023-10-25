<h1>Network Setup</h1>
<h2>Now that we're in the virtual machine (VM), we need to configure the networks for the Active Directory/Domain Controller (AD/DC) environment.</h2>

1. First, let's access our network settings by clicking on "Change Adapter Options."

2. You'll see two network connections, and our task is to identify which one is for the internet and which one is for our internal network.

3. To do this, right-click on either of the connections and select "Status," then click on "Details."

3A. You will notice that one of these connections will display your Internet Service Provider (ISP) name on the first line, along with an IP address likely in the format of 10.0.XX.XX. This is your external connection. The other connection will serve as the internal network for future users.

4. To distinguish between them, let's rename these connections. Right-click on each and select "Rename."

5. Now, let's assign an IP address to our internal Network Interface Card (NIC). Right-click on the internal NIC and choose "Properties."

5A. Double-click on the IPv4 option.
5B. Select "Use the following IP address."
5C. Enter a private IP address such as (192.168.0.1), Subnet Mask (255.255.255.0), Default Gateway (none), and DNS (127.0.0.1, the loopback address).
With this, the foundation of our network is set up. Let's proceed to configure the domain."





