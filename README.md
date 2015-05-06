ALPS VR
========

#### Unity framework for mobile virtual reality apps ####

The aim of the ALPS VR project is to create a lightweight Unity framework to help developers publish virtual reality apps for every mobile based viewers. Framework features include:
*Side-by-side rendering
*Barrel distortion
*Chromatic aberration correction
*Responsive head-tracking
*Head gesture navigation system
*Built-in configurations for supported devices

[Official website](http://alpsvr.com)

### Usage ###

Download the [Unity package](https://github.com/shwars/ALPS-VR/blob/master/Package/alpsvr-wp.unitypackage) and import it into your Unity project.

Drag and drop the ALPSCamera prefab (ALPS/Prefabs/ALPSCamera.prefab) into your scene.

If you want to see the demo, download [complete Unity package with demo](https://github.com/shwars/ALPS-VR/blob/master/Package/alpsvr-wp-demo.unitypackage), import into empty project, and open the Demo.scene.

![alt tag](/Screenshots/ALPSVR_Preview.JPG)

### Requirements ###
* Unity 5 or higher (might require some modifications if using version below)
* To deploy on Android:
  * Unity Pro for Android
  * Android SDK 3.2 or higher
* To deploy to Windows Phone 8.1
  * Visual Studio 2013 Update 4 or higher with the Windows SDK
  * Use "Windows Store" Build Option in Unity and chose Windows Phone 8.1 as target

You can still use ALPS VR without a Pro license but you will only benefit from side-by-side rendering and head-tracking features.
