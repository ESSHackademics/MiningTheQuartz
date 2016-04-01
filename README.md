[![Stories in Ready](https://badge.waffle.io/ESSHackademics/MiningTheQuartz.svg?label=ready&title=Ready)](http://waffle.io/ESSHackademics/MiningTheQuartz)

# Mining The Quartz - Android Edition
Shared repo for SDK Quartz Training 2/26



## Overview

This sample app is a very simple getting started layout for Quartz Training to reduce the time needed to get started.  It contains 3 Activities that are detailed below:

1. Login Activity - This is where a user can log in with AGOL credentials<br>
![Image of Login](https://dl.dropboxusercontent.com/u/343305078/Login_Activity.png)
<br>
[XML file here](app/src/main/res/layout/activity_login.xml)
<br>
[Java Class file here](app/src/main/java/david/com/quartztraining/LoginActivity.java)

2. Main Activity - Holder for our map and a button that launches the Content Activity to show user content<br>
![Image of Main](https://dl.dropboxusercontent.com/u/343305078/Activity_main.png)
<br>
[XML file here](app/src/main/res/layout/activity_main.xml)
<br>
[Java Class file here](app/src/main/java/david/com/quartztraining/MainActivity.java)


3. Content Activity - Storage for a ListView of content<br>
![Image of Content](https://dl.dropboxusercontent.com/u/343305078/content_main.png)
<br>
[XML file here](app/src/main/res/layout/activity_content.xml)
<br>
[Java Class file here](app/src/main/java/david/com/quartztraining/ContentActivity.java)

## Steps to setup
#### There are a few ways that you can utilize version control during our meeting today.  
1. Using the built in [Android Studio VCS tools][android-vcs]
2. Using an [IDE of your choice][github-ide]
3. Using git from the [Command line][command-line]

Whatever tool you decide to use is O.K. Everyone in the training today has been added as a collaborator to the repository and has full read/write access to push directly to master. In order to get this app template locally follow these steps

1. Clone the repository directly from here. git clone https://github.com/david-chambers/MiningTheQuartz.git
2. Open the project in Android Studio (unless using the built in VCS tools) 
3. During your turn, write code, add the files modified, commit, and push directly to master.  

[android-vcs]: http://javapapers.com/android/android-studio-git-tutorial/
[github-ide]: https://desktop.github.com/
[command-line]: https://git-scm.com/downloads
