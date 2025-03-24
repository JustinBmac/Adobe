# Adobe
This is a collection of scripts and pkgs that I have made and used in managing Abobe Creative Cloud within an Enterprise Environment. This ranges from individual uinstallers for different Abode CC applications as well as a full suite uninstaller for all Adobe CC applications. 


# Adobe Uninstaller PKG
This is a package made using Jamf Composer that takes the AdobeUninstaller Unix Executable File and adds it into the User\Shared Folder. After it adds it to the Shared user folder its runs a post install bash script that navigates to the shared folder and then runs the AdobeUninstaller to remove all Adobe Creative Cloud applications on a macOS device and then deletes the AdobeUinstaller from the Shared folder. Please see the Wiki page for this PKG for more information about the bash script. This package is useful to have when you need to uninstall Adobe Creative Cloud from large lab deployments.
