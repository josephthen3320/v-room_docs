# Setting up Embedded Browser (by Zen Fulcrum LLC)

The Embedded Browser provides an easy solution to rendering webpages in your Unity project. It supports both PC and VR mode.

[View in Asset Store](https://assetstore.unity.com/packages/tools/gui/embedded-browser-55459#)

---

## Getting Started

To get started with Embedded Browser, you should install it on your machine. See below for the version that we are using! <br>

##### Download Unity Editor

`2019.8.4f1` &nbsp;&nbsp;&nbsp;&nbsp; [Unity Hub](https://unity3d.com/get-unity/download) &nbsp;&nbsp; | &nbsp;&nbsp; [Editor (Win)](https://download.unity3d.com/download_unity/9bc9d983d803/Windows64EditorInstaller/UnitySetup64-2018.4.8f1.exe)  &nbsp;&nbsp; | &nbsp;&nbsp; [Editor (Mac)](https://unity3d.com/get-unity/download?thank-you=update&download_nid=62959&os=Mac)

...or [`click here`](unityhub://2019.4.8f1/60781d942082) to install directly if you already have Unity Hub!

---

## Installation Walkthrough

There are two ways to install Unity on your machine: via [`Unity Hub`](#unity-hub) or  [`standalone installation`](#standalone-installation).

#### Unity Hub

Installing through Unity Hub is the most recommended method as it is simple and straightforward! 

You need to make sure that you have Unity Hub installed already on your machine to proceed.

Open Unity Hub &#8594;  Navigate to the `Installs` tab on the left &#8594;  Click on `Add` button to add the version of Unity Editor that you need.

![Unity Hub](..\img\unity-hub-install.png)

Select the version that you need (`2019.4.8f1`) &#8594;  Click `next`.

![Unity version select](..\img\unity-hub-versionselect.png)

Now select all the modules that you need.

Since we are developing for both mobile and PC version, go ahead and check `Android Build Support`, `Universal Windows Platform Build Support`, and `Windows Build Support`.

We highly recommend you to also install `Microsoft Visual Studio Community`. Visual Studio is an integrated development environment (IDE) that most people use when developing in Unity. It has been integrated directly into Unity to provide you with an easy and fast access when you need to code.

<table>
    <tr>
    	<td><img src="../../img/unity-hub-modulesselect.png" /></td>
        <td><img src="../../img/unity-hub-modulesselect2.png" /></td>
    </tr>
</table>

When you're done, click `next`.

Check the box `I have read and agree...` and click `next`. (Feel free to read the EULA given in the link :D )

Do the same thing with the Android EULA and then press `Done`.

<table>
    <tr>
    	<td><img src="../../img/unity-hub-vsagreement.png"></td>
        <td><img src="../../img/unity-hub-androidagreement.png"></td>
    </tr>
</table>


Wait until the installation finishes. This may take several minutes to several hours, depending on which module(s) you have chosen.

![unity-hub-installing](..\img\unity-hub-installing.png)

And... you're done!



#### Standalone Installation

The standalone installation is typically used when you can't find the Unity version you need since it might already been replaced by a new version or when there are issues with installing using the Unity Hub. This includes downloading and executable installer (.exe), installing, and locating on Unity Hub.

Unity Archive [Download](https://unity3d.com/get-unity/download/archive).

You need to have `Unity Hub` already installed on your machine.

![unity-archive](..\img\unity-archive.png)Download `Unity Installer` for the version you need (`2019.4.8f1`). 

If you only need the editor without any modules, download the `Unity Editor 64-bit`for Windows or `Unity Editor` for Mac.

##### Unity Install Assistant

**Note: ** The Unity Installer **requires** the internet to download the editor files for installation. Make sure you have adequate internet connection.

Locate the file you have downloaded and open it.

The name should be something like `UnityDownloadAssistant-2019.4.8f1.exe`. 

![unity-installer](..\img\unity-installer.png)

Click `next` &#8594;  check the `I accept ...`  &#8594;  `next`.

<table>
    <tr>
    	<td><img src="..\..\img\unity-installer-01.png" alt="unity-installer-01" /></td>
        <td><img src="..\..\img\unity-installer-02.png" alt="unity-installer-02" /></td>
    </tr>
</table>

Select all the modules you need - you can refer to the picture below.

![unity-installer-03](..\img\unity-installer-03.png)

Select where you want to download the installation files (temporary) and the install location. Click `next` when you're done.

![unity-installer-04](..\img\unity-installer-04.png)

Wait for the installation to finish and then click on `Finish`. You have successfully installed the Unity Editor.

##### Unity Editor

This one is very straightforward. 

After you download the installer, open it. The file should be named something like `UnitySetup64-2018.4.8f1.exe`.

![unity-editor-01](..\img\unity-editor-01.png)

Follow the instruction on screen. Choose where you want to install it. Once finished you have successfully installed the editor.

##### Locating on Unity Hub

Now, you need to locate the newly installed editor on Unity Hub.

Open Unity Hub and navigate to the `Installs` section &#8594; click on `Locate`. 

![unity-hub-install](..\img\unity-hub-install.png)

Locate the `Unity.exe` in the location where you install the editor. It will be inside the `Editor` folder.

Select `Unity.exe` and then click `Select Editor`.

![unity-hub-locate](..\img\unity-hub-locate.png)

You should now have the editor in your Unity Hub.

---

## Unity License

If you have not yet activated a license to use Unity, see below.

**You need a Unity ID to manage your license.** <a href="https://id.unity.com/en/" target="_blank">`Create Unity ID`</a>

[Create Unity ID]: https://id.unity.com/en/	"Create Unity ID"

#### Activating Unity License

Go to your profile on the top right corner &#8594; `Manage license`

![Activate new license screen](..\img\unity-hub-license.png)

Click on `Activate New License` &#8594;  `Unity Personal` &#8594;  `I don't use Unity in...` &#8594;  `Done`

![Unity personal license activation](..\img\unity-hub-licenseselect.png)

**You have successfully activated your new license!**

---

[Home](/../)