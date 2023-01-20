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

**NOTE:** *The steps below can also be completed within the MyBotRun app, but this method is faster. If desired, a guide on how to do this within the app can be provided.*  


* Open the Profiles folder within the xbebenk root directory, where you pulled the code from Github via Sourcetree. 
* Copy the MyVillage folder, and rename it to a different name. This will be used as a template for future accounts.

![Images](Images/Usage/MyBotRun_09.png)  

* Repeat the process of copying the template folder, and renaming it to a new name for each additional account. 
  * If you want to create 15 accounts, then create 15 folders
    * Keep in mind that each BlueStacks instance can support up to 16 Clash of Clans accounts.
    * In my example, I named them dono# because these particular accounts will be donation accounts. 
  * Rename each folder after each one was created to the naming convention you choose (dono1, dono2, dono3, etc.)   

![Images](Images/Usage/MyBotRun_10.png)  

* To switch accounts in MyBotRun, you can use the *SwitchAccount.01.ini* file to specify which accounts you'd like to switch to.
  * This file is not present in the Profiles folder by default, but a copy can be found in the [Configs](./Configs) folder and configured for a specific number of profiles. 
    * Configured for 15 profiles named dono1, dono2, etc.

![Images](Images/Usage/MyBotRun_01.png)  
* Once you've done this, open MyBotRun, right-click on MyBot.run.au3 and select "Run Script (x86)"
  * if a User Account Control window appears, select Yes   
* Let is start, and open BlueStacks and CoC, Stop the bot if it auto starts.

![Images](Images/Usage/MyBotRun_11.png)  
* Go to the Bot tab, then the Profiles sub-tab and select the Switch Profiles dropdown.
  * The profiles you've created will be listed here, and you can select the one you want to switch to.

![Images](Images/Usage/MyBotRun_12.png)  
* If not selected, Select the first account from the dropdown list (e.g. dono1, coc1, etc.) and wait for it to load. 
  * You can check the status at the bottom of the MyBotRun application to confirm that the profile has been loaded. "*Status: Profile dono1 loaded from...*"
* On BlueStacks, go to the first logged-in account that you want to associate with this profile and wait for it to load.

![Images](Images/Usage/MyBotRun_13.png)  
* Select the blue down arrow to sync the account with the profile.

![Images](Images/Usage/MyBotRun_14.png)  
* The status at the bottom of MyBotRun will indicate that the shared preferences have been pulled. "*Status: Pulled shared_prefs of profile...*"
* **Repeat this process for EACH account.** It is important to wait for each new profile to load and for the account you want to associate with that profile to load before moving on to the next account. 
  * Failure to do this may result in the bot not properly switching accounts.

## <a name="multi"></a>Multi-Instance

**UNDER CONSTRUCTION =]**



 
