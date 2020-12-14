
<h1 style="line-height:2;"><p align="center"><a href="https://nexplayersdk.com/contact/" target="_blank"><img  src="https://github.com/NexPlayer/NexPlayer_Unity_Plugin/blob/master/resources/Button%20Demo.png" width="23%" height="10%" alt="Unity video player" align="right"></img></a>
<a align=right href="https://nexplayersdk.com" target="_blank"><img src="Source/Images/nexplayer_logo_unreal.png" width="100%" height="100%" ></a>
</p></h1>
</br>

<p align="center">
 <img  src="Source/Gifs/2020_11_17.gif" width="80%" height="80%" alt="Cube Demo" align="center"></img>
</p>

NexPlayer™ for Unreal Engine is a cross-platform video streaming player for Unreal Engine apps that supports video playback across all Android, iOS, and Windows devices. NexPlayer's Unreal video plugin is the only player supporting HLS & DASH streaming on **all Android & iOS devices.**

This repository contains the NexPlayer™ Unreal Engine video streaming player plugin features list as well as an installation guide. If you want to get a copy of our fully working demo, contact us at our [website](https://nexplayersdk.com/).

## Table of Contents

* **[Features](#features)**  

* **[Supported Platforms](#supported-platforms)**

* **[Demo Installation Guide](#demo-installation-guide)**
 
 <br> 


<p align="center">
 <img  src="Source/Gifs/Fortnite_450p.gif" width="80%" height="80%" alt="Cube Demo" align="center"></img>
</p>

<p style="margin-left:auto;margin-right:auto" width="300px" align="left">Our Unreal Engine video plugin allows for the introduction of new exciting levels within your Unreal Engine projects. With our plugin, you can use in-game actions and objects to modify video content.</p>

## Features

The NexPlayer™ for Unreal Engine video streaming player plugin contains the latest features. As our Unreal Engine video plugin is developed entirely in-house, we can implement any desired functionalities. 

We support the following features:

<table>
 <tbody style="text-align:center;">
   <tr>
     <td valign="top" style="text-align:center;">
         <p style="max-width:100%;"><b>Overview</b></p>
     </td>
     <td>
       <ul>
       <li>HLS & DASH Streaming with ABR (Adaptive Bitrate)</li>
       <li>Server-Side & Client-Side Ad Insertion</li>
       <li>Windows Editor (C++ & Blueprint)</li>
       <li>Up to 8K (UHD) Resolution</li>
       <li>Up to 60 Frames Per Second (FPS)</li>
       <li>Rendering Videos on 3D Objects</li>
       </ul>
     </td>
        <tr>
            <td valign="top" style="text-align:center;">
            <p style="max-width:100%;"><b>Basic Features</b></p>
     </td>
     <td>
       <ul>
        <li>Auto Playback</li>
        <li>Open Video Content</li>
        <li>Play / Pause</li>
        <li>Stop</li>
        <li>Close</li>
       </ul>
     </td>
     </tr>
   </tr>
 </tbody>
</table>

## Supported Platforms

| Platform | Supported Graphics APIs | HLS | DASH | Local|
| :-----:| :-----:| :-----:| :-----:| :-----:|
| Android  | OpenGLES2, OpenGLES3 | :heavy_check_mark: | :heavy_check_mark: | :x:|
| iOS | Metal | :heavy_check_mark: | :heavy_check_mark: | :x: |
| Windows | DirectX11 / DirectX12 | :heavy_check_mark: | :heavy_check_mark: | :x:|

## Demo Installation Guide

### 1) Plugin Import

<p> Make sure that your Unreal Engine Project is closed. </p>
<p> Open the project's root directory (the one that includes the .uproject): </p>
<img  src="Source/Images/QuickStart/Step_01.PNG" width="80%" height="80%" alt="Quickstart_Step_1" align="center"></img>

<p> Create a Plugins folder if you don't have it, and unzip the NexPlayerUnreal SDK inside of it: </p>
<img  src="Source/Images/QuickStart/Step_02.PNG" width="80%" height="80%" alt="Quickstart_Step_2" align="center"></img>

<p> Open the  project, and open the Plugins Window:</p>
<img  src="Source/Images/QuickStart/Step_03.png" width="80%" height="80%" alt="Quickstart_Step_3" align="center"></img>

<p> Scroll all the way down to the Project section and under the Video category, select NexPlayerUnreal and check Enabled: </p>
<img  src="Source/Images/QuickStart/Step_04.png" width="80%" height="80%" alt="Quickstart_Step_4" align="center"></img>

<p> A yellow prompt will pop-up asking you to restart the editior, press the Restart Now button: </p>
<img  src="Source/Images/QuickStart/Step_05.png" width="80%" height="80%" alt="Quickstart_Step_5" align="center"></img>

<p> Unreal Engine will compile the plugin and open the project, with the plugin fully imported. </p>

### 2) Video Setup

<p> Add to the scene some basic Actor where the rendering will ocur. It needs to have the uvs properly set. We recomend a Plane or Shape cube (the regular primitive cube won't work because of it's UVs): </p>
<img  src="Source/Images/QuickStart/Step_06.png" width="80%" height="80%" alt="Quickstart_Step_6" align="center"></img><br>

<p> Feel free to scale the Actor to match the desired video screen ratio (generally 16:9).
On the bottom right corner of the Content Browser, press View Options and make sure Show Plugin Content: </p>
<img  src="Source/Images/QuickStart/Step_07.png" width="80%" height="80%" alt="Quickstart_Step_7" align="center"></img><br>

<p> Add the BP_NexPlayer Blueprint located in Content/Blueprints to the scene: </p>
<img  src="Source/Images/QuickStart/Step_08.png" width="80%" height="80%" alt="Quickstart_Step_8" align="center"></img><br>

<p> Add the BP_NexPlayer Blueprint located in Content/Blueprints to the scene: </p>
<img  src="Source/Images/QuickStart/Step_08.png" width="80%" height="80%" alt="Quickstart_Step_8" align="center"></img><br>

<p> Select the bP_NexPlayer Blueprint and Set Stream URL in the Details tab to select the video content url: </p>
<img  src="Source/Images/QuickStart/Step_09.png" width="80%" height="80%" alt="Quickstart_Step_9" align="center"></img><br>

<p> Add one element to Target Actors in the Details tab and reference the Actor you added before: </p>
<img  src="Source/Images/QuickStart/Step_10.png" width="80%" height="80%" alt="Quickstart_Step_10" align="center"></img><br>

<p> Play the scene, and you will see your video rendering on the target Actor: </p>
<img  src="Source/Gifs/GuideTest.gif" width="80%" height="80%" alt="Quickstart_Step_11" align="center"></img><br>

-------------------


## Contact
[support.madrid@nexplayer.com](mailtosupport.madrid@nexplayer.com)
<br>+34 914 184 356
