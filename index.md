### EasyBarCode2
- The EasyBarCode2 algorithm to detect bar codes in images has been modified:
  - minModuleSize is not used anymore, so you do not need to perform any setup to read small bar codes in large images
  - On average, the reading is now twice faster. Unfortunately, some edge case reads and failed readings take more time than before
- The EBarCodeReader now supports the ITF-14 standard
- The EBarCodeReader did not restore the correct symbologies when reading serialized files from older versions. This has been corrected
  - Files created before release 22.12 still show the issue with later versions