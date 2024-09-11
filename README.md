# Walrus_HApp
This is a repository that uses the preview of Walrus storage to create a prototype version of simple PKI/CA.

## Building
1. Navigate to [this website](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
2. Download and install SDK.
3. Download the zip file.
4. Extract the zip file.
5. Open command line.
6. Navigate to first folder (Walrus_HApp).
7. Do /dotnet build
8. Navigate to second folder (Walrus_HApp.Desktop).
9. Do /dotnet build

The compiled application reside within **bin/debug/net8.0**.

## Running
1. Do all the steps in building.
2. If you're on Windows, navigate to the folder where the compiled application resides. Double click on **Walrus_HApp.Desktop.exe**.
3. If you're on Linux/MacOS, navigate to the folder where the compiled application resides via command line. Do **/dotnet Walrus_HApp.Desktop.dll**
