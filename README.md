# Checkstyle Configuration
A Checkstyle configuration file for use with any Java code we write.

It is based on the one used by Sun, but with some modifications to make it less strict.

Changes:
* No check for magic numbers
* Private fields and methods don't require documenting
* Max line length upped to 120 characters

## Using in IntelliJ IDEA

First it is necessary to install the Checkstyle plug-in (Checkstyle-IDEA) via `Settings->Plugins` if it is not in the list then click `Browse repositories` and search there. Once installed, the plug-in should appear under `Other Settings->Checkstyle`. 

There are two ways of setting the configuration file:
* Clone this repository and then add a new configuration in `Other Settings->Checkstyle` and point it at the local copy of the file from this repository
* Add a new configuration in `Other Settings->Checkstyle` and point it directly at the raw Github document (`https://raw.githubusercontent.com/ScreamingUdder/checkstyle_configuration/master/check_style.xml`)
