 [![Android Arsenal](http://img.shields.io/badge/Android%20Arsenal-MPAndroidChart-blue.svg?style=flat)](http://android-arsenal.com/details/1/741)  [![Release](https://img.shields.io/github/release/PhilJay/MPAndroidChart.svg?label=maven central)](https://jitpack.io/#PhilJay/MPAndroidChart)      [![API](https://img.shields.io/badge/API-8%2B-green.svg?style=flat)](https://android-arsenal.com/api?level=8)

MPAndroidChart
=======

A simple charting library for Android, supporting line-, bar-, scatter-, candlestick-, pie- and radarcharts (spider web), as well as scaling, dragging, selecting and animations. **Supporting Android 2.2 (API level 8)** and upwards.

Remember: *It's all about the looks.*

The **experimental** branch might contain new features that are still buggy. It is recommended to be safe and only make use of the code on the **master** branch.

Forks, pull-requests or any other forms of contribution are **always welcome**.

Donations
-----

If you would like to support this project's further development, the creator of this project or the continuous maintenance of this project, **feel free to donate**. Your donation is highly appreciated.

PayPal

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EGBENAC5XBCKS)

Gittip

<a href="https://www.gittip.com/PhilJay/">
  <img alt="Support via Gittip" src="https://rawgithub.com/twolfson/gittip-badge/0.2.0/dist/gittip.png"/>
</a>

[![Gratipay](http://img.shields.io/gratipay/PhilJay.svg)](https://gratipay.com/PhilJay)

Demo
-----

For a brief overview of the most important features, please download the **PlayStore Demo** [**MPAndroidChart Example.apk**](https://play.google.com/store/apps/details?id=com.xxmassdeveloper.mpchartexample) and try it out. The corresponding code for the demo-application is also included in this repository inside the **MPChartExample folder**.

[![ScreenShot](https://github.com/PhilJay/MPAndroidChart/blob/master/design/video_thumbnail.png)](https://www.youtube.com/watch?v=ufaK_Hd6BpI)

Questions & Issues
-----

If you are having questions or problems, feel free to contact me. Since I would very much like that other users of this library **can also benefit** from your question, I am asking you to contact me via e-mail **only as a last option**. Instead, you should:

 - Make sure you are using the latest version of the library. Check the [**release-section**](https://github.com/PhilJay/MPAndroidChart/releases).
 - Study the [**Documentation-Wiki**](https://github.com/PhilJay/MPAndroidChart/wiki)
 - Search or open questions on [**stackoverflow**](https://stackoverflow.com/search?q=mpandroidchart) with the `mpandroidchart` tag
 - Search [**known issues**](https://github.com/PhilJay/MPAndroidChart/issues) for your problem (open and closed)
 - Create new issues (please **search known issues before**, do not create duplicate issues)

You can let me know via e-mail that you have opened a stackoverflow question so that I might get to answering it more quickly. Thank you.

Features
=======

**Core features:**
 - Scaling on both axes (with touch-gesture, axes separately or pinch-zoom)
 - Dragging / Panning (with touch-gesture)
 - Combined-Charts (line-, bar-, scatter-, candle-data)
 - Finger drawing (draw values into the chart with touch-gesture)
 - Highlighting values (with customizeable popup-views)
 - Multiple / Separate Axes
 - Save chart to SD-Card (as image, or as .txt file)
 - Predefined color templates
 - Legends (generated automatically, customizeable)
 - Customizeable Axes (both x- and y-axis)
 - Animations (build up animations, on both x- and y-axis)
 - Limit lines (providing additional information, maximums, ...)
 - Fully customizeable (paints, typefaces, legends, colors, background, gestures, dashed lines, ...)
 
**Chart types:**

 - **LineChart (with legend, simple design)**
![alt tag](https://raw.github.com/PhilJay/MPChart/master/screenshots/simpledesign_linechart4.png)
 - **LineChart (with legend, simple design)**
![alt tag](https://raw.github.com/PhilJay/MPChart/master/screenshots/simpledesign_linechart3.png)

 - **LineChart (cubic lines)**
![alt tag](https://raw.github.com/PhilJay/MPChart/master/screenshots/cubiclinechart.png)

 - **LineChart (single DataSet)**
![alt tag](https://raw.github.com/PhilJay/MPChart/master/screenshots/linechart.png)

 - **BarChart (with legend, simple design)**

![alt tag](https://raw.github.com/PhilJay/MPChart/master/screenshots/simpledesign_barchart3.png)

 - **BarChart (grouped DataSets)**

![alt tag](https://raw.github.com/PhilJay/MPChart/master/screenshots/groupedbarchart.png)

 - **Horizontal-BarChart**

![alt tag](https://raw.github.com/PhilJay/MPChart/master/screenshots/horizontal_barchart.jpg)


 - **PieChart (with selection, ...)**

![alt tag](https://raw.github.com/PhilJay/MPAndroidChart/master/screenshots/simpledesign_piechart1.png)

 - **ScatterChart** (with squares, triangles, circles, ... and more)

![alt tag](https://raw.github.com/PhilJay/MPAndroidChart/master/screenshots/scatterchart.png)

 - **CandleStickChart** (for financial data)

![alt tag](https://raw.github.com/PhilJay/MPAndroidChart/master/screenshots/candlestickchart.png)

 - **RadarChart** (spider web chart)

![alt tag](https://raw.github.com/PhilJay/MPAndroidChart/master/screenshots/radarchart.png)



Usage
=======

In order to use the library, there are 4 options:

**1. Gradle dependency**

 - 	Add the following to your `build.gradle`:
 ```gradle
repositories {
	    maven { url "https://jitpack.io" }
}

dependencies {
	    compile 'com.github.PhilJay:MPAndroidChart:v2.0.7'
}
```

**2. Maven**
- Add the following to your `pom.xml`:
 ```xml
<repository>
       	<id>jitpack.io</id>
	    <url>https://jitpack.io</url>
</repository>

<dependency>
	    <groupId>com.github.PhilJay</groupId>
	    <artifactId>MPAndroidChart</artifactId>
	    <version>v2.0.7</version>
</dependency>
```

**3. jar file only**
 - Download the [**latest .jar file**](https://github.com/PhilJay/MPAndroidChart/releases) from the releases section
 - Copy the **mpandroidchartlibrary-.jar** file into the `libs` folder of your Android application project
 - Start using the library
	
**4. clone whole repository**
 - Open your **commandline-input** and navigate to your desired destination folder (where you want to put the library)
 - Use the command `git clone https://github.com/PhilJay/MPAndroidChart.git` to download the full MPAndroidChart repository to your computer (this includes the folder of the library project as well as the example project)
 - Import the library folder (`MPChartLib`) into your Eclipse workspace
 - Add it as a reference to your project: [referencing library projects in Eclipse](http://developer.android.com/tools/projects/projects-eclipse.html#ReferencingLibraryProject)

Documentation
=======
For a **detailed documentation**, please have a look at the [**Wiki**](https://github.com/PhilJay/MPAndroidChart/wiki).

Furthermore, you can also rely on the [**MPChartExample**](https://github.com/PhilJay/MPAndroidChart/tree/master/MPChartExample) folder and check out the example code in that project. The corresponding application to the example project is also  [**available in the Google PlayStore**](https://play.google.com/store/apps/details?id=com.xxmassdeveloper.mpchartexample). 

You have a problem that cannot be solved by having a look at the example project and documentation?
No problem, let's talk: [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/PhilJay/MPAndroidChart?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=body_badge)

License
=======
Copyright 2014 Philipp Jahoda

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

**Special thanks** to [mikegr](https://github.com/mikegr) and [ph1lb4](https://github.com/ph1lb4) for their contributions to this project.
