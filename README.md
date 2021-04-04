# Azure SDK for Embedded C

This repository is a cut-out of [azure-sdk-for-c](https://github.com/Azure/azure-sdk-for-c) for PlatformIO.

## Usage

Add this repository url to the lib_deps in your platform.ini.

**platform.ini:**
```
[env:seeed_wio_terminal]
lib_deps = 
    https://github.com/SeeedJP/pio-azure-sdk-for-c#1.1.0
```

## Update method

1. Copy sdk/inc and sdk/src in https://github.com/Azure/azure-sdk-for-c to this repository.
