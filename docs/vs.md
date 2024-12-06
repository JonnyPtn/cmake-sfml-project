# Visual Studio

Visual studio has built-in support for cmake projects, so there are two ways you can use this

## Visual studio workspace

For this approach, you simply select "Open a local folder" and select this projects root folder. By default it should configure cmake automatically, but if not you can do that via the `Project -> Configure CMakeSFMLProject` menu option

## Visual studio project

Generating a proper visual studio project can be necessary or optimal in some cases, and is almost as simple.

Open a windows terminal in the root project folder and run:

`cmake -B build`

This will generate a visual studio solution under `build/CMakeSFMLProject.sln` which you can open with visual studio and use normally