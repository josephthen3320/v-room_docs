# Welcome to the V-ROOM Documentations

Find how to setup various things needed to work with the V-ROOM Project Team.

---

## Project prerequisites


Please download and install the following software to start developing.

| Prerequisite | Version      | Link(s)                                                      |
| ------------ | ------------ | ------------------------------------------------------------ |
| Unity Hub    | `Latest`     | [:material-microsoft-windows: Download](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe){ .md-button .md-button--primary} [:material-apple: Download](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.dmg){.md-button} |
| Unity Editor | `2019.4.8f1` | [Unity Hub :material-download:](unityhub://2019.4.8f1/60781d942082){.md-button .md-button--primary} [:material-microsoft-windows:](https://download.unity3d.com/download_unity/60781d942082/Windows64EditorInstaller/UnitySetup64-2019.4.8f1.exe){.md-button} [:material-apple:](https://unity3d.com/get-unity/download?thank-you=update&download_nid=64071&os=Mac){.md-button} |
| Steam        | `Latest`     | [Get Steam :material-download:](https://store.steampowered.com/about/){.md-button .md-button--primary} [:material-microsoft-windows:](https://cdn.cloudflare.steamstatic.com/client/installer/SteamSetup.exe){.md-button} [:material-apple:](https://cdn.cloudflare.steamstatic.com/client/installer/steam.dmg){.md-button} |
| SteamVR      | `Latest`     | [:material-steam: Get on Steam](steam://run/250820){.md-button .md-button--primary} [:octicons-link-external-16: View on Web]([SteamVR on Steam (steampowered.com)](https://store.steampowered.com/app/250820/SteamVR/)){.md-button} |

!!! important
    You can't start working until you have all of these software!

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

??? hint "You don't need to worry about this section!"
    This is for the documentations maintainer to see the layout of this website.

```
mkdocs.yml				# The configuration file.
README.md				# The README shown on GitHub
docs/
    index.md			# The documentation homepage.
    about.md			# About us page.
    
	user-guide/
        unity-setup.md		# Unity installation & Unity License activation.
        project-setup.md	# Setting up a project in Unity.
        steamvr.md			# Setting up SteamVR in Unity.
		zfbrowser.md		# Setting up ZF Browser (including for SteamVR)

    img/				# Contains various images used in the site
        logo/			# Logo images
```

