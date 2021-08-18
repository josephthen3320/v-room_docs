# Setting up SteamVR

[![steamvr](..\img\logo\steamvr_header.jpg)](https://store.steampowered.com/app/250820/SteamVR/)

SteamVR&trade;  is the ultimate tool for experiencing VR content on the hardware of your choice. 

Full documentations [here](https://valvesoftware.github.io/steamvr_unity_plugin/).

---

## Quickstart

You will need to have SteamVR&trade;   installed through Steam and a SteamVR&trade;  -compatible headset. 

Download SteamVR&trade;   here: [Steam link](https://store.steampowered.com/app/250820/SteamVR/)

---

## Importing on Unity

1. Import SteamVR Plugin from the Asset Store by going to `Window` &rightarrow;  `Asset Store` or clicking on the Asset Store tab in the editor.![Asset Store in Window dropdown](..\img\unity-window-assetstore.png)

2. Search for `SteamVR` in the search box.![unity-assetstore-steamvr](..\img\unity-assetstore-steamvrsearch.png)

3. Scroll down and find the SteamVR Plugin.![unity-assetstore-steamvr](..\img\unity-assetstore-steamvr.png)

4. To import the SteamVR Plugin:

    * If this is your first time importing, click on the blue `Download` button and wait. 

    * Click on the blue `Import` button.

      ![unity-assetstore-steamvr2](..\img\unity-assetstore-steamvr2.png)

5. Wait for the dialog to finish.<br> ![wait for dialogue](..\img\unity-assetstore-steamvr3.png)

6. Click the `All` button at the bottom left corner &rightarrow;  `Import`.<br>![click "all" then "import"](..\img\unity-assetstore-steamvr4.png)
7. If this is your first time setup, this may pop up. Click on `Legacy VR`.<br>![unity-assetstore-steamvr5](..\img\unity-assetstore-steamvr5.png)
8. Since we are developing for VR, click on `Yes`.<br>![unity-assetstore-steamvr6](..\img\unity-assetstore-steamvr6.png)
9. Again, first time setup, click `Accept All`. <br>![unity-assetstore-steamvr7](..\img\unity-assetstore-steamvr7.png)
10. Click `Ok`. <br>![unity-assetstore-steamvr8](..\img\unity-assetstore-steamvr8.png)
11. You have successfully imported SteamVR Plugin to Unity! You should find that the following have been added to your Project Manager.<br>![unity-assetstore-steamvr9](..\img\unity-assetstore-steamvr9.png)

---

## Enabling VR Support

Before you can use SteamVR on Unity, you will need to change some settings to enable VR features.

1. Click on `File` &rightarrow;  `Build Settings`. <br>![enable-vr1](..\img\enable-vr1.png)
2. Click `Player Settings`. <br>![enable-vr2](..\img\enable-vr2.png)
3. Click on `Player` on the left bar &rightarrow;  `Computer Icon`. <br>![enable-vr3](..\img\enable-vr3.png)
4. Navigate to `XR Settings`. <br>![enable-vr4](..\img\enable-vr4.png)
5. Make sure that `Virtual Reality Supported` is **checked**. <br>![enable-vr5](..\img\enable-vr5.png)
6. Under the `Virtual Reality SDKs`, make sure that `OpenVR` is there. <br>![enable-vr6](..\img\enable-vr6.png)
	* If `OpenVR` is missing, click on the `+` icon and select `OpenVR`. <br>![enable-vr6a](..\img\enable-vr6a.png)
7. Remove any other SDKs (e.g. Oculus) by selecting them and clicking the `-` icon. <br>![enable-vr7](..\img\enable-vr7.png)
8. You can now close all the settings windows.

---

## Basic Scene

This section will teach you several SteamVR features that you would use when developing an app.

##### Adding a VR Player

Adding a VR-mode player is as easy as drag and dropping a prefab to the scene - literally!

1. Search for a `Player` prefab under SteamVR assets. <br>![steamvr-import-player1](..\img\steamvr-import-player1.png)
2. Drag and drop to the the scene or the project hierarchy. <br>![steamvr-import-player2](..\img\steamvr-import-player2.png)
3. Delete the `Main Camera` object from the scene hierarchy. <br>![steamvr-import-player3](..\img\steamvr-import-player3.png)
4. 

