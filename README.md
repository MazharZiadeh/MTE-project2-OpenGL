OpenGL 3D Rendering Project

This repository contains a simple C++ program using OpenGL for 3D rendering. The program creates a window, loads shaders, sets up a 3D model (a cube), and renders it with textures and basic camera controls.
Table of Contents

    Dependencies
    Getting Started
    Features
    Controls
    Directory Structure
    License

Dependencies

    GLFW - GLFW is a multi-platform library for creating windows with OpenGL contexts.
    GLAD - GLAD is a simple library for loading OpenGL functions.
    stb_image - stb_image is a single-file public domain library for image loading.
    glm - GLM is a mathematics library for graphics programming.
    MyTexture, MyShader, VAO, VBO, EBO, Camera - Custom C++ classes for handling textures, shaders, and OpenGL objects.

Getting Started

    Clone this repository: git clone https://github.com/your-username/your-repository.git
    Make sure you have the necessary dependencies installed.
    Build the project using a C++ compiler that supports C++11 standards.
    Run the executable.

Features

    Basic GLFW window creation and OpenGL context setup.
    Loading of shaders, textures, and basic rendering pipeline.
    Camera implementation for user interaction.
    Simple 3D model (cube) with texture mapping.

Controls

    Use arrow keys for camera movement (up, down, left, right).
    Use mouse movement for camera rotation.
    Scroll wheel for zooming in and out.

Directory Structure

    res/Textures: Directory for storing texture files.
    default.vert, default.frag: Vertex and fragment shader files.
    MyTexture.h, MyShader.h, VAO.h, VBO.h, EBO.h, Camera.h: Custom C++ classes.
