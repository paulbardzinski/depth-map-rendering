# Depth Map Rendering
A small console app that renders real-time depth data from the Intel Realsense camera.

*Tested on Intel Realsense D435*

## How To Run
- Download the `Program.cs` and `Intel.RealSensed.dll` library
- Create a new C# project, place the content of `Program.cs` to the main file
- Place `Intel.RealSensed.dll` to the bin folder, where all dependencies are (for exmaple: `bin/Debug/net8.0/`)
- Run it in **Debug** mode. If you want to do it in a **Release** mode, you will have to compile the Intel Realsense SDK for C# bindings. See more [here](https://github.com/IntelRealSense/librealsense).

![image](https://github.com/user-attachments/assets/478a7ed8-48fa-4836-ba08-d421cc16ac5a)

![image](https://github.com/user-attachments/assets/9dfb2932-f995-4b6d-9d74-adaab017721c)

## Dependencies Libraries and Products
#### [librealsense](https://github.com/IntelRealSense/librealsense)
> **License:** Apache License 2.0
>
> **Author:** IntelRealSense
>
> **Principal Use:** Communication with Intel Realsense D435 camera
