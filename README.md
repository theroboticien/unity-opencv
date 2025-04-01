# Unity OpenCV Integration

## Introduction

This project demonstrates how to integrate the OpenCV library with Unity. It includes two example files:

1. A Unity C# script that calls a function from a native DLL.
2. A C++ implementation using OpenCV to load and display an image.

## Files

- **C# Script**: Contains the Unity MonoBehaviour script that initializes the DLL call.
- **Load image opencv**: Implements the `Load` function using OpenCV to read and display an image.

## Usage

1. Replace `"name of your dll"` in the C# script with the name of your compiled DLL.
2. Update the `imread("Path of your file")` line in the C++ file with the path to your image file.
3. Compile the C++ file into a DLL and place it in the appropriate directory for Unity to access.
4. Attach the C# script to a GameObject in your Unity scene.

## Additional Resources

For a detailed explanation of the setup process, watch the accompanying YouTube video: [Unity OpenCV Integration Tutorial](https://youtu.be/ucznDaFe-mE).

Thank you for exploring this project!
