---
layout: default
title: Copy over the latest image
---

1. Get the latest Yocto firmware image for the Intel® Edison.

    <div class="callout goto" markdown="1">
    1. On the USB key: <span class="icon folder">downloads</span> → <span class="icon folder">Mac/Windows/Linux</span> → <span class="icon folder">edison_media</span>
    2. Copy <span class="icon file">edison-iotdk-image-[version].zip</span> to your computer.
    </div>
      
    <div class="callout info" markdown="1">
    **Interested in finding out what's new with each firmware release?**
    
    Visit [Intel® Edison Boards and Compute Modules — Support Package Release Notes](http://www.intel.com/support/edison/sb/CS-035253.htm) to view the release notes PDF.
    </div>

2. Extract the contents of <span class="icon file">edison-image-[version].zip</span> to your hard drive.

3. Copy the **entire** contents of <span class="icon folder">edison-image-[version]</span> to the "**Edison**" drive that shows up after plugging the Intel® Edison to your computer. 

    Do **not** include the containing/parent edison-image-[version] folder; just the contents of the folder.

    ![Progress of copying files to Edison drive](images/windows-copying_files.jpg)

<div class="callout done" markdown="1">
Your "Edison" drive should now look similar to this:

![All edison-image files copied to the Edison drive](images/windows-edison_drive_with_files.jpg)
</div>