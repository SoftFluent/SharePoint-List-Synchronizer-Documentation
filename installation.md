# Installation


## Visual Installation

* Download the installer: [http://www.softfluent.com/product/sharePoint-list-synchronizer/](http://www.softfluent.com/product/sharePoint-list-synchronizer/)
* Launch the installer "**XlSyncSetup.msi**":

![Install](img/3.1 - install.png)

* Click "**Next**", then read and check "**I accept the terms in the License Agreement**", and hit "**Next**" again

![End-User License Agreement](img/3.2 - license.png)

* Type-in your license key, click on "**Validate Key**", and "**Next**"

![Validate Key](img/3.3 - validate_key.png)

* Select your destination folder

![Destination Folder](img/3.4 - destination_folder.png)

* Click "**Install**" to install the application on your machine

![](img/3.5 - install_end.png)

* The application will be deployed to the destination folder, and upon completion the following form will show up:

![](img/3.6 - finish.png)



## Silent Installation

To install the tool silently you can use the following command line:

`$>msiexec /i XlSyncSetup.msi /qn XLSYNC_KEY=<provided key>`

**Note**: Don't forget to replace the `<provided key>` tag by your actual key.


