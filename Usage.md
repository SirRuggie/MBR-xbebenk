# Using MyBotRun xbebenk
There are different ways to launch MyBotRun depending on your preferences and the number of accounts you have connected.   

**Note:** If you haven't launched MyBotRun before, there will not be a "profiles" folder in the directory where you pulled the files from Sourcetree. It is recommended that you follow the instructions for "Single Session" if this is your first time using the bot.

### Quick Links
[Single-Session](Usage.md#single)  
[Switch Accounts](Usage.md#switch)  
[Multi-Instance](Usage.md#multi)  

## <a name="acc"></a>Preparing Your Clash of Clans Account
In order for MyBotRun to work properly with a Town Hall 3 account, it must have at least 70 capacity *Army Camps*. This can be achieved by upgrading two Army Camps to level 3.
**NOTE:** The game provides enough gems to upgrade everything needed to prepare your account for MyBotRun, make sure to do so before running the bot.


## <a name="single"></a>Single Session
### First Time Use Setup
* Open the folder where you downloaded MyBotRun from Github via Sourcetree.

![Images](Images/Usage/MyBotRun_01.png)  
* Right-click on the file "MyBot.run.au3" and select "Run Script (x86)"
  * if a User Account Control window appears, select Yes   

![Images](Images/Usage/MyBotRun_04.png)  
![Images](Images/Usage/MyBotRun_05.png)  
* Once MyBotRun loads, you will see the above application.
  * Close out MyBotRun and open the source folder that Sourcetree downloaded to.

![Images](Images/Usage/MyBotRun_06.png)  
* Open the source folder where you downloaded MyBotRun from Github and find the "profiles" folder.

![Images](Images/Usage/MyBotRun_07.png)  
* Open the "MyVillage" folder within the "profiles" folder.
* **Important** The config file MUST be updated in order for Clash of Clans to launch.
* You can find Amazon configs to use in the [Configs](./Configs) folder.
  * **NOTE:** The configs included in the folders are based on personal preferences for Town Hall levels. You can update the configs within MyBotRun to meet your own preferences. 
  * *If you are using new Town Halls, copy the config.ini and building.ini from the "Below TH6" folder and overwrite the ones in the MyVillage folder.*

**Relaunch MyBotRun**  

* Open the folder where you downloaded xbebenk via Sourcetree.

![Images](Images/Usage/MyBotRun_01.png)  
* Right-click on MyBot.run.au3 and select "Run Script (x86)"
  * if a User Account Control window appears, select Yes   

* Once MyBotRun is loaded, click Start Bot or if you used one of the configs in [Configs](./Configs), the bot will start automatically within 10 seconds.
* Wait for Clash to load and stop the bot. 
 * **NOTE: If Clash does not load or loads a black screen, ensure that you have added the Amazon Config file settings**
* Click on the Clash account settings and connect your Supercell ID the same as you would do on any other device.

![Images](Images/Usage/MyBotRun_01.png)  
* On the MyBotRun application, click on the Bot tab. 
  * Select the Profiles sub-tab and click the blue down arrow to pull the CoC Shared Prefs
    * Clicking the blue down arrow saves your current BlueStacks Logged in Clash of Clans session to the current MyBotRun Profile (MyVillage folder).

* Click Start Bot and watch it work


## <a name="switch"></a>Switch Accounts
* On the BlueStacks Instance where you configured the first account from above, add the number of Clash accounts that you'd like.
 * 16 Clash accounts can be loaded on each BlueStacks instance. 
 * For multiple-instances of BlueStacks, see [Multi-Instance](Usage.md#multi)  

**NOTE:** *The Below methods can be created within the MyBotRun app as well, but I find this method to be faster.*  
*I can add a guide on how to do via the app as well, if someone wants it*  


* Open the xbebenk root folder that was selected for the Sourcetree download, open the Profiles folder and copy the MyVillage folder. 
  * Personally I change MyVillage to "Default" and create copies from it so that I always have a baseline to copy if needed later.   

![Images](Images/Usage/MyBotRun_09.png)  

* Paste the MyVillage folder into the Profiles folder for the amount of accounts that you would like to create. 
  * If you want to create 15 accounts, then create 15 folders
    * In my example, I named them dono# because these particular accounts will be donation accounts. 
  * Rename each folder after each one was created to the naming convention you choose (dono1, dono2, dono3, etc.)   

![Images](Images/Usage/MyBotRun_10.png)  

* MyBotRun reads *SwitchAccount.01.ini* to know which accounts are to be loaded and switched to.
  * By default the SwitchAccount.01.ini file does not exist in the Profiles folder unless selected within the app. 
  * A copy of it can be found in the [Configs](./Configs) folder
    * Configured for 15 profiles named dono1, dono2, etc.

![Images](Images/Usage/MyBotRun_01.png)  
* Right-Click on MyBot.run.au3 and select "Run Script (x86)"
  * if a User Account Control window appears, select Yes   
* Let is start, and open BlueStacks and CoC, Stop the bot.

![Images](Images/Usage/MyBotRun_11.png)  
* Click on the Bot tab, click on the Profiles sub-tab and click on the Switch Profiles dropdown. 
  * The profiles created above will now be shown in the dropdown list.

![Images](Images/Usage/MyBotRun_12.png)  
* If not selected, Select the first account from the drop down (dono1, coc1, etc.) and wait for it to load.
  * A good way to know the account was loaded is to watch the Status at the bottom of MybotRun "*Status: Profile dono1 loaded from...*"
* On BlueStacks, go to the first logged in account that you would like to be associated with this profile and wait for it to load. 

![Images](Images/Usage/MyBotRun_13.png)  
* Select the blue down arrow to sync the account with the profile

![Images](Images/Usage/MyBotRun_14.png)  
* The Status at the bottom of MyBotRun will say "*Status: Pulled shared_prefs of profile...*"
* **Repeat this process for EACH account.** With each step, you must wait for the new profile to load as well as the account you want associated with that profile. 
  * Failure to do this will result in a failure of the bot properly switching accounts. 

## <a name="multi"></a>Multi-Instance

**UNDER CONSTRUCTION =]**



 
