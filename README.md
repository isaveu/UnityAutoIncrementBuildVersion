# Unity-auto-version-increment
Simply post build script to increment each build version in Unity

#How-to
Just place it under your Editor/ directory and it should run automatically after every build.

#Getting the version number inside your unity project
Simply call 
```C#
Application.version
```

Note: only works for Android and iOS at the moment. Feel free to add other platforms and make a pull request.
