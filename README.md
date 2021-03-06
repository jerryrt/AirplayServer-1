APS
===========================
APS(Airplay Server) is an complete implementation of Airplay server including screen mirroring and video streaming. And this project is written for cross-platform.

| Platform | Master |
| --- |  :---: |
| **Windows** |  [![Build status](https://dev.azure.com/sheentian/T-Work/_apis/build/status/AirplayServerSDK-Build-Windows)](https://dev.azure.com/sheentian/T-Work/_build/latest?definitionId=20) |
| **Android** | [![Build status](https://dev.azure.com/sheentian/T-Work/_apis/build/status/AirplayServerSDK-Build-Android)](https://dev.azure.com/sheentian/T-Work/_build/latest?definitionId=21) |
| **macOS** | [![Build status](https://dev.azure.com/sheentian/T-Work/_apis/build/status/AirplayServerSDK-Build-macOS)](https://dev.azure.com/sheentian/T-Work/_build/latest?definitionId=22) |
| **Linux** |[![Build status](https://dev.azure.com/sheentian/T-Work/_apis/build/status/AirplayServerSDK-Build-Linux)](https://dev.azure.com/sheentian/T-Work/_build/latest?definitionId=23)|

# Build instructions:

## Windows
Run the generate_vs_proj.bat to generate the project files. Build the generated solutions and collect the output static library. 

## Android
Open the project folder with Android Studio and build the airplay module. The output is AAR library.

## macOS & iOS
Run the generate_xcode_proj.bat to generate the project files. Build the xCode project.


# Runtime requirements
APS depends on the the Bounjour service on all platforms.

## Windows
Make sure the Bonjour Service is installed, this is required by APS sdk. Download the runtime library from: https://developer.apple.com/bonjour/

## Android, macOS and iOS
APS will use the system build-in Bonjour service, no need to install any extra library.