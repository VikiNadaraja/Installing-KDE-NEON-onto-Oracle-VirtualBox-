## Installing KDE Neon onto Oracle VirtualBox

## Browse for Oracle VirtualBox in any browser and install the software :
- Advisable to download VirtualBox 7.0 (https://www.virtualbox.org/wiki/Download_Old_Builds)
- Once download complete, run the program.
- After finish installation the Oracle Virtual Box home page will be displayed.
- If there’s already any Virtual Machine running, it should show on the left panel as below, if not it should be just empty.

## Browse for KDE Neon in any browser and install the software : 
- Install User Edition (https://neon.kde.org/download)
- Once downloaded, no need to run the file since it’s a disc image file.

## Next open up Oracle VirtualBox : 
- Click on New to add a new Virtual Machine. It will prompt a window to enter installation details 
- Give your Virtual Machine a suitable name (eg: KDE_NEON)
- In the ISO Image click the dropdown and Select the KDE Neon ISO file from the downloads earlier.
- It should auto fill the Type and Version automatically (Linux and Ubuntu 64-bit)
- Click Next and it should prompt a window for hardware setup
- It is advisable to make Base Memory 4096MB for a smoother experience.
- For Processors by Default the value should be 1 but it is advisable to change it to 2 for faster speed and performance.
- Click Next and it should prompt a new window for Virtual Hard Disk setup.
- By Default the Disk Size should be 20GB but it is advisable to increase the storage to minimum of 25GB to avoid any lagging.
- Click Next and it should prompt a new installation Summary window.
- Click Finish to finish setup.
- You should see a Powered Off Virtual Machine on the left panel of your VirtualBox and on the right side you should see the details of the Virtual Machine and a Preview.
- Click on Settings to install the KDE Neon to the Virtual Machine
- It should prompt a new window and click on Display maximize the Video Memory to 128MB for smooth display.
- Click OK.
- Next Click on Storage.
- On the right hand side at the Attributes → Optical Drive → Blue Disc → Dropdown (Pick the ISO file)
- Click OK.
- Click Start and it should prompt your newly created Virtual Machine with KDE Neon OS.
  
## KDE Neon Installation :
- Click on the Purple Down Arrow button to start installation.
- It should prompt KDE Neon Installer
- Continue clicking Next until you reach Partitions 
- In Partitions choose Erase Disk option to avoid manually partitioning the disk yourself.
- Click Next and it should prompt Users settings.
- Type in your name and password (a simple password is enough) 
- Click Install
- It should take about a few minutes to finish installing.
- Once finish installation it should prompt to Restart your Virtual Machine.
- Click Done to restart.
- After restart you should see a login window.
- Key in the password you’ve created earlier in the users settings to login into your machine.

## Configuration : Personalizing KDE Environment
- Right-click on the Panel at the bottom
- Click on Show Panel Configuration to go into Edit Mode
- Once in Edit Mode, click on Add or Manage Widgets
- It should prompt a side panel and you can choose from the widgets there to add or drag and drop
- Example : Drag and Drop Application Launcher on Desktop
- Once click the Application Launcher on the Desktop it should display available apps in the device

## Adding Files/Apps to Favorites
- Go to All Applications in Application Launcher and Select and right-click any apps to add it to favorites
- Then at Application Launcher go to Favorites to view

## Time Format : Changing the date and time format
- At the bottom right corner, right-click at the date and time 
- Select Adjust Date and Time
- It should prompt Date & Time - System Settings 
- From there you can set the time zone, date and time accordingly

## Shortcut for Toggle Overview :
- Go to Desktop Effects → Window Management → Overview → Configure → Select Toggle Overview
- Once selected, click on Custom to set Super Key or select Default if the Global value is set to Meta+W

## Application Installation and Testing : 
- Go to Firefox and search for WPS download (https://www.wps.com/office/linux/)
- Pick Deb Package for Linux and start downloading the .deb file
- Once downloaded go to File Manager → Downloads
- Right-click on the deb file and click Open with Discover
- It should open the file in discover 
- On the top right corner, click Install (file location)
- The installation will shortly start
- After installation complete, click Launch at the top right corner to use the application
- Go to Firefox and browse for Brave browser (https://brave.com/linux/) 
- Copy the command line → curl -fsS https://dl.brave.com/install.sh | sh ← and paste on Konsole and press Enter
- Type brave-browser in the Konsole to launch the browser

