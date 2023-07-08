---
description: >-
  Multi-Instance is for the sole purpose of having multiple MyBotRun and
  Bluestacks instances running at the same time.
---

# Multi-Instance

{% hint style="info" %}
The normal MyBotRun instance can run up to 16 accounts, but with multiple insances you can run even more or split your accounts up between instances.&#x20;
{% endhint %}

*   To create an identical instance to the one you've already set up in BlueStacks, please follow these steps:

    1. Open the BlueStacks multi-instance manager.
    2. Locate the instance you've previously created in [bluestacks-installation.md](../installation/bluestacks-installation.md "mention")
    3. Select the option to clone the instance from the icon on right side of your current BlueStacks instance.
    4. BlueStacks will then create a new instance that is identical to the one you had set up before.

    <div align="left">

    <figure><img src="../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

    </div>

{% hint style="warning" %}
The number of instances you can run on your computer depends on its specifications. Typically, for systems with an i5 processor and 8GB of RAM, you can run around 3 instances simultaneously. However, it's important to note that these numbers can vary based on other factors such as the specific tasks or applications running alongside the instances.
{% endhint %}

* Following the previous instructions provided in [switch-accounts.md](switch-accounts.md "mention"), where you have already created multiple accounts by copying and pasting the "MyVillage" folder and renaming them with your chosen naming convention (e.g., dono1, dono2, coc1, coc2, etc.), you can proceed to create additional accounts for the second or third instance.
* To do so, you can use a similar file naming convention as mentioned before. Instead of "SwitchAccount.01.ini," you will use "SwitchAccount.02.ini" for the second instance and "SwitchAccount.03.ini" for the third instance. This approach enables effective differentiation and management of the accounts associated with each respective instance.

{% hint style="danger" %}
Update the "ProfileNames" in the respective "SwitchAccount.0X.ini" files to match the desired account names. Refer to the example files in [configs.md](../files/configs.md "mention") for guidance. ![](<../.gitbook/assets/image (54).png>)
{% endhint %}

* If not done before, Follow the steps in [start.bat.md](../tips-and-tricks/start.bat.md "mention") to create a file to start the MyBotRun instances.&#x20;
* To start your second MyBotRun instance, use the following command `start "coc16" MyBot.run.au3 coc16 BlueStacks5 Pie64_1`
  * In this command, "coc16" represents the account you are launching, and "Pie64\_1" represents the instance of BlueStacks. By executing this command, you will initiate the second MyBotRun instance with the specified account and BlueStacks instance.
* After launching BlueStacks and the Clash instance with MyBotRun loads, stop the bot and connect your desired accounts to the desired profiles, as done previously in [single-session.md](single-session.md "mention").

{% hint style="info" %}
**Reminder:** Ensure that each account and profile is properly connected. To do this, go to the profile tab and use the blue down arrow to reference each account and profile accordingly.
{% endhint %}

* After completing the setup, you can use the created Start.bat file to launch all MyBotRun and BlueStacks instances simultaneously.

