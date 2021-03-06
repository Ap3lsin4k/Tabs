# Image Viewer

This project allows you to keep the downloaded images neat. App has a convenient and intuitive interface. 

## Getting Started

At first, user should install both modules.

<img src="https://i.imgur.com/GnGa3Aq.png" width="250" />


Image Manager (first module A) is created to input URLs and to work with SQLite database.

Image Viewer (second module B) is created to show images and save them on the device.

### Prerequisites

To install our project user should have a phone with API 21: Android 5.0 (Lollipop) or higher.

### Installing

Click [here](https://github.com/TrueDevels/Tabs/tree/Release/apks) to download apk-files, and click [here](https://github.com/TrueDevels/Tabs/tree/Release/project) to download whole project.

<img src="https://i.imgur.com/7QWDUbW.png" />

Attention! User always must run Image Manager first! Image Viewer is not an independent program!

### How to use it

Enter URL and press OK:

<img src="https://i.imgur.com/nPvHyE9.png" width="250" />


If the link is valid, user will see this:

<img src="https://i.imgur.com/NaxyVqf.png" width="250" />

'Module A' has the second tab called 'History'. Here user can see all URLs that are in database. 

Every URL has its own status, e.g. 'downloaded', 'failed' or 'unknown'. If URL in 'History' is red — this URL is not an image or this URL doesn't exist. And if it is green — it was downloaded fine. If URL is transparent, so checking of URL or downloading of image was failed. 

In this tab user may sort links by date or by status. User may go to ModuleB by clicking on the URL in History. Module B will recheck status of this link, and if it is green, URL would be deleted from the database in 15 seconds, but image would be saved in /sdcard/BIGDIG/test/B. User will be notified about this action.

<img src="https://i.imgur.com/wtKYeM7.jpg" height="150" />


## Authors

* *Ivan Zolotaryov* - 3olplay@gmail.com
* *Andrii Fedorko* - andrii.fedorko01@gmail.com
* *Volodymyr Panasenko* - panvovandrik@gmail.com
* *Andrii Serbenyuk* - andriy.serb1@gmail.com
* *Danil Miniailo* - daniel_changer@yahoo.com
* *Mihail Samsonenko* - michaeldark49a@gmail.com
