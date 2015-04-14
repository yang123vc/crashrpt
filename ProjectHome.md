**`CrashRpt`** is a free open-source library designed for intercepting exceptions in your C++ program, collecting technical information about the crash and sending error reports over the Internet to software vendor.

## Download ##

The latest version: **crashrpt v1.4.2** ([What's New](http://crashrpt.sourceforge.net/Changelog.txt)) Release date:  8 April 2013

[![](http://crashrpt.googlecode.com/svn/wiki/img/CrashRpt/download.png)](http://crashrpt.googlecode.com/files/CrashRpt_v.1.4.2_r1609.7z)

You can open the downloaded archive using [7-Zip](http://www.7-zip.org/) program.

## Support ##

**[Online Documentation](http://crashrpt.sourceforge.net/)** - `CrashRpt` user manual & API reference

**[Forum](https://groups.google.com/forum/#!forum/crashrpt)** - Ask a `CrashRpt` related question

## Features ##

**An example of user interface** MoreScreenshots

![http://crashrpt.googlecode.com/svn/wiki/img/CrashRpt/maindlg.png](http://crashrpt.googlecode.com/svn/wiki/img/CrashRpt/maindlg.png)

  * Supports Visual C++ 2005, 2008, 2010, 2012 and Visual C++ Express<sup>1</sup>. Can be compiled   for 32-bit and 64-bit platforms.

  * Works in Windows XP/2003/Vista, Windows 7 and Windows 8.

  * Handles exceptions in the main thread and/or in all worker threads of your user-mode program: SEH exceptions, unhandled C++ typed exceptions, signals and CRT errors.

  * Generates error report including crash minidump, extensible crash description XML, application-defined files, desktop screenshots and screen capture videos.

  * Presents UI allowing user to review the crash report. Supports Privacy Policy definition.

  * Can display its UI using different languages, which makes it even more suitable for multi-lingual applications.

  * Sends error reports in background after user has provided his/her consent. HTTP (or HTTPS), SMTP and Simple MAPI are available methods to transfer the report data over the Internet.

  * Automatically restarts the application on crash (if user provides his/her consent).

  * Small overhead to the size of the software - only 1,9 Mb of additional files: `CrashRpt.dll`, `CrashSender.exe`, `crashrpt_lang.ini`, `dbghelp.dll`.

  * Automates error report processing on developer's side using command-line tool. This option becomes helpful when you receive lots of error reports from users of your software. Provides API for accessing error report properties and files programmatically.

<sup>1)</sup> Windows Driver Kit or Microsoft Platform SDK for Windows Server 2003 is required to compile in Visual C++ Express.