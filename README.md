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




var useragent = require('com.abada.useragent');

useragent.setWebViewUserAgent('WHAT YOU WANT');

 
###NOTICE

**You must set your UserAgent String before showing a Ti.UI.WebView object at your Window.**

Cheers!
