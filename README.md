## HomeSeer HS4 Dashboard Clock

**Features**: Animation when time changes (every minute), day/night mode.


**Prerequisites**: Before installing, in HomeSeer, create a new Virtual Device, named something like "Dashboard Clock".
Note the Reference Id number of the VD.
Next, create a recurring event that runs every minute from the top of every hour.
Run an immediate script command.

<img width="511" height="324" alt="image1" src="https://github.com/user-attachments/assets/cdd413c7-6242-4010-9bd7-1aae0a1a745f" />


copy/paste this line and replace the reference Id 4022 with your VD Ref Id:

> &nhs.SetDeviceString(4022,DateTime.Now.ToString("t"),True)

**Installation**: Download the card_clock.zip file attachment from this post.
Go into Edit mode on your dashboard, and click the '+' button on the bottom right.
Click the Upload Card button on the top right and upload the card_clock.zip file you just downloaded.
Add the Clock to your dashboard and configure. Select the VD you created above and configure as needed.

<img width="474" height="819" alt="image2" src="https://github.com/user-attachments/assets/05058cd4-2178-4308-8e96-8ed391d29a7d" />

**Features**: Animation when time changes (every minute), day/night mode.

**Example**:
<img width="313" height="100" alt="image3" src="https://github.com/user-attachments/assets/09a1a3aa-4247-4983-b275-d1bedaba9027" />​
