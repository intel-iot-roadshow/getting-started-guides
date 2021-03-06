---
layout: default
title: Ethernet over USB - Windows
---

<div id="toc" markdown="1">
* [Add static IPv4 address »](#add-static-ipv4-address)
* [Share your computer's WiFi connection (optional) »](#share-your-computers-wifi-connection-optional)
</div>

# Set Up Ethernet over USB - Windows

When you are in a busy or restricted network environment, connect to the Intel® Edison using the device mode micro-USB cable and a virtual Ethernet connection known as "Ethernet over USB". Ethernet over USB uses the RNDIS protocol.

This document will guide you through obtaining an IP address for the Intel® Edison in order to program your board offline using the Intel® IoT Developer Kit IDEs.

<!-- <div id="related-videos" class="callout video">
[Ethernet over USB - Intel Edison - Windows (preview)](https://drive.google.com/open?id=0B2ywC78pxngCUWJxZXJiYngycU0&authuser=0)
</div> -->

## Add static IPv4 address

<div class="tldr" markdown="1">
If you have the Intel® Edison Drivers installed, update your computer's Network Adapter configuration with a static IP address to use Ethernet over USB. 
</div>

[![Animated gif: adding static IPv4 address in Windows](){: .animated data-still="images/ipv4_windows-sampleframe.jpg" data-animated="images/ipv4_windows-animated.gif"}](details-ipv4_address.html)

[View detailed instructions »](details-ipv4_address.html){: .link-button .centered}


## Share your computer's WiFi connection (optional)

<div class="tldr" markdown="1">
Turn on Internet Connection Sharing (ICS) to cut down on Wi-Fi traffic in a crowded room. Sharing your computer's internet connection also means that you can log into networks that have HTML password pages and then share the connection with the Intel® Edison. Internet sharing is an optional step but is highly recommended if you are at a hackathon. 
</div>

[View detailed instructions »](details-share_internet.html){: .link-button .centered}


<div id="next-steps" class="callout done" markdown="1">
You should now have an Ethernet over USB connection set up between your computer and your Intel® Edison. 

[Continue to the next step in the START HERE guide »](../../../index.html#done-connectivity){: .link-button .centered}

For more info, see what you can do [once connected »](../shared/once_connected.html)
</div>