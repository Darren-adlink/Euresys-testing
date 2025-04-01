---
title: Open eVision 24.10 Release Note
weight: 310
disableToc: true
---

## New Features

### The new Open eVision Studio (preview)
- Preview of the new Open eVision Studio
- Features:
  - Complex processing sequences using tool graphs
  - Tool Catalog with search capabilities
  - Sample Catalog with preconfigured projects
  - Code generation in C++ and C#
  - Support for main image formats
  - Full support of regions of interest
  - Connection to live image sources
  - Benchmarking capabilities
  - Free to use
  - Compatible with Windows and Linux

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
