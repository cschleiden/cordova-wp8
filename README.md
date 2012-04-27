Cordova for WP7 Mango
===

Cordova WP7 is a .net application library that lets you create Cordova applications targeting WP7 Mango devices.
Cordova based applications are, at the core, an application written with web technology: HTML, CSS and JavaScript.

Requires
---

- Windows Phone SDK 7.1 [http://create.msdn.com/en-us/home/getting_started]


Getting Started
---

- copy the file CordovaStarter-1.6.0.zip to the folder : \My Documents\Visual Studio 2010\Templates\ProjectTemplates\
 - if you have just installed VisualStudio, you should launch it once to create this folder
 - if you prefer, you may add the project instead to the "Silverlight for Windows Phone" subfolder of "Visual C#".  This is up to you, and only affects where the project template is shown when creating a new project. Also, You may need to create this folder.
- Launch Visual Studio 2010 and select to create a new project
 - CordovaStarter should be listed as an option, give your new project a name
  - Note: The description will let you know the version of Cordova you are targetting, if you have multiple templates.
 - If you do not see it, you may have to select the top level 'Visual C#' to see it
- Build and Run it!

Important!!!
---

When you add or remove files/folders in the www folder you will need to do the following

- ensure the new item is included in the project ( Content ) This includes ALL images/css/html/js/* and anything that you want available at runtime.
- Do not modify the CordovaSourceDictionary.xml file which is included in the project, it is auto-generated for you when you build.

Known Issues
---

You cannot deploy (and thus debug) the framework if you want to make use
of various Media features by default (like taking a picture, capturing
audio, etc.). This is because the Zune software
locks the media library and somehow that affects your device. For a
workaround, please check out this [MSDN blog article](http://blogs.msdn.com/b/jaimer/archive/2010/11/03/tips-for-debugging-wp7-media-apps-with-wpconnect.aspx).


BUGS?
-----
File them at Apache Incubator 
https://issues.apache.org/jira/browse/CB


Further Reading
---

- [http://docs.phonegap.com](http://docs.phonegap.com)
- [http://wiki.phonegap.com](http://wiki.phonegap.com)
