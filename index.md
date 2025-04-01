---
title: Release Note
weight: 310
redirect_from: /Release%20note/_index.en.md
disableToc: true
---

# Open eVision 24.10

## New Features

### The new Open eVision Studio (preview)
- The new Open eVision Studio is a tool developed to learn, prototype and demonstrate Open eVision.
- It has the following features:
  - Definition of complex processing sequences using a graph of tools (directed acyclic - without loop - graphs are supported)
  - Tool Catalog exposing the available Open eVision tools with search capabilities
  - Sample Catalog exposing preconfigured projects with sample resources (images, point clouds...). The catalog is searchable by tool names, topics, related keywords...
  - Code generation in C++ and C# that matches the graphical project (Python coming soon)
  - Support of the main image formats from Open eVision (EImageBW8, EImageBW16, EImageC24)
  - Full support of regions of interest (EROI) and flexible regions (ERegion)
  - Connection to live image sources using eGrabber Studio
  - Benchmarking: measurement of the real execution time
  - Free (no license, no activation required, free use of the Open eVision libraries within Studio)
  - Compatible with Windows (10 minimum) and Linux, Intel and ARM 64-bit architectures
- The new Open eVision Studio application is included in the full Open eVision installation package and also as an independent installer (only for Windows)
- The current version is a preview, more tools and features will be added in forthcoming releases of Open eVision

![New Open eVision Studio](https://documentation.euresys.com/Products/OPEN_EVISION/OPEN_EVISION/en-us/Content/Resources/Images/02_What_s_New/RN2410_New_Open_eVision_Studio_thumb_200_0.png)

### EasyBarCode2
- Modified algorithm
- ITF-14 standard support
- Serialization issue fixed

### Easy3D
- New EZMapLeveler class

### EasyImage
- High Dynamic Range image fusion
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
