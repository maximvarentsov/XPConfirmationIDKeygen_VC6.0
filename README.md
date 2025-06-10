# XPConfirmationIDKeygen

## Description
This project generates a confirmation identifier for activating Windows XP SP0. Compatible with Visual Studio 6.0.

## Project Contents
- `main.cpp`: main source code file.
- `resource.h`, `Resource.rc`, `resrc1.h`: interface and icon resources.
- `stdint.h`: auxiliary header file.
- `xp_activate32.ico`: application icon.

## Requirements
- Development Environment: **Visual Studio 6.0**
- Supported OS: **Windows XP SP0** (to avoid `DecodePointer` error)

### About the `DecodePointer` Error
The `DecodePointer` error occurs in Windows versions later than XP SP0 due to incompatibilities with newer security mechanisms introduced in later service packs and Windows updates. Specifically, functions like `DecodePointer` were introduced in Windows XP SP2, leading to runtime errors when software is run on older or mismatched versions.

## Build Instructions
1. Open the `XPConfirmationIDKeygen.dsw` file in Visual Studio 6.0.
2. Build the project.

## Usage
Run the compiled executable on Windows XP SP0 to generate the confirmation identifier.
