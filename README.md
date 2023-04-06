
![Windows Server Management Tools - Banner](https://github.com/TheFlightSims/windowsserver-mgmttools/blob/master/docs_image.png?raw=true)
# The Repository

***This repository presents to you a collection of server management tools for various purposes:***
- *Mass administration of Active Directory environment*
- *Manage multiple databases (e.g., MySQL, Microsoft SQL Server, etc.)*
- *Backup all Hyper-V virtual machines*
- *Clean up temporary NVIDIA GPU drivers*
- *Remote install for MSI installer*
- *Passthrough physical device into the virtual machine*
- *Activation services for server*
- *Manage updates for servers and clients*

For better understanding, you can see the [wiki page](https://github.com/TheFlightSims/windowsserver-mgmttools/wiki).

# Use and install
***To run and use applications in this project, make sure your computer is installed with features:***
 - dotNET 2.1, dotNET 3.5, dotNET 4.8. These are built-in features and can be enabled. You can see the document [here](https://learn.microsoft.com/en-us/dotnet/framework/install/dotnet-35-windows)
 - Modern applications require .NET 6.0.11 and .NET 7.0. You can download in [there](https://dotnet.microsoft.com/en-us/download)
 - Visual C++ 2015 and all versions later. You can download in [here](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)

# The Files and Folders

***The repo consists of three parts***
 - **[!bin!](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/!bin!):** store compiled source codes (if the solution source needs to comply)
 - **[!docs & ref!](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/!docs%20&%20ref!):** store documents and Visual Studio configurations. We use **Visual Studio 2022 (17.5 LTSC)** to edit the source codes and [Advanced Installer](https://www.advancedinstaller.com/) to create installer.
 - **[!pub!](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/!pub!):** store complied and published packages. We will update it monthly, if possible.
 - **[!makevs!](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/!makevs!):** Make Visual Studio offline layout. It is recommended to fully editing in this project.
 - **.vs:**: includes Visual Studio source files.
 - **winser-mgmttools.sln:** solution files, contains all required paths for all projects.
 - **The rest of the files and folders:** Project files and folders.

# Contributing & Feedback

## Contributing
To fully edit this repository, run to download all layouts for the Visual Studio 2022 that located in **[!makevs!](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/!makevs!):**.
Also, you may need [Advanced Installer](https://www.advancedinstaller.com/) to create installer. These are all located in folder [!bin](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/!bin!) in each project.

Otherwise, you can do other ways:
 - [Review Wiki Page](https://github.com/TheFlightSims/windowsserver-mgmttools/wiki)
 - Submit bugs and feature requests in [GitHub](https://github.com/TheFlightSims/windowsserver-mgmttools/issues) or our [Discord server](https://discord.gg/VdbJAHKhuW)
 - [Review source codes](https://github.com/TheFlightSims/windowsserver-mgmttools)
 - [Review and commit pull requests](https://github.com/TheFlightSims/windowsserver-mgmttools/pulls)

*Note that the Visual Studio workload can be really heavy: requires around 20-40Gb for all required libraries*

## Feedback
To feedback this repository, go to [**feedback**](https://github.com/TheFlightSims/windowsserver-mgmttools/issues) or **[join our Discord server](https://discord.gg/VdbJAHKhuW)**

# License & Original Contributors
## License 
This repo uses [**GNU GPL 3.0**](https://www.gnu.org/licenses/gpl-3.0.en.html) and [**MIT License**](https://opensource.org/licenses/MIT) for all contributors to have free, no limit to 
- Use (for both private and commercial uses)
- Modify (including edit the source files and compile/decompile) 
- Distribution without permission directly from TheFlightSims, except emergency revokes permission. In that case, this repo will be moved to private and cannot be accessed by the public.

## Original Contributors
|Usage|Name|Contributors|Folks from|
|--|--|--|--|
|IIS Management|[Check IIS](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/check-iis)|@[TheFlyingCorpse](https://github.com/TheFlyingCorpse), TheFlightSims staff|https://github.com/TheFlyingCorpse/check_iis
|Database Management|[Database Manager](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/database-manager)|@[dependabot[bot]](https://github.com/apps/dependabot), @[victor-wiki](https://github.com/victor-wiki), TheFlightSims staff|https://github.com/victor-wiki/DatabaseManager|
|VM Management|[Hyper-V Backup](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/hyperv-backup)|@[pablopioli](https://github.com/pablopioli), @[schtritoff](https://github.com/schtritoff), TheFlightSims staff|https://github.com/ColiseoSoftware/hypervbackup|
|VM Management|[Hyper-V Passthrough Device](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/hyperv-passthrough)|@[chanket](https://github.com/chanket), TheFlightSims staff|https://github.com/chanket/DDA|
|Computer Management|[NVIDIA Driver Cleaner](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/nvidia-driver-cleaner)|@[ataberkylmz](https://github.com/ataberkylmz), TheFlightSims staff|https://github.com/ataberkylmz/NvidiaDriverCleaner|
|Debugging|[PDB Downloader](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/PDB-Downloader)|@[rajkumar-rangaraj](https://github.com/rajkumar-rangaraj), TheFlightSims staff|https://github.com/rajkumar-rangaraj/PDB-Downloader
|Computer Management|[Port Scanner](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/port-scanner)|@[IceMoonHSV](https://github.com/IceMoonHSV), TheFlightSims staff|https://github.com/IceMoonHSV/PortScanner|
|Computer Management|[Remote MSI Manager](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/remote-msi-manager)|@[DCourtel](https://github.com/DCourtel), TheFlightSims staff|https://github.com/DCourtel/Remote_MSI_Manager|
|Volume Activation|[vlmcsd beta](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/vlmcsd-beta)|@[Wind4](https://github.com/Wind4/vlmcsd), @[kkkgo](https://github.com/kkkgo), @[HarukaMa](https://github.com/HarukaMa), @[Hotbird64](https://forums.mydigitallife.net/members/hotbird64.333466/), @[Nang](https://jike.info/user/nang), TheFlightSims staff, @[Linus Torvalds](https://github.com/torvalds), Erik Andersen, Waldemar Brodkorb, Denys Vlasenko, H. Peter Anvin|https://github.com/kkkgo/vlmcsd|
|Group Policy|[GPO Checker](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/gpo-checker)|@[georgeatgrayson](https://github.com/georgeatgrayson), TheFlightSims staff|https://github.com/georgeatgrayson/Windows-GPO-Security-Checker|
|Debugging|[PDB Downloader](https://github.com/TheFlightSims/windowsserver-mgmttools/tree/master/PDB-Downloader)|@[rajkumar-rangaraj](https://github.com/rajkumar-rangaraj), TheFlightSims staff|https://github.com/rajkumar-rangaraj/PDB-Downloader|
