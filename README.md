This is a dashboard card that can be used with HomeSeer HS4.

Features: Animation when time changes (every minute), day/night mode.


Prerequisites: Before installing, in HomeSeer, create a new Virtual Device, named something like "Dashboard Clock".
Note the Reference Id number of the VD.
Next, create a recurring event that runs every minute from the top of every hour.
Run an immediate script command.


copy/paste this line and replace the reference Id 4022 with your VD Ref Id:
Code:
&nhs.SetDeviceString(4022,DateTime.Now.ToString("t"),True)

Installation: Download the card_clock.zip file attachment from this post.
Go into Edit mode on your dashboard, and click the '+' button on the bottom right.
Click the Upload Card button on the top right and upload the card_clock.zip file you just downloaded.
Add the Clock to your dashboard and configure. Select the VD you created above and configure as needed.

Features: Animation when time changes (every minute), day/night mode.
​
Example:
​
