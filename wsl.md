# Windows Subsystem for Linux Setup for OpenShift on Azure

This is a quick guide for installing the Windows Subsystem for Linux, getting the Azure CLI installed, and enabling the copy/paste functionality within bash by pinning it to the desktop.

## Install Windows Subsystem for Linux

- Follow the steps at [Windows Subsystem for Linux Installation Guide for Windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10). Make sure you follow the last step to [initialize your newly installed distro](https://docs.microsoft.com/en-us/windows/wsl/initialize-distro).

### Enable Copy/Paste

- Hit the start menu, type in your distro name.
- **Important** right click the *command* result, *not* the app result, and choose "open file location".
- Right click the distro executable, in this case ubuntu.exe, and choose *pin to taskbar*.
- Right click the icon in your taskbar, right click the word ubuntu, and choose *Properties*.
- Now go to the Options tab, and check the box "Use Ctrl+Shift+C/V as Copy/Paste".

## Install Azure CLI

- [Install the Azure cli on linux](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest). You can also install via either of these methods as well:
  - `curl -L https://aka.ms/InstallAzureCli | bash`
  - via [chocolatey](https://chocolatey.org) by executing `choco install azure-cli`
