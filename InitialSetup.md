# Initial MyBotRun xbebenk MOD Setup

## Installation QuickLinks

[Step 1: BlueStacks](#bluestacks)\
[Step 2: Amazon Clash of Clans Install](./#cocinstall)\
[Step 3: SourceTree](./#sourcetree)\
[Step 4: AutoIt](./#autoit)\
[Step 5: RivaTuner](./#rivatuner)\
[Step 6: MemReduct](./#memreduct)

## BlueStacks Installation <a href="#bluestacks" id="bluestacks"></a>

* Download the BlueStacks Setup file
* Double click on BlueStacksInstaller.exe
  * if a User Account Control window appears, select Yes

![Images](Images/BlueStacks/BlueStacks\_01.png)

* Click the "Install Now" button and close the BlueStacks application once the installation is complete.
* Open the "BlueStacks 5 Multi-Instance Manager" on your desktop. By default, each instance will be named "BlueStacks App Player" followed by a number, but you can rename them to something more memorable. Keep in mind, you will need to remember these names later on when you begin using the bot.
* BlueStacks naming conventions
  * Nougat32
  * Nougat32\_1
  * Nougat32\_2
  * etc

![Images](Images/BlueStacks/BlueStacks\_02.png)

* Open the BlueStacks 5 Multi-Instance Manager, and click on the gear icon next to the BlueStacks instance you wish to configure.

![Images](Images/BlueStacks/BlueStacks\_03.png)

* Under the Performance tab, adjust the following settings:
  * CPU allocation: Low (1Core)
  * Memory allocation: low (1GB)
  * Frame rate: 20
* Click "Save Changes" and then click on the gear icon again to re-open the settings menu.

![Images](Images/BlueStacks/BlueStacks\_04.png)

* Select "Display" from the left tab menu and change the following settings:
  * Display Resolution: Custom
    * Click Add resolution
    * Width = 860
    * Height = 676
    * Click save on the right of the resolution menu
    * Select the 860 x 676 radio button
  * Pixel density: 160 DPI (Low)
  * Click "Save Changes" and then click on the gear icon again to re-open the settings menu.

![Images](Images/BlueStacks/BlueStacks\_05.png)

* Select "Graphics" from the left tab menu and change the following settings:
  * Graphics engine mode: Compatibility
* Click "Save Changes".

### Install the Amazon Appstore and Clash of Clans on the BlueStacks Instance by following these steps: <a href="#cocinstall" id="cocinstall"></a>

* From the BlueStacks 5 Multi-Instance Manager, start the first BlueStacks instance.

![Images](Images/BlueStacks/BlueStacks\_06.png)

* Once Loaded, click on the "System apps" folder and open Chrome.
* Go to Amazon.com and search for "Amazon Appstore".

![Images](Images/BlueStacks/BlueStacks\_07.png)

* Download and Install the Amazon Appstore

![Images](Images/BlueStacks/BlueStacks\_08.png)

* Click Get Amazon AppStore.

![Images](Images/BlueStacks/BlueStacks\_09.png)

* Click Ok on the security pop up at the bottom of the screen.

![Images](Images/BlueStacks/BlueStacks\_10.png)

* Click Open on the pop up at the bottom of the screen.

![Images](Images/BlueStacks/BlueStacks\_11.png)

* Click Install.

![Images](Images/BlueStacks/BlueStacks\_12.png)

* Click Open.

![Images](Images/BlueStacks/BlueStacks\_13.png)

* Click Sign In or Create a new Amazon Account.

![Images](Images/BlueStacks/BlueStacks\_14.png)

* Once Signed in, Search for Clash of Clans and Install it.

![Images](Images/BlueStacks/BlueStacks\_15.png)

* Click Install on the pop up.
* Close the BlueStacks session when the installation is complete and open the Multi-Instance Manager.

![Images](Images/BlueStacks/BlueStacks\_16.png)

* Click the "Clone Instance" button to create a copy of the first BlueStacks instance

![Images](Images/BlueStacks/BlueStacks\_19.png)

* Repeat these steps to create additional BlueStacks instances and make sure to name them accordingly (e.g. "Nougat32", "Nougat32\_1", "Nougat32\_2", etc.) for use with the bot.
  * Instance count can be changed to 2 or more (_Not all machines can handle more than 2. This will be based on your machines performance_)

_BlueStacks Installation and configuration complete_

## SourceTree Installation <a href="#sourcetree" id="sourcetree"></a>

* Download the Sourcetree Setup file
* Double click on SourcetreeSetup.exe
  * if a User Account Control window appears, select Yes

![Images](Images/Sourcetree/Sourcetree\_01.png)

* Click Skip on the Registration Menu

![Images](Images/Sourcetree/Sourcetree\_02.png)

* Click Next

![Images](Images/Sourcetree/Sourcetree\_03.png)

* Click Cancel on the error message

![Images](Images/Sourcetree/Sourcetree\_04.png)

* Click Next

![Images](Images/Sourcetree/Sourcetree\_05.png)

* Enter your email and click Next

![Images](Images/Sourcetree/Sourcetree\_06.png)

* Select No

**Once the setup is successful, you'll see a window like below:**\
![Images](Images/Sourcetree/Sourcetree\_07.png)

![Images](Images/Sourcetree/Sourcetree\_08.png)

* Click "Clone" from the top menu in Sourcetree.

![Images](Images/Sourcetree/Sourcetree\_09.png)\
**Source Path:** https://github.com/xbebenk/MBR\_xbebenkMOD\
**Destination Path:** Enter the directory where you want to save the MBR folder.\
_In my instance, I created a folder on the desktop called xbeb, so the Destination path for me was C:\Users\User\Desktop\xbeb_\
**Name:** Choose a name for your folder.

![Images](Images/Sourcetree/Sourcetree\_10.png)

* Click "Clone" to download xbebenkmod and save it in the given folder.

![Images](Images/Sourcetree/Sourcetree\_11.png)\
Successfully cloned xbebenkMOD on your desktop

![Images](Images/Sourcetree/Sourcetree\_12.png)\
Verify the folder structure that was cloned

_Sourcetree Installation Complete_

## AutoIt Installation <a href="#autoit" id="autoit"></a>

* Download the AutoIt setup file and double click on AutoIt-Setup.exe
  * if a User Account Control window appears, select Yes

![Images](Images/AutoIt/AutoIt\_01.png)

* Click Next and **leave all defaults selected during the installation**

![Images](Images/AutoIt/AutoIt\_02.png)

* Click I Agree

![Images](Images/AutoIt/AutoIt\_03.png)

* Click Next

![Images](Images/AutoIt/AutoIt\_04.png)

* Click Next

![Images](Images/AutoIt/AutoIt\_05.png)

* Click Next

![Images](Images/AutoIt/AutoIt\_06.png)

* Click Install

![Images](Images/AutoIt/AutoIt\_07.png)

* Click Finish

**After installation is complete, add AutoIt to the system variable path**

![Images](Images/AutoIt/AutoIt\_08.png)

* Click on the Windows Start Menu and type "Path" and open "Edit the system environment variables"

![Images](Images/AutoIt/AutoIt\_09.png)

* The System Properties menu will load, select Environment Variables at the bottom of the screen menu

![Images](Images/AutoIt/AutoIt\_10.png)

* Select Path on **System Variables** and click Edit

![Images](Images/AutoIt/AutoIt\_11.png)

* Click New and add the AutoIt folder there "C:\Program Files (x86)\AutoIt3"

_AutoIt Installation Complete_

## RivaTuner Installation <a href="#rivatuner" id="rivatuner"></a>

* Download the RivaTuner setup file and double click on RTSSSetup732.exe
  * if a User Account Control window appears, select Yes

![Images](Images/RivaTuner/RivaTuner\_01.png)

* Select Ok and **leave all defaults selected during the installation**

![Images](Images/RivaTuner/RivaTuner\_02.png)

* Select Next

![Images](Images/RivaTuner/RivaTuner\_03.png)

* Select "I accept" radio button and click Next

![Images](Images/RivaTuner/RivaTuner\_04.png)

* Select Next

![Images](Images/RivaTuner/RivaTuner\_05.png)

* Select Install

![Images](Images/RivaTuner/RivaTuner\_06.png)

* Click Finish

**After installation is complete, edit Riva Tuner settings**

![Images](Images/RivaTuner/RivaTuner\_07.png)

* Click the Windows Start Menu and search for RivaTuner and select "RivaTuner Statistics Server"
  * if a User Account Control window appears, select Yes

![Images](Images/RivaTuner/RivaTuner\_08.png)

* Click OK on the DirectX Warning

![Images](Images/RivaTuner/RivaTuner\_09.png)

* Click "No" on the Download Page Menu **DO NOT UPDATE**

![Images](Images/RivaTuner/RivaTuner\_10.png)

* RivaTuner will now open and display as an icon on the task tray on the bottom right above the clock. Click on the icon to open RivaTuner.

![Images](Images/RivaTuner/RivaTuner\_11.png)\
**Once Riva Tuner is open, navigate to the settings and change the following:**

* Settings
  * Start with Windows "On"
  * Application Detection level "High"
  * Framerate limit "20"
* Minimize RivaTuner **DO NOT Close** Congratulations, you have successfully installed RivaTuner.

## MemReduct Installation <a href="#memreduct" id="memreduct"></a>

MemReduct cleans any cached memory to ensure your system is running smoothly.

* Download the MemReduct setup file and double click on memreduct-3.4-setup.exe
  * if a User Account Control window appears, select Yes

![Images](Images/MemReduct/MemReduct\_01.png)

* Select Next and **leave all defaults selected during the installation**

![Images](Images/MemReduct/MemReduct\_02.png)

* Accept the terms and click Next

![Images](Images/MemReduct/MemReduct\_03.png)

* Click Next

![Images](Images/MemReduct/MemReduct\_04.png)

* Click Install

![Images](Images/MemReduct/MemReduct\_05.png)

* Click Yes when the Update popup displays to update.

![Images](Images/MemReduct/MemReduct\_06.png)

* Click Close

![Images](Images/MemReduct/MemReduct\_07.png)

* On the Mem Reduct Application, click Settings on the top Menu bar.
  * Check "Load on system startup"
  * Check "Start minimized"

![Images](Images/MemReduct/MemReduct\_08.png)

* Click "Clean memory" and "Yes" to confirm
* Close the menu and exit out of any installation window that is still open.

Congratulations, you have successfully installed MemReduct.

## Installation Complete

Continue to the usage page for further instructions on how to use it.\
[MyBotRun Usage](Usage.md)
