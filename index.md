---
title: Release Note
weight: 310
redirect_from: /Release%20note/_index.en.md
disableToc: true
---

# Open eVision 24.10

## New Features

### The new Open eVision Studio (preview)
![New Open eVision Studio](https://documentation.euresys.com/Products/OPEN_EVISION/OPEN_EVISION/en-us/Content/Resources/Images/02_What_s_New/RN241极失]
-
The current version is a preview, more tools and features will be added in forthcoming releases of Open eVision

### EasyBarCode2
- The EasyBarCode2 algorithm to detect bar codes in images has been modified:
  - minModuleSize is not used anymore, so you do not need to perform any setup to read small bar codes in large images
  - On average, the reading is now twice faster. Unfortunately, some edge case reads and failed readings take more time than before
- The EBarCodeReader now supports the ITF-14 standard
- The EBarCodeReader did not restore the correct symbologies when reading serialized files from older versions. This has been corrected
  - Files created before release 22.12 still show the issue with later versions

### Easy3D
- Use the new class EZMapLeveler to perform the leveling of EZMaps
![EZMapLeveler](https://documentation.euresys.com/Products/OPEN_EVISION/OPEN_EVISION/en-us/Content/Resources/Images/02_What_s_New/RN2410_Easy3D_EZMapLeveler_thumb_200_0.png)

### EasyImage
- High Dynamic Range image fusion:
  - The class EasyImage.EHDRFusion provides methods to merge several input images captured with different exposures into a single image, while conserving the details and the visual quality of the source images
  - For the merging operation, select between the Mertens, Debevec and Robertson algorithms
  - For the tone mapping operation, select between the Linear, Drago and Mantiuk algorithms
![HDR Fusion](https://documentation.euresys.com/Products/OPEN_EVISION/OPEN_EVISION/en-us/Content/Resources/Images/02_What_s_New/RN2410_EasyImage_HDR_thumb_200_0.png)
- New deinterlace and interlace methods
- AdaptiveThreshold support for EImageBW16 and ERegion
- New resize method

### EasyColor
- New YCbCr color system

### Deep Learning tools
- "Engine setup data" serialization

## Improvements
- Updated Euresys logo
- Deep Learning Studio improvements
- EasyQRCode and EasyMatrixCode performance improvements
- Various bug fixes and enhancements

## Solved Issues
- Fixed multiple issues in Deep Learning tools, Studio, and various modules
- Resolved memory leaks and crashes
- Corrected algorithm behaviors

## Breaking Changes
- EasyImage histogram analysis changes
- Easy3D median filter behavior
- EasyQRCode drawing reference

## Changes
- Linux system requirements updated
- Deep Learning tools internal changes
- EasyObject ECodedImage2 enhancements
- Qt and Python samples improvements

## Deprecations
- Deprecated methods in EImageEncoder and related classes
