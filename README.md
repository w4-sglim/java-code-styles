Java Code Styles
================

IntelliJ IDEA code style settings for Square's Java and Android projects.


Purpose of the fork
-------------------

Kotlin has extension like data binding by default.
To use this feature, we need to import too many classes for UI elemnt id in "kotlinx.android.synthetic" package.
So I add this package to use star imports.
It will not be confusing where the class from, while the UI element id has camel case.


Installation
------------

 * On Unix, run the `install.sh` script. Windows users should use `install.bat` instead.
 * Restart IntelliJ if it's running.
 * Open IntelliJ Project Settings -> Code Styles, change the code style for the
   project to the one you want.


License
-------

[![Public domain](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/legalcode)
