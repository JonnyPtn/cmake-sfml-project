# Xcode

Xcode cannot open cmake projects directly, however cmake has great support for generating Xcode projects

To generate an xcode project run this command in the root project folder:

`cmake -B build -GXcode`

Once finished this will generate an xcode project at `build/CMakeSFMLProject.xcodeproj` which you can use to build and run as you normally would with Xcode