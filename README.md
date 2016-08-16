Appcelerator Titanium Mobile Module Project
===========================================

This Module  is to customize WebView's UserAgent (iOS).


MODULE NAMING
-------------

com.abada.useragent


GET STARTED
------------

0. Download this module Project
1. Copy `com.abada.useragent-iphone-1.0.0.zip` file into the folder of your Titanium Project
2. If you build the titanium project, the zip will be unziped and placed to you module folder


DOCUMENTATION FOR YOUR MODULE
-----------------------------

Register your module with your application by editing `tiapp.xml` and adding your module.
Example:

	<modules>
		<module version="1.0.0">com.abada,useragent</module>
	</modules>


TEST HARNESS EXAMPLE FOR YOUR MODULE
------------------------------------

The `example` directory contains a skeleton application test harness that can be
used for testing and providing an example of usage to the users of your module.


BUILDING YOUR MODULE
--------------------

var useragent = require('com.abada.useragent');
useragent.setWebViewUserAgent('WHAT YOU WANT');

INSTALL YOUR MODULE
-------------------

Mac OS X
--------
Copy the distribution zip file into the `~/Library/Application Support/Titanium` folder

Linux
-----
Copy the distribution zip file into the `~/.titanium` folder

Windows
-------
Copy the distribution zip file into the `C:\ProgramData\Titanium` folder


REGISTER YOUR MODULE
--------------------

Register your module with your application by editing `tiapp.xml` and adding your module.
Example:

<modules>
	<module version="0.1">com.abada.useragent</module>
</modules>

When you run your project, the compiler will combine your module along with its dependencies
and assets into the application.


###NOTICE

**You must set your UserAgent String before showing a Ti.UI.WebView object at your Window.**

Cheers!
