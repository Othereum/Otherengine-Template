cmake_minimum_required(VERSION 3.16)

# Change this to your project name
project(MyGame)

# Set engine version
set(ENGINE_VERSION_REQUIRED 0.2.0)

# Change "../Otherengine" to the engine installed path
add_subdirectory("../Otherengine" Engine)
