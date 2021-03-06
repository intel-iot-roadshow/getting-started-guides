---
layout: default
title: Ethernet over USB - Mac
---

<div id="toc" markdown="1">
* [Install HoRNDIS »](#install-horndis)
* [Configure network settings »](#configure-network-settings)
* [Share your computer's WiFi connection (optional) »](#share-your-computers-wifi-connection-optional)
</div>

# Set Up Ethernet over USB - Mac

When you are in a busy or restricted network environment, connect to the Intel® Edison using the device mode micro-USB cable and a virtual Ethernet connection known as "Ethernet over USB". Ethernet over USB uses the RNDIS protocol.

This document will guide you through obtaining an IP address for the Intel® Edison in order to program your board offline using the Intel® IoT Developer Kit IDEs.

<div class="callout danger" markdown="1">
**IMPORTANT NOTE: At this time, Ethernet over USB on Mac is not officially supported.**

HoRNDIS has been found to crash some computers running Mac OS. Please proceed with caution and only attempt to use Ethernet over USB if you are unable to use Wi-Fi.

If you have access to a Wi-Fi network, instead follow [Connect Your Intel Edison to Wi-Fi »](../.../wifi/index.html)
</div>

<!-- <div id="related-videos" class="callout video">
[Ethernet over USB - Intel Edison - Mac (preview)](https://drive.google.com/open?id=0B2ywC78pxngCSlJtbTNmNGhVVEU&authuser=0)
</div> -->

## Install HoRNDIS

<div class="tldr" markdown="1">
Install the HoRNDIS (pronounced "horrendous") kernel extension to use Ethernet over USB via the RNDIS protocol on your Mac. You must reboot your computer after installing HoRNDIS. 
</div>

<!-- ![Animated gif: installing HoRNDIS](images/install_horndis-animated.gif) -->

[View detailed instructions »](details-install_horndis.html){: .link-button .centered}


## Configure network settings

<div class="tldr" markdown="1">
Update your computer's Network configuration with a static IP address to use Ethernet over USB. 
</div>

<!-- [![Animated gif: configuring DHCP IP address in Mac Network settings](images/configure_mac_network-animated.gif)](details-configure_mac_network.html) -->

[View detailed instructions »](details-configure_mac_network.html){: .link-button .centered}


## Share your computer's WiFi connection (optional)

<div class="tldr" markdown="1">
Turn on Internet Sharing to cut down on Wi-Fi traffic in a crowded room. Sharing your computer's internet connection also means that you can log into networks that have HTML password pages and then share the connection with the Intel® Edison. Internet sharing is an optional step but is highly recommended if you are at a hackathon. 
</div>

[View detailed instructions »](details-share_internet.html){: .link-button .centered}


<div id="next-steps" class="callout done" markdown="1">
You should now have an Ethernet over USB connection set up between your computer and your Intel® Edison. 

[Continue to the next step in the START HERE guide »](../../../index.html#done-connectivity){: .link-button .centered}

For more info, see what you can do [once connected »](../shared/once_connected.html)
</div>