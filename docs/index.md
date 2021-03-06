---
layout: guide
title: Getting Started
---

![Arduino Expansion Board with Intel® Edison](images/arduino_expansion_board_with_edison.png)

# How to go from Zero to Blinking Light Hero

<!-- _Instructions for **Intel® Edison** installed on an **Arduino-compatible expansion board** using the Intel® IoT Developer Kit **(C/C++, JavaScript or Arduino development workflow)**_ -->


<div id="start" markdown="1">
## 1. Get Started with Intel® Edison

Find out what hardware is included with your Intel® IoT Developer Kit ("dev kit"), and review important assembly and cable hook up instructions.

[Assemble your Arduino expansion board »](assembly/arduino_expansion_board/index.html){: .link-button .centered}
</div>


<div id="done-assembly" markdown="1">
## 2. Set Up Your Computer

Use the Intel IoT DevKit 2.0 offline installer to install USB drivers and an IDE. Use the installer to also update the firmware to the latest version to get access to important features.

[Set up your computer with the offline installer »](offline_installer/index.html){: .link-button .centered}

<!--   <div class="link-button-container" markdown="1">
  [Windows 64-bit »](computer_setup/windows/index.html){: .link-button}
  [Mac»](computer_setup/mac/index.html){: .link-button}
  [Linux »](computer_setup/windows/index.html){: .link-button}
  </div> -->
  <div style="text-align:center;" markdown="1">
  **Offline installer not working?** **Have 32-bit Windows?**<br>
  Follow the [manual installation instructions »](manual-installation.html)
  </div>
</div>


<div id="done-computer-setup" markdown="1">
## 3. Shell Access

Gain command line access of your IoT board. Execute special Linux commands to configure your IoT board such as setting up Wi-Fi.

  <div class="link-button-container" markdown="1">
  <span class="link-button-container-title">Select your operating system:</span>
  [Windows »](shell_access/windows/index.html){: .link-button}
  [Mac »](shell_access/mac/index.html){: .link-button}
  [Linux »](shell_access/linux/index.html){: .link-button}
  </div>
</div>


<div id="done-shell-access" markdown="1">
## 4. Get Your IoT Board Online

Get your board online in order to turn your IoT board into a true "Internet of Things" device. You also need the IP address of your IoT board to program it using the dev kit IDEs.
  
Connect to the Intel® Edison using the device mode micro-USB cable and a virtual Ethernet connection known as "Ethernet over USB".

  <div class="link-button-container" markdown="1">
  <span class="link-button-container-title">Select your operating system:</span>
  [Windows »](connectivity/ethernet_over_usb/windows/index.html){: .link-button}
  [Linux »](connectivity/ethernet_over_usb/linux/index.html){: .link-button}
  </div>

  <div style="text-align:center;" markdown="1">
   **Using Mac OSX?** **Have a dependable Wi-Fi connection?**<br>
   _At this time, Ethernet over USB on Mac is not officially supported._<br>
  [Connect Your Intel Edison to Wi-Fi »](connectivity/wifi/index.html)
  </div>
</div>


<div id="done-connectivity" markdown="1">
## 5. Build a sample project

Get the on-board LED blinking on your Intel Edison.

  <div class="link-button-container" markdown="1">
  <span class="link-button-container-title">Select your IDE:</span>
  [XDK »](ide_setup/xdk/sample_project/index.html){: .link-button}
  [Eclipse »](ide_setup/eclipse/index-create_project.html){: .link-button}
  [Arduino »](ide_setup/arduino/details-create_project.html){: .link-button}
  </div>
</div>


<div id="done-ide" markdown="1">
## 6. Get Familiar with the Grove Starter Kit

Install the Grove Base Shield and learn how to connect Grove components.

[Read Grove Starter Kit Intro »](sensor_examples/grove_starter_kit/index.html){: .link-button .centered}

</div>

<div id="done-grove-intro" markdown="1">
## 7. Sensor Tutorials

See code samples for your programming language and IDE.

  <div class="link-button-container" markdown="1">
  [JavaScript / XDK »](sensor_examples/grove_starter_kit/javascript/index.html){: .link-button}
  <!-- [C++ »](https://software.intel.com/en-us/articles/internet-of-things-using-mraa-to-abstract-platform-io-capabilities#_Toc4) -->
  [C++ / Eclipse »](https://software.intel.com/en-us/working-with-sensors-in-eclipse){: .link-button}
  [Arduino »](sensor_examples/grove_starter_kit/arduino/index.html){: .link-button}
  </div>

  <div style="text-align:center;" markdown="1">
  **Need more examples?**<br>
  Search for your component on [software.intel.com/en-us/iot/sensors](http://software.intel.com/en-us/iot/sensors).<br>
  View app examples on [github.com/intel-iot-devkit/how-to-code-samples](https://github.com/intel-iot-devkit/how-to-code-samples).
  </div>
</div>



<div id="done-sensors" markdown="1">
## 7. Start Hacking!

  <div class="callout done" style="margin-top: 1em" markdown="1">
  **You have completed the set up guide!** Now go make your own creation!

  Take pictures along the way. Create your own guide and post them to [Instructables.com](http://instructables.com/id/intel).
  </div>
</div>


<div class="callout troubleshooting" markdown="1">
**Running into issues?**
Search for answers and post your questions to the [Intel® Edison Support Community](https://communities.intel.com/community/tech/edison).
</div>

## Additional Resources

* [Intel® Edison Product Brief](http://www.intel.com/support/edison/sb/CS-035277.htm) (Specs)
* [Intel® Edison Arduino Expansion Board Hardware Guide](http://www.intel.com/support/edison/sb/CS-035275.htm)
  * For pinout listing, see page 7
* [Intel® Edison Mini Breakout Board Hardware Guide](http://www.intel.com/support/edison/sb/CS-035252.htm)
  * For pinout listing, see page 9 
* [Yocto Project: Foundation for the Internet of Things](https://www.youtube.com/watch?v=ztsnQ3p59jA&list=PLg-UKERBljNw254jnyMNZiu8yqF8pPq0m&index=24) (Introduction to Yocto video)
* [Intel® IoT Developer Kit Cloud-based Analytics User Guide](https://software.intel.com/en-us/intel-iot-developer-kit-cloud-based-analytics-user-guide) 
