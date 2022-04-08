# Welcome to the V-ROOM Documentations

Find how to setup various things needed to work with the V-ROOM Project Team.

---

## Project prerequisites

Please download and install the following software to start developing.

| Prerequisite | Version      | Link(s)                                                      |
| ------------ | ------------ | ------------------------------------------------------------ |
| Unity        | `2019.4.8f1` | [Install on Unity Hub](unityhub://2019.4.8f1/60781d942082) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ***Recommended!***<br />[Download Unity Hub](https://unity3d.com/get-unity/download)<br />[[Win] Download Editor (.exe)](https://download.unity3d.com/download_unity/60781d942082/Windows64EditorInstaller/UnitySetup64-2019.4.8f1.exe)<br />[[Mac] Download Editor (.dmg)](https://unity3d.com/get-unity/download?thank-you=update&download_nid=64071&os=Mac)<br /> |
| Steam        | `Latest`     | [Download Steam](https://store.steampowered.com/about/)      |
| SteamVR      | `Latest`     | [Steam Link](https://store.steampowered.com/app/250820/SteamVR/) |

---

## Documentations

This section details various setting up guides especially useful for first-time users or when trying to do complex operations.

### Software Setup

[Unity Installation Guide](user-guide/unity-setup/index.html)

### Unity Plugins

| Plugin Name 		| Quick Link 	|
| ----------- 		| ----------	|
| SteamVR Plugin 	| [Setup Guide](user-guide/steamvr/index.html) \| [Local link](user-guide/steamvr) |
| Embedded Browser 	| [Setup Guide](user-guide/zfbrowser/index.html) 	|


---

## Documentations layout

```
mkdocs.yml    			# The configuration file.
docs/
    index.md  			# The documentation homepage.
    about.md			# About us page.
    
	user-guide/
        unity-setup.md		# Unity installation & Unity License activation.
        project-setup.md	# Setting up a project in Unity.
        steamvr.md			# Setting up SteamVR in Unity.
		zfbrowser.md		# Setting up ZF Browser (including for SteamVR)

    img/
        logo/
```

