# Initial MyBotRun xbebenk MOD Setup

## Installation QuickLinks
[BlueStacks](InitialSetup.md#bluestacks)  
[Amazon Clash of Clans Install](InitialSetup.md#cocinstall)  
[SourceTree](InitialSetup.md#sourcetree)  
[AutoIt](InitialSetup.md#autoit)  
[RivaTuner](InitialSetup.md#rivatuner)  

## <a name="bluestacks"></a>BlueStacks Installation
* Download the BlueStacks Setup file
* Double click on BlueStacksInstaller.exe
  * if a User Account Control window appears, select Yes    

![Images](Images/BlueStacks/BlueStacks_01.png)
* Click Install now and close BlueStacks session once installation is complete. 

* Go to your desktop and double-click on "BlueStacks 5 Multi-Instance Manager"
By default BlueStacks will name each instance "BlueStacks App Player" with a number behind it. 
You can rename this to anything you want, but take note that you MUST remember the following naming later on once we start the bot. 
* BlueStacks Data Naming
  * Nougat32
  * Nougat32_1
  * Nougat32_2
  * etc

![Images](Images/BlueStacks/BlueStacks_02.png)
* Click on the gear to the right of the BlueStacks instance

![Images](Images/BlueStacks/BlueStacks_03.png)
* On Performance change the following Settings:
  * CPU allocation: Low (1Core)
  * Memory allocation: low (1GB)
  * Frame rate: 20
* Click Save Changes and Click the Gear again to open the settings menu

![Images](Images/BlueStacks/BlueStacks_04.png)
* Select Display on the left tab menu and change the following settings:
  * Display Resolution: Custom 
    * Click Add resolution
    * Width = 860
    * Height = 676
    * Click save on the right of the resolution menu
    * Select the 860 x 676 radio button
  * Pixel density: 160 DPI (Low)
  * Click Save Changes and Click the Gear again to open the settings menu

![Images](Images/BlueStacks/BlueStacks_05.png)
* Select Graphics on the left tab menu and change the following settings:
  * Graphics engine mode: Compatibility
* Click Save Changes

### <a name="cocinstall"></a>Clash of Clans install on BlueStacks Instance  
* From the BlueStacks multi-instance manager, click start on the first BlueStacks instance

![Images](Images/BlueStacks/BlueStacks_06.png)
* Once Loaded click on the "System apps" folder and open Chrome
* Go to Amazon.com and search for Amazon Appstore

![Images](Images/BlueStacks/BlueStacks_07.png)
* Click Download and Install Amazon Appstore

![Images](Images/BlueStacks/BlueStacks_08.png)
* Click Get Amazon AppStore

![Images](Images/BlueStacks/BlueStacks_09.png)
* Click Ok on the security pop up at the bottom of the screen

![Images](Images/BlueStacks/BlueStacks_10.png)
* Click Open on the pop up at the bottom of the screen

![Images](Images/BlueStacks/BlueStacks_11.png)
* Click Install

![Images](Images/BlueStacks/BlueStacks_12.png)
* Click Open

![Images](Images/BlueStacks/BlueStacks_13.png)
* Click on Sign In or Create a new Amazon Account

![Images](Images/BlueStacks/BlueStacks_14.png)
* Once Signed in, Search for Clash of Clans and Install

![Images](Images/BlueStacks/BlueStacks_15.png)
* Click Install on the pop up
* Close out of the BlueStacks Session when the Clash installation is complete and open the multi-instance manager.

![Images](Images/BlueStacks/BlueStacks_16.png)
* Click on the Clone Instance button

![Images](Images/BlueStacks/BlueStacks_17.png)
* Leave the Clone Instance menu settings as default. This will take the settings that was set earlier in the BlueStacks installation and duplicate it to the new instances. 
  * Instance count can be changed to 2 or more (*Not all machines can handle more than 2. This will be based on your machines performance*)

*BlueStacks Installation and configuration complete*

## <a name="sourcetree"></a>SourceTree Installation
* Download the Sourcetree Setup file
* Double click on SourcetreeSetup.exe
  * if a User Account Control window appears, select Yes   


![Images](Images/Sourcetree/Sourcetree_01.png)
* Click Skip on the Registration Menu

![Images](Images/Sourcetree/Sourcetree_02.png)
* Click Next

![Images](Images/Sourcetree/Sourcetree_03.png)
* Click Cancel on the error message

![Images](Images/Sourcetree/Sourcetree_04.png)
* Click Next

![Images](Images/Sourcetree/Sourcetree_05.png)
* Enter your email and click Next

![Images](Images/Sourcetree/Sourcetree_06.png)
* Select No

**Once the setup is successful, you'll see a window like below:**  
![Images](Images/Sourcetree/Sourcetree_07.png)


![Images](Images/Sourcetree/Sourcetree_08.png)
* Click on "Clone" from the top menu


![Images](Images/Sourcetree/Sourcetree_09.png)  
**Source Path:** https://github.com/xbebenk/MBR_xbebenkMOD  
**Destination Path:** Where you intend to have your MBR folder  
*In my instance, I created a folder on the desktop called xbeb, so the Destination path for me was C:\users\user\Desktop\xbeb*    
**Name:** Choose any name you prefer  


![Images](Images/Sourcetree/Sourcetree_10.png)
* Click "Clone" 
  * This will download xbebenkmod and save it in the given folder on my desktop.


![Images](Images/Sourcetree/Sourcetree_11.png)  
Successful cloned xbebenkMOD on our desktop

![Images](Images/Sourcetree/Sourcetree_12.png)  
Folder structure that we cloned

*Sourcetree Installation Complete*

## <a name="autoit"></a>AutoIt Installation
* Download the AutoIt Setup file
* Double click on AutoIt-Setup.exe
  * if a User Account Control window appears, select Yes    

![Images](Images/AutoIt/AutoIt_01.png)
* Click Next and **leave all defaults selected**  

![Images](Images/AutoIt/AutoIt_02.png)
* Click I Agree  

![Images](Images/AutoIt/AutoIt_03.png)
* Click Next  

![Images](Images/AutoIt/AutoIt_04.png)
* Click Next  

![Images](Images/AutoIt/AutoIt_05.png)
* Click Next  

![Images](Images/AutoIt/AutoIt_06.png)
* Click Install  

![Images](Images/AutoIt/AutoIt_07.png)
* Click Finish  

**After installation is complete, add AutoIt to the system variable path**  

![Images](Images/AutoIt/AutoIt_08.png)
* Click on the Windows Start Menu and type "Path" and open "Edit the system environment variables"  

![Images](Images/AutoIt/AutoIt_09.png)
* The System Properties menu will load, select Environment Variables at the bottom of the screen menu  

![Images](Images/AutoIt/AutoIt_10.png)
* Select Path on **System Variables** and click Edit

![Images](Images/AutoIt/AutoIt_11.png)
* Click New and add the AutoIt folder there "C:\Program Files (x86)\AutoIt3"

*AutoIt Installation Complete*

## <a name="rivatuner"></a>RivaTuner Installation 
* Download the RivaTuner Setup file
* Double Click on RTSSSetup732.exe
  * if a User Account Control window appears, select Yes      

![Images](Images/RivaTuner/RivaTuner_01.png)
* Select Ok and **Leave all defaults selected**

![Images](Images/RivaTuner/RivaTuner_02.png)
* Select Next

![Images](Images/RivaTuner/RivaTuner_03.png)
* Select "I accept" radio button and click Next

![Images](Images/RivaTuner/RivaTuner_04.png)
* Select Next

![Images](Images/RivaTuner/RivaTuner_05.png)
* Select Install

![Images](Images/RivaTuner/RivaTuner_06.png)
* Click Finish

**After installation is complete, edit Riva Tuner settings**  

![Images](Images/RivaTuner/RivaTuner_07.png)
* Click the Windows Start Menu and search for RivaTuner and select "RivaTuner Statistics Server"
  * if a User Account Control window appears, select Yes    

![Images](Images/RivaTuner/RivaTuner_08.png)
* Click OK on the DirectX Warning

![Images](Images/RivaTuner/RivaTuner_09.png)
* Click "No" on the Download Page Menu **DO NOT UPDATE**

![Images](Images/RivaTuner/RivaTuner_10.png)
* RivaTuner will now open and display as an icon on the task tray on the bottom right above the clock. Click on the icon to open RivaTuner.

![Images](Images/RivaTuner/RivaTuner_11.png)  
**Once Riva Tuner is open change the following settings**
* Settings
  * Start with Windows "On"
  * Application Detection level "High"
  * Framerate limit "20"

* Minimize RivaTuner **DO NOT Close**


## Installation Complete
If all the previous installation steps have been completed, go to the Usage page for further instructructions.     
[MyBotRun Usage](Usage.md)  
