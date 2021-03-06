---
title: "Android Wear"
description: "Building apps for Android wearable devices."
ms.topic: article
ms.prod: xamarin
ms.assetid: 3BE4A128-2D88-4500-9E48-20375EA99A49
ms.technology: xamarin-android
author: mgmclemore
ms.author: mamcle
ms.date: 02/16/2018
---

# Android Wear

Android Wear is a version of Android that is designed for wearable
devices such as smart watches. This section includes instructions on
how to install and configure tools required for Wear development, a
step-by-step walkthrough for creating your first Wear device, and a
list of samples that you can refer to for creating your own Wear apps.

##  [Getting Started](~/android/wear/get-started/index.md)

Introduces Android Wear, describes how to install and configure your
computer for Wear development, and provides steps to help you create
and run your first Android Wear app on an emulator or Wear device.

##  [User Interface](~/android/wear/user-interface/index.md)

Explains Android Wear-specific controls and provides links to 
samples that demonstrate how to use these controls.

##  [Platform Features](~/android/wear/platform/index.md)

Documents in this section cover features specific to Android Wear. Here
you'll find a topic that describes how to create a WatchFace.

##  [Screen Sizes](~/android/wear/screen-sizes.md)

Preview and optimize your user interface for the available screen sizes.

##  [Deployment & Testing](~/android/wear/deploy-test/index.md)

Explains how to deploy your Android Wear app to an Android
Wear device or to Android emulator configured for Wear. It also
includes debugging tips and information for how to set up a Bluetooth
connection between your development computer and an Android device.



## Samples

You can find a number of 
[samples](https://developer.xamarin.com/samples/android/Android%20Wear/) using Android Wear (or go 
directly to 
[github](https://github.com/xamarin/monodroid-samples/tree/master/wear)). 

<table align="center" border="1" cellpadding="1" cellspacing="1">
  <thead>
      <th>
          <strong>Sample</strong>
      </th>
      <th>
          <strong>Description</strong>
      </th>
      <th>
          <strong>Screenshot</strong>
      </th>
  </thead>
  <tbody>
  <tr>
      <td valign="top">
          <a href="https://developer.xamarin.com/samples/SkeletonWear/">SkeletonWear</a>
      </td>
      <td valign="top">
          A simple example of the basics of wearable projects,
          including GridViewPager and interactive notifications.
      </td>
      <td>
          <img src="Images/skeleton.png" class="tableimg">
      </td>
  </tr>
  <tr>
      <td valign="top">
          <a href="https://developer.xamarin.com/samples/WatchViewStub/">WatchViewStub</a>
      </td>
      <td valign="top">
          A simple demo of the WatchViewStub control that detects
          screen shape and automatically loads the correct layout.
          See how WatchViewStub works in the
          <b>Resources/layout/main_actvity.xml</b> layout.
      </td>
      <td>
          <img src="Images/watchview.png" class="tableimg">
      </td>
  </tr>
  <tr>
      <td valign="top">
          <a href="https://developer.xamarin.com/samples/RecipeAssistant/">RecipeAssistant</a>
      </td>
      <td valign="top">
          Demonstration of Wear notification pages, in the form of
          recipe steps. Notifications are created in <b>RecipeService.cs</b>.
      </td>
      <td>
          <img src="Images/recipeassist.png" class="tableimg">
      </td>
  </tr>
  <tr>
      <td valign="top">
          <a href="https://developer.xamarin.com/samples/ElizaChat/">ElizaChat</a>
      </td>
      <td valign="top">
          Fun sample of interacting with a "personal assistant"
          called Eliza, using Wear interactive notifications to
          create a conversation using canned responses.
      </td>
      <td>
          <img src="Images/eliza.png" class="tableimg">
      </td>
  </tr>
  <tr>
      <td valign="top">
          <a href="https://developer.xamarin.com/samples/GridViewPager/">GridViewPager</a>
      </td>
      <td valign="top">
          GridViewPager implements the 2D navigation pattern, where
          the user swipes vertically and then horizontally to navigate
          through options and content.
      </td>
      <td>
          <img src="Images/gridviewpager.png" class="tableimg">
      </td>
  </tr>
  <tr>
      <td valign="top">
          <a href="https://developer.xamarin.com/samples/monodroid/wear/WatchFace">WatchFace</a>
      </td>
      <td valign="top">
          <b>WatchFace</b> is a custom watch face with analog-style hour,
          minute, and second hands. This sample demonstrates how
          to create a watch face service that draws the
          current time and handles ambient mode and visibility 
          change events. It includes a broadcast receiver that listens
          for time zone changes and automatically updates the time
          accordingly.
      </td>
      <td>
          <img src="Images/watchface.png" class="tableimg">
      </td>
  </tr>
  </tbody>
</table>

##  Videos

Check out these video links that discuss Xamarin.Android with Wear support.

<table align="center" border="0" cellpadding="1" cellspacing="1">
	<tr>
		<td>
		<a href="http://blog.xamarin.com/webinar-recording-android-l-and-so-much-more/"><img src="Images/video-android-l.png" border="0" /></td>
		<td><a href="http://blog.xamarin.com/webinar-recording-android-l-and-so-much-more/">Android L and So Much More</a>
		<br />
		The Android L Developer Preview introduced a plethora of new APIs
		for developers to take advantage of, including Material Design,
		notifications, and new animations, to name a few.</td>
	</tr>
	<tr>
		<td>
		<a href="https://www.youtube.com/watch?v=80H8tXByZQc"><img src="Images/video-eyes-ears.png" border="0" /></td>
		<td><a href="https://www.youtube.com/watch?v=80H8tXByZQc">C# is in my Ears and in my Eyes: Google Glass and Android Wear</a>
		<br />
		Wearable computing might seem like something from the future
		(or an Inspector Gadget episode), but many people are already
		embracing the future today! C# developers know this and already
		have the tools and skills to harness the power of wearable devices (from Evolve 2014).</td>
	</tr>
	<tr>
		<td>
		<a href="https://www.youtube.com/watch?v=Gpqc2XZIQfU"><img src="Images/video-whats-new.png" border="0" /></td>
		<td><a href="https://www.youtube.com/watch?v=Gpqc2XZIQfU">What's new in Xamarin.Android</a>
		<br />
		<i>Android L, Android Wear, Android TV, Android Auto, Material Design, and ART;
		what does this mean to you as a Xamarin developer?</i> from Evolve 2014.</td>
	</tr>
</table>


<!--

March 18
http://blog.xamarin.com/android-wear/

August 14
http://blog.xamarin.com/android-l-developer-preview-android-wear-support/

August 27
http://blog.xamarin.com/tips-for-your-first-android-wear-app/

Watch Face
https://github.com/Redth/Xamarin.Wear.WatchFace
-->
