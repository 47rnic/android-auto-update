Android automatic update library(android-auto-update)
===================


The library project implements software version checking, apk file download, software installation（API 21+)


#### 1.Import the library project

Provides two version check methods, add the following code to your project

- Dialog
   
        UpdateChecker.checkForDialog(this);

- Notification

        UpdateChecker.checkForNotification(this);
