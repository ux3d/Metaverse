[![](glTF.png)](https://github.com/KhronosGroup/glTF/tree/master/specification/2.0)

# Gestaltor in the Metaverse
[Gestaltor](https://gestaltor.store/) is the first visual [glTF](https://www.khronos.org/gltf/) editor to directly modify `.gltf` and `.glb` files. One of the [main features](https://ux3d.io/gestaltor) of this 3D editor and stager is, that a glTF is loaded and saved. This means, that any information and configuration inside the glTF during editing is preserved.  
  
glTF is the 3D format of choice for the [Metaverse](https://www.mckinsey.com/business-functions/growth-marketing-and-sales/our-insights/value-creation-in-the-metaverse), [Web3](https://en.wikipedia.org/wiki/Web3), [3D Commerce](https://www.khronos.org/3dcommerce/) and [simplifies the digital twin exchange](https://venturebeat.com/ai/10-digital-twin-trends-for-2023/). glTF 2.0 became an [ISO standard](https://www.iso.org/standard/83990.html) in July 2022.
  
Following assets do help to create content using Gestaltor for the following open Metaverse platforms.

## General

Like in the real world, meters are also used as units in virtual space and the Metaverse.  
Following ruler does have a size of 0.1 x 2.0 x 0.1 meters, which does easily allow size comparisson and adjustments.  
In this scene, an avatar from [Ready Player Me](https://readyplayer.me/) and a chair from [wayfair](https://www.aboutwayfair.com/tech-blog/welcome-to-wayfairs-realtime-3d-model-api) are compared:  

![](Ruler_in_Gestaltor.jpg)

* Download [Ruler_2m.glb](General/Ruler_2m.glb)  

In some cases, one does want to add a basic shadow to the scene. This is possible with a simple fake shadow.  
In this scene, the [Boom Box](https://github.com/KhronosGroup/glTF-Sample-Models/tree/master/2.0/BoomBox) and a cupboard from [wayfair](https://www.aboutwayfair.com/tech-blog/welcome-to-wayfairs-realtime-3d-model-api) are used. The shadow asset is arranged in such a way, that the Boom Box looks like it is positioned on the cupboard (screenshot taken from Gestaltor):  

![](Shadow_screenshot.jpg)

* Download [Shadow.glb](General/Shadow.glb)  

Sometimes, one does need a [Color Checker](https://en.wikipedia.org/wiki/ColorChecker). Here we go:  

![](ColorChecker.jpg)

* Download [ColorChecker.glb](General/ColorChecker.glb)  

## AltspaceVR
In [AltspaceVR](https://altvr.com/) one can upload and use glb assets. All polygons in the scene should [not exceed](https://docs.microsoft.com/windows/mixed-reality/altspace-vr/world-building/importing-models) the 100000 limit.  

The world units are in meters, so any provided glTF assets in meters can be used.

AltspaceVR is using in many cases only materials without textures. The following glTF contains several dielectric, rough materials based on this [color table](https://www.rapidtables.com/web/color/RGB_Color.html).

![](AltspaceVR_in_Gestaltor.jpg)

* Download [Colors.glb](AltspaceVR/Colors.glb)  

## Decentraland
In [Decentraland](https://decentraland.org/) it is possible to add own 3D models using glTF.  

### LAND
3D models can be placed on a [LAND](https://docs.decentraland.org/decentraland/faq/#what-is-land) estate. A LAND estate does have a dimension of [16m x 16m](https://docs.decentraland.org/decentraland/faq/#how-large-is-a-tile-of-land).  
The following asset does have a dimension of 16m x 16m in glTF plus a checkerboard texture of 1m x 1m:

![](LAND_in_Gestaltor.jpg)

* Download [1x1LAND.glb](Decentraland/1x1LAND.glb)  

## Hubs
Using [spoke](https://hubs.mozilla.com/spoke) it is possible to upload and download 3D models to [Hubs](https://hubs.mozilla.com/) using glTF.  
In spoke and Hubs, the virtual space is segmented in several 10m x 10m areas.

![](Hubs_in_Gestaltor.jpg)

* Download [10x10m_Area.glb](Hubs/10x10m_Area.glb)  

## Oculus Home
In [Oculus Home](https://creator.oculus.com/blog/introducing-oculus-home-user-created-spaces/) the navigation area is a 250m cube and the visible area a 1000m cube.  
This asset includes a 250m x 250m floor plus visual hints for the navigation and visible area:

![](Oculus_Home_in_Gestaltor.jpg)

* Download [OculusHome.glb](OculusHome/OculusHome.glb)  

## Somnium Space
In [Somnium Space](https://somniumspace.com/) it is possible to upload and download 3D models using glTF.  

### Parcels
3D models can be placed on a Parcel. A Parcel can be of size [S, M and XL](https://somniumspace.medium.com/everything-you-need-to-know-about-buying-land-parcel-in-somnium-space-4f66d18c1a73).  
The following assets are the basement of each Parcel:

![](Parcels_in_Gestaltor.jpg)

* Download [ParcelS.glb](SomniumSpace/ParcelS.glb)  
* Download [ParcelM.glb](SomniumSpace/ParcelM.glb)  
* Download [ParcelXL.glb](SomniumSpace/ParcelXL.glb)  

## Spatial
In [Spatial](https://spatial.io/) it is possible to upload both `.glTF` and `.glb` 3D assets.  
However, they are using a different scaling system and it seems that 2m in other worlds is 1m in their world.

![](Spatial_Ruler_in_Gestaltor.jpg)

* Download [Ruler_Spatial_2m.glb](Spatial/Ruler_Spatial_2m.glb)  

## Substrata
In [Substrata](https://substrata.info/) it is possible to upload 3D models using glTF.  

### Parcels
3D models can be placed on a Parcel in Substrata. A Parcel does have a size of 20m x 20m:

![](Substrata_parcels_in_Gestaltor.jpg)

* Download [20x20m_Parcel.glb](Substrata/20x20m_Parcel.glb)  
