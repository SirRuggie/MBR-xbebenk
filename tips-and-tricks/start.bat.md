---
description: Useful for starting multiple instances quickly
---

# Start.bat

*   From the root folder that you downloaded the xbeb files from sourcetree, right-click, New > Text Document&#x20;

    <div align="left">

    <figure><img src="../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

    </div>

{% hint style="warning" %}
If you're unable to see the file name extenstion (i.e. .txt, .bat, etc.) then do the following.

* Click on View on the top of your File Explorer
*   Check File Name Extensions

    <div align="left">

    <figure><img src="../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

    </div>
{% endhint %}

* Rename the new Text Document you created to "Start.bat"
*   Click yes

    <div align="left">

    <figure><img src="../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

    </div>
* Right-click the file and click edit
* The following is an example that **I PERSONALLY** use and may not match yours

```
pushd "%~dp0"
start "coc1" MyBot.run.au3 coc1 BlueStacks5 Pie64 
timeout /t 90
start "coc16" MyBot.run.au3 coc16 BlueStacks5 Pie64_1 
timeout /t 90
start "coc31" MyBot.run.au3 coc31 BlueStacks5 Pie64_2 
```

{% hint style="info" %}
**Breaking down the file**

* `pushd "%~dp0"`: This command changes the current directory of the command line to the location where the script file is saved.
* `start "coc1" MyBot.run.au3 coc1 BlueStacks5 Pie64`: This starts a new bot session with the Profile named coc1 (This will be based on how you named your profiles) and will start Pie64 session of BlueStacks
* `timeout /t 90`: This command pauses the script for 90 seconds before opening the next bots.
{% endhint %}

*   Click File and Click Save

    <div align="left">

    <figure><img src="../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

    </div>
*   **Optional:** Right-click Start.bat, Send to desktop create shortcut

    <div align="left">

    <figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

    </div>
