
WinRS Agent Install - Overview
==============================

# Overview


### Overview




The WinRS Agent Install plug-in installs agents on Windows systems through WinRS. It contains a single step, which installs an agent. This step is equivalent to installing an agent from the server with the WinRS option.

### Compatibility

This plug-in requires IBM UrbanCode Deploy version 6.1 or later.

This plug-in works with versions of Windows that have Windows PowerShell, including Windows Server 2003, 2008, and 2012.

The step can run on any Windows operating system. However, to install an agent on the target system, that target system must be configured as described in [Installing agents on Windows through WinRS](https://www.ibm.com/docs/en/urbancode-deploy/7.2.3?topic=agents-installing-windows-through-winrs) in the product documentation.

### **Installation**

No special steps are required for installation. See [Installing plug-ins in UrbanCode Deploy](https://community.ibm.com/community/user/wasdevops/blogs/laurel-dickson-bull1/2022/06/13/install-plugins "Installing plug-ins in UrbanCode Deploy").

### Release Notes

#### Version 10

Plugin updates to install Web agents

#### Version 9

Compatibility update to match 6.2.7.2+ UCD server.

#### Version 8

#### Version 7

Plugin now obfuscates WinRS service password.

#### Version 6

Fixes APAR PI57417. Plug-in now checks the agent settings for acceptance of self signed certificates.


|Back to ...||Latest Version|WinRS Agent Install |||
| :---: | :---: | :---: | :---: | :---: | :---: |
|[All Plugins](../../index.md)|[Deploy Plugins](../README.md)|[12.1131558](https://raw.githubusercontent.com/UrbanCode/IBM-UCD-PLUGINS/main/files/WinRSAgentInstall/ucd-WinRSAgentInstall-12.1131558.zip)|[Readme](README.md)|[Steps](steps.md)|[Downloads](downloads.md)|
