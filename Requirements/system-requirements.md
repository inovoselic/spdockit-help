This article lists the minimum hardware and software requirements for the installation of the SPDocKit.

### Requirements

*   The product needs to be installed (or started) on a **SharePoint 2016**, **SharePoint 2013** or **SharePoint 2010** Server
    *   For SharePoint 2013 & 2010: SharePoint Foundation, Standard and Enterprise are supported.
    *   You can install the product on WFE, Application server, Index or any other server in the farm.
    *   User must have [proper privileges](http://www.spdockit.com/support/help/requirements/spdockit-user-permission-requirements/ "SPDocKit User Permission Requirements") to run the application.
*   Software
    *   For SharePoint 2016: Windows 2012 R2 or Windows Server 2016
    *   For SharePoint 2013: Windows 2012 or Windows 2008 R2
    *   For SharePoint 2010: Windows 2012 or Windows 2008 R2
    *   On Windows 2008 you will need to download [Windows PowerShell Snap-In 1.0](http://www.iis.net/download/powershell) to fully extract information about IIS Settings
    *   SQL 2008 or better is supported
    *   **Microsoft .NET Framework 3.5 SP1** for SharePoint 2010, **Microsoft .NET Framework 4.0** for SharePoint 2013 and SharePoint 2016.
*   Hardware:
    *   CPU - any standard server CPU
    *   Memory - up to 200 MB RAM while idle, up to 1GB RAM during the data load
    *   Disk - 200 MB disk space

### Running on a workstation

The application can be installed on a workstation with **Windows 10**, **Windows 8** or **Windows 7** operating system, but you will not be able to load new SharePoint farm settings, but only connect to an existing SPDocKit database and open already saved farm settings. <span class="TextRun SCX218498858" xml:lang="HR-HR"><span class="NormalTextRun SCX218498858">From the version 5.2., SPDocKit installed on a workstation also supports connecting to any **SharePoint 2010**, **SharePoint 2013, SharePoint 2016** or **SharePoint Online** site and real-time </span></span><span class="TextRun SCX218498858" xml:lang="HR-HR"><span class="NormalTextRun SCX218498858">viewing and management of permissions.</span></span><span class="EOP SCX218498858"> </span>

*   Hardware:
    *   CPU - any Windows 7, Windows 8 or Windows 10 capable CPU
    *   Memory - up to 200 MB RAM while idle
    *   Disk - 100 MB disk space

### Running SPDocKit Event Collection Service

From the version 6.2., SPDocKit offers the new installation of **SPDocKit Event Collection Service**. It is used for real-time collection and searching of the ULS logs from **SharePoint 2010, SharePoint 2013, or SharePoint 2016**. SPDocKit Event Collection Service can be installed on any server with Windows Server 2008 or better. It is recommended to install it on a server that is not a part of the SharePoint farm to minimize its impact on the farm. **Please note** that we advise you **not** to install the SPDocKit Event Collection Service on a server running SharePoint 2010, as .net 4.5 is required.

*   Software
    *   Windows Server 2008 or better
    *   Microsoft .NET Framework 4.5
*   Hardware:
    *   CPU – any standard server CPU
    *   Memory – up to 500 MB RAM
    *   Installation – 100 MB disk space
    *   Index – 200GB disk space required to store the index containing all the ULS logs. It is recommended to change the index location to a secondary drive.

### Learn more

*   [Installation Guide](http://www.spdockit.com/support/help/installation/installation-guide/ "Installation Guide")
*   [How to create Farm Documentation](http://www.spdockit.com/support/help/how-to/farm-documentation/create-farm-documentation/ "Create Farm Documentation")
*   [How to compare SharePoint Farms](http://www.spdockit.com/support/help/how-to/compare-wizard/compare-sharepoint-farms/ "Compare SharePoint Farms")
*   [How to configure Automatic Snapshots](http://www.spdockit.com/support/help/how-to/sharepoint-farm-snapshots/configure-automatic-snapshots/ "Configure Automatic Snapshots")
