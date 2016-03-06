A Google Code repository to share everything from Processing code snippets to full apps.

## HemeshGui & HemeshGuiLight v0.2 (July 22, 2011) ##

Just a minor update so HemeshGui & HemeshGuiLight can run under the latest version of Processing (1.5.1) and Hemesh (Beta 1.4.9). Planning on a more substantial update, but until then you can use these. The only addition in this version of HemeshGui is the ability to change the size of the Sunflow render output.

## How to install HemeshGui ##

Note: Sunflow 0.7.3 requires Java 1.6

  1. Install the latest version of [Hemesh](http://code.google.com/p/hemesh2010/downloads/list) (1.4.9).
  1. Install the latest version of [controlP5](http://www.sojamo.de/libraries/controlP5/index.html) (0.5.4).
  1. Download & unpack the latest version of HemeshGui (0.2).
  1. Download [SunflowAPIAPI.java](http://sunflowapiapi.googlecode.com/svn/trunk/SunflowAPIAPI/src/com/briansteen/SunflowAPIAPI.java). Place it in the HemeshGui main directory besides “HemeshGui.pde”.
  1. Remove the line **package com.briansteen;** from SunflowAPIAPI.java.
  1. An already compiled version of Sunflow (0.7.3) can be found on [this page](http://www.polyquark.com/opensource/). Download the file “binariesAndSources.zip”. Unpack the contents. Place the file “sunflow-and-janino.jar” in the HemeshGui subdirectory called “code”. You can delete the rest of the contents.
  1. Run. Use the gui to choose a shape and modifiers. Use the gui or keyboard shortcuts to render in Sunflow. Click [here](http://www.flickr.com/photos/amnonp5/5281532572/) to see a fully annotated gui.

## How to install HemeshGuiLight ##

  1. Install the latest version of [Hemesh](http://code.google.com/p/hemesh2010/downloads/list) (1.4.9).
  1. Install the latest version of [controlP5](http://www.sojamo.de/libraries/controlP5/index.html) (0.5.4).
  1. Download & unpack the latest version of HemeshGuiLight (0.2).
  1. Run. Use the gui to choose a shape and modifiers. Click [here](http://www.flickr.com/photos/amnonp5/5281532572/) to see a fully annotated gui.

## SlitsP5 (January 22, 2011) ##

  * **SlitsP5** is a full HD slit-scanning sketch for Processing. It's easy to use and should work regardless of the size and number of input images due to it's batch-processing technique. For some background info and instructions on how to use it properly check out [this blogpost](http://amnonp5.wordpress.com/2011/01/16/eternalism-the-art-of-slitscanning/).

_Some **stills** of the video [Eternalism](http://vimeo.com/18847955) I made with SlitsP5:_

![http://farm6.static.flickr.com/5128/5361044337_a4f8611dc9_m.jpg](http://farm6.static.flickr.com/5128/5361044337_a4f8611dc9_m.jpg)
![http://farm6.static.flickr.com/5130/5361036895_e45e39227a_m.jpg](http://farm6.static.flickr.com/5130/5361036895_e45e39227a_m.jpg)
![http://farm6.static.flickr.com/5005/5361036333_fd660ebea7_m.jpg](http://farm6.static.flickr.com/5005/5361036333_fd660ebea7_m.jpg)

## HemeshGui & HemeshGuiLight (December 22, 2010) ##

  * **HemeshGui** is a graphical user interface I made for the excellent Hemesh library by Frederik Vanhoutte. HemeshGui can render shapes directly in Sunflow via Christopher Warnow's SunflowApiApi.
  * **HemeshGuiLight** is a stripped down version of the regular HemeshGui. It does not have Sunflow rendering capabilities. Thus also less dependencies, making it a little easier to install and run.
  * For some background info check out the post on [CreativeApplications.net](http://www.creativeapplications.net/processing/hemesh-and-hemeshgui-processing/).

_Some **screenshots** of renders I made with HemeshGui (see more on [Flickr](http://www.flickr.com/photos/amnonp5/sets/72157625647108894/)):_

![http://farm6.static.flickr.com/5041/5281109226_fc07044456_m.jpg](http://farm6.static.flickr.com/5041/5281109226_fc07044456_m.jpg) ![http://farm6.static.flickr.com/5003/5280507377_000df101f2_m.jpg](http://farm6.static.flickr.com/5003/5280507377_000df101f2_m.jpg) ![http://farm6.static.flickr.com/5081/5280508087_8176b1b01e_m.jpg](http://farm6.static.flickr.com/5081/5280508087_8176b1b01e_m.jpg)

**If you have any questions, the easiest way to get help is via the [Processing forum](http://forum.processing.org/#Topic/25080000000580064).**