<div class="cPost_contentWrap">
<div data-role="commentContent" class="ipsType_normal ipsType_richText ipsPadding_bottom ipsContained" data-controller="core.front.core.lightboxedImages" id="ips_uid_8953_2">
<p style="background-color:#24262b;color:#ababab;font-size:14px;text-align:center;">
<a data-fileid="undefined" href="https://sdn.dreambot.org/scripts/?q=botbuddy" rel="external nofollow noopener" style="background-color:transparent;" title="Enlarge image" target="_blank" class="ipsAttachLink_block" data-loaded="true"><img alt="spacer.png" data-ratio="100.00" height="200" style="border:none;vertical-align:middle;height:auto;" width="200" data-src="https://i.imgur.com/J4vxXel.png" src="https://i.imgur.com/J4vxXel.png" class="ipsImage_thumbnailed" data-loaded="true"></a>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;text-align:center;">
<span style="font-size:20px;"><a href="https://store.botbuddy.net" rel="external nofollow noopener" target="_blank">BotBuddy.net</a></span>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;text-align:center;">
<span style="font-size:20px;">BotBuddy GPSeller is a script designed to automate gold sales. It manages real-time order processing through Sellix webhooks to allow fast, secure, unattended gold sale transactions.</span>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;text-align:center;">
<span style="font-size:20px;"><strong><a href="https://sdn.dreambot.org/scripts?q=botbuddy" rel="external nofollow noopener" target="_blank">Make money while you sleep! Click here to add the script via DreamBot SDN</a></strong></span>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;text-align:center;">
<span style="font-size:20px;">Any questions or further setup assistance needed? Post below or&nbsp;<a href="http://discord.gg/oldschoolrs" rel="external nofollow noopener" style="background-color:transparent;" target="_blank">join our discord!</a></span>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
<strong><span style="font-size:20px;">Features:</span></strong>
</p>
<ul style="background-color:#24262b;color:#ababab;font-size:14px;">
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Webhook endpoint server able to receive&nbsp;POST requests from remote servers
</li>
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Signature verification to ensure POST requests are processed only from your intended remote server
</li>
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Order queue with concurrent trade support&nbsp;(<strong>A</strong>&nbsp;bought&nbsp;GP 5 minutes ago but hasn't&nbsp;shown&nbsp;up yet. This&nbsp;won't prevent<span>&nbsp;</span><strong>B</strong><span>&nbsp;</span>from receiving the GP they&nbsp;purchased after<span>&nbsp;</span><strong>A</strong>.)
</li>
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Cubic Bezier curve mouse algorithm for anti-pattern
</li>
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Anti-pull&nbsp;to prevent users from pulling your bot too far&nbsp;from its starting tile
</li>
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Any starting location&nbsp;supported, wherever the script starts is where it will stay; Provide the world and location to your customers in their invoice so they will know where to meet
</li>
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Configurable webhook endpoint port and trade world via config.json
</li>
<li style="background-color:#24262b;color:#ababab;font-size:14px;">
Order expiry after 10 minutes
</li>
</ul>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
<strong><span style="font-size:20px;">Requirements:</span></strong>
</p>
<ul style="background-color:#24262b;color:#ababab;font-size:14px;">
<li>
Free Sellix storefront&nbsp;and API key from Sellix Settings &gt; General &gt; "Webhook Secret"
</li>
<li>
You must always ensure your&nbsp;inventory contains your&nbsp;current stock of GP (Adjust stock on Sellix product listing, multiply by 1,000,000 so 100M GP in stock is 100 on Sellix).&nbsp;<span style="font-size:18px;"><em><strong>The script will never open your bank.</strong> </em></span>
</li>
<li>
Open port&nbsp;for webhook endpoint
</li>
</ul>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
<strong><span style="font-size:20px;">Instructions:</span></strong>
</p>
<ul style="background-color:#24262b;color:#ababab;font-size:14px;">
<li>
Start script initially to generate config file, the GUI will only appear if the config file does not exist in /DreamBot/Scripts/BBGPSeller/.&nbsp;Modify as needed&nbsp;to contain your desired port, trade world, and Sellix API key.<br>
<a href="https://dreambot.org/forums/uploads/monthly_2024_02/image.png.7c30a77669ccce9dbed5e055fbe8d56e.png" title="Enlarge image" data-fileid="7692" data-wrappedlink="" data-ipslightbox="" data-ipslightbox-group="undefined"><img alt="image.png.7c30a77669ccce9dbed5e055fbe8d56e.png" class="ipsImage ipsImage_thumbnailed" data-fileid="7692" data-ratio="65.89" style="height:auto;" width="302" data-src="https://dreambot.org/forums/uploads/monthly_2024_02/image.png.7c30a77669ccce9dbed5e055fbe8d56e.png" src="https://dreambot.org/forums/uploads/monthly_2024_02/image.png.7c30a77669ccce9dbed5e055fbe8d56e.png" data-loaded="true"></a>
</li>
<li>
Ensure the port specified in your config is open on both your OS firewall and your router. To test, run the script and check the port with<span>&nbsp;</span><a href="https://canyouseeme.org/" rel="external nofollow noopener" style="background-color:transparent;" target="_blank">https://canyouseeme.org</a>&nbsp;to confirm the port is open. The script must be running for this&nbsp;site to see the port.
</li>
<li>
Configure your listing in Sellix with the below information in the "Additional Details" and "Webhooks Endpoints"&nbsp;section at the bottom of the product info. (<em><strong>http://YOURPUBLICIP:420/webhook&nbsp;</strong></em><strong>needs to be changed&nbsp;to match your own public IP and your own opened port)</strong>
</li>
</ul>
<p style="text-align:center;">
<a href="https://dreambot.org/forums/uploads/monthly_2024_02/image.png.ff3dc203986d0c252a043f60fa4c1395.png" title="Enlarge image" data-fileid="7708" data-wrappedlink="" data-ipslightbox="" data-ipslightbox-group="undefined"><img alt="image.png.ff3dc203986d0c252a043f60fa4c1395.png" class="ipsImage ipsImage_thumbnailed" data-fileid="7708" data-ratio="23.92" style="height:auto;" width="949" data-src="https://dreambot.org/forums/uploads/monthly_2024_02/image.png.ff3dc203986d0c252a043f60fa4c1395.png" src="https://dreambot.org/forums/uploads/monthly_2024_02/image.png.ff3dc203986d0c252a043f60fa4c1395.png" data-loaded="true"></a>
</p>
<p style="text-align:center;">
<a href="https://i.imgur.com/BJnyGRR.png" title="Enlarge image" data-fileid="undefined" data-wrappedlink="" data-ipslightbox="" data-ipslightbox-group="undefined"><img alt="BJnyGRR.png" data-ratio="100.28" style="height:auto;" width="724" data-src="https://i.imgur.com/BJnyGRR.png" src="https://dreambot.org/forums/applications/core/interface/js/spacer.png" class="ipsImage_thumbnailed"></a>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
<strong><span style="font-size:20px;">Future Plans:</span></strong>
</p>
<ul style="background-color:#24262b;color:#ababab;font-size:14px;">
<li>
Script paint containing GP sold, sales count, avg GP per sale, etc.
</li>
<li>
Auto-muling to prevent "master mule" from being customer facing
</li>
<li>
Support for other storefronts
</li>
<li>
Integration with CloudFlare Tunnel to remove the need to portforward
</li>
<li>
Support for specific items (not just GP) ?
</li>
</ul>
<p style="text-align:center;">
<a href="https://i.imgur.com/US0aGJW.png" title="Enlarge image" data-fileid="undefined" data-wrappedlink="" data-ipslightbox="" data-ipslightbox-group="undefined"><img alt="US0aGJW.png" data-ratio="53.48" style="height:auto;" width="690" data-src="https://i.imgur.com/US0aGJW.png" src="https://dreambot.org/forums/applications/core/interface/js/spacer.png" class="ipsImage_thumbnailed"></a>
</p>
<p style="text-align:center;">
&nbsp;
</p>
<p style="text-align:center;">
<a href="https://developers.sellix.io/#webhooks" rel="external nofollow noopener" target="_blank">https://developers.sellix.io/#webhooks</a>
</p>
<p style="text-align:center;">
Sellix claims to only send production webhooks to SSL hosts, but this isn't true at the moment. I will post an update whenever this stops being the case. <a contenteditable="false" data-ipshover="" data-ipshover-target="https://dreambot.org/forums/index.php?/profile/260781-camalcase/&amp;do=hovercard" data-mentionid="260781" href="https://dreambot.org/forums/index.php?/profile/260781-camalcase/" rel="">@camalToe</a>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
<strong><span style="font-size:20px;">Safety Warning:</span></strong>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
Opening ports to the public network can expose your computer to potential security risks. It's vital to proceed with caution and understand the implications of making your services accessible over the internet. When you open a port, you create a pathway for external traffic to enter your network, which could be exploited by malicious actors to gain unauthorized access or carry out attacks against your system. To mitigate these risks, ensure you:
</p>
<ul>
<li style="background-color:rgb(36,38,43);color:rgb(171,171,171);font-size:14px;">
Use strong, unique passwords for all services and devices.
</li>
<li style="background-color:rgb(36,38,43);color:rgb(171,171,171);font-size:14px;">
Regularly update your software to patch any known vulnerabilities.
</li>
<li style="background-color:rgb(36,38,43);color:rgb(171,171,171);font-size:14px;">
Limit port exposure by only opening the ports necessary for your bot to function and closing them when not in use.
</li>
<li style="background-color:rgb(36,38,43);color:rgb(171,171,171);font-size:14px;">
Consider implementing additional security measures, such as firewalls and intrusion detection systems, to monitor and control incoming traffic.
</li>
</ul>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
<strong><span style="font-size:20px;">Understanding Port Ranges and Safe Practices for Port Forwarding:</span></strong>
</p>
<p style="background-color:#24262b;color:#ababab;font-size:14px;">
When configuring port forwarding for the GPSeller script, it's essential to choose an appropriate port number that minimizes security risks while ensuring reliable functionality. Ports are divided into three ranges: Well-Known Ports (0-1023), Registered Ports (1024-49151), and Dynamic/Private Ports (49152-65535).
</p>
<ul>
<li>
Well-Known Ports (0-1023): Reserved for system or well-known services (e.g., HTTP on port 80). Avoid using these ports to prevent conflicts with standard services.
</li>
<li>
Registered Ports (1024-49151): Typically used by user applications or non-privileged services. It's safer and more common to use a port within this range for your script.
</li>
<li>
Dynamic/Private Ports (49152-65535): Generally used for client-side communications or ephemeral ports that applications use for temporary communications. These can be used but are less common for services that need a consistent port.
</li>
</ul>
<p>
When choosing a port for the GPSeller script, select one within the Registered Ports range (1024-49151) that does not conflict with any known services you run. This reduces the chance of security risks and service conflicts.
</p>
<p style="border:0px solid #e3e3e3;">
<strong><span style="font-size:20px;">Port Forwarding Guide:</span></strong>
</p>
<p style="border:0px solid #e3e3e3;">
Port forwarding is a process that allows remote computers on the internet to connect to a specific computer or service within a private local-area network (LAN). Here's a simplified guide on how to open ports, but keep in mind that the exact steps may vary depending on your router's make and model:
</p>
<ol>
<li style="border:0px solid #e3e3e3;">
<p style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Access Your Router:</strong> Open your web browser and enter your router's IP address (commonly <code style="border:0px solid #e3e3e3;font-size:0.875em;">192.168.1.1</code> or <code style="border:0px solid #e3e3e3;font-size:0.875em;">192.168.0.1</code>) in the address bar. You'll need to log in with your router's credentials (often found on the router itself or in its manual).
</p>
</li>
<li style="border:0px solid #e3e3e3;">
<p style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Find Port Forwarding Settings:</strong> Look for a section labeled "Port Forwarding," "Apps and Gaming," or something similar. This can usually be found under the "Advanced" or "Network" settings.
</p>
</li>
<li style="border:0px solid #e3e3e3;">
<p style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Create a New Port Forwarding Rule:</strong> Enter the necessary information for your script:
</p>
<ul style="border:0px solid #e3e3e3;padding:0px;">
<li style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Service Name:</strong> Give your rule a name, like <code style="border:0px solid #e3e3e3;font-size:0.875em;">GPSeller</code>.
</li>
<li style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Port Range:</strong> Enter the port number you want to open (specified in your <code style="border:0px solid #e3e3e3;font-size:0.875em;">config.json</code>). If required, enter the same number for both the starting and ending points.
</li>
<li style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Local IP:</strong> Enter the IP address of the computer running the GPSeller script. You can find this by running <code style="border:0px solid #e3e3e3;font-size:0.875em;">ipconfig</code> (Windows) or <code style="border:0px solid #e3e3e3;font-size:0.875em;">ifconfig</code> (Linux/Mac) in the command line.
</li>
<li style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Protocol:</strong> Choose <code style="border:0px solid #e3e3e3;font-size:0.875em;">TCP</code>, as it is typically used for web server communications.
</li>
<li style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Enable the Rule:</strong> Make sure your new rule is enabled, then save or apply your changes.
</li>
</ul>
</li>
<li style="border:0px solid #e3e3e3;">
<p style="border:0px solid #e3e3e3;">
<strong style="border:0px solid #e3e3e3;">Test Your Setup:</strong> Use a service like <a href="https://canyouseeme.org/" rel="external nofollow noopener" target="_blank">https://canyouseeme.org</a> to confirm that your port is open and reachable from the external internet. Remember, the GPSeller script needs to be running for the port to appear open.
</p>
</li>
</ol>
<p style="border:0px solid #e3e3e3;">
For a more tailored guide, including illustrations and router-specific instructions, you might refer to resources like <a href="https://portforward.com/router.htm" rel="external nofollow noopener" target="_blank">PortForward's Router Guide</a>. This website provides step-by-step instructions for a wide range of router models and services.
</p>
