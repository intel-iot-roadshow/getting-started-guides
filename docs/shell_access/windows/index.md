---
layout: default
title: Shell Access - Windows
---

<div id="toc" markdown="1">
* [Download a terminal client (PuTTY) »](#download-a-terminal-client-putty)
* [Identify the serial COM port »](#identify-the-serial-com-port)
* [Establish a serial connection »](#establish-a-serial-connection)
* [Configure a password to enable SSH](#configure-a-password-to-enable-ssh)
</div>

# Shell Access - Windows

![computer icon with command prompt](../images/icon-computer_shell.png)

If you need to configure your IoT board, you will need to remotely connect to the Intel® Edison or Intel® Galileo. Once connected to your Intel® IoT board, you have access to the Linux-based Yocto operating system running on the board. 

You can then execute special Linux commands such: changing the hostname and password, setting up Wi-Fi, or flashing new firmware.


## Download a terminal client (PuTTY)

<div class="tldr" markdown="1">
Windows does not come with a built-in terminal emulator so download and use the [PuTTY](http://www.putty.org/) client. 
</div>

[![Animated gif: downloading and installing PuTTY](){: .animated data-still="images/install_putty-firstframe.jpg" data-animated="images/install_putty-animated.gif"}](details-putty.html)

[View detailed instructions »](details-putty.html){: .link-button .centered}


## Identify the serial COM port

<div class="tldr" markdown="1">
Use Device Manager to find the COM port number for the "**USB Serial Port**" connection. You will need the COM # to configure PuTTY in <span class="icon bookmark">Establish a serial connection</span> next. 
</div>

[![Animated gif: identifying the serial COM port](){: .animated data-still="images/identify_com_port-sampleframe.jpg" data-animated="images/identify_com_port-animated.gif"}](details-identify_com_port.html)

[View detailed instructions »](details-identify_com_port.html){: .link-button .centered}


## Establish a serial connection

<div class="tldr" markdown="1">
Use PuTTY to establish a **serial** connection to the IoT board using the COM # you noted in the previous <span class="icon bookmark">Identify the serial COM port</span> section and the baud rate **115200**. 
</div>

[![Animated gif: logging into the IoT board via a PuTTY serial connection](){: .animated data-still="images/putty_serial_connection-sampleframe.jpg" data-animated="images/putty_serial_connection-animated.gif"}](details-putty_serial_connection.html)

[View detailed instructions »](details-putty_serial_connection.html){: .link-button .centered}


## Configure a password to enable SSH 

<div class="tldr" markdown="1">
You must enable SSH in order to work with the Intel® XDK and Eclipse over Wi-Fi. Setting a password on your Intel® Edison by running `configure_edison --password` will enable SSH.
</div>

![screen shot of password setup](images/configure_edison_password.png)

[View detailed instructions »](details-configure_password.html){: .link-button .centered}


<div id="next-steps" class="callout done" markdown="1">
You are now logged into your IoT board and can run shell commands.

[Continue to the next step in the START HERE guide »](../../index.html#done-shell-access){: .link-button .centered}
</div>
