TheParallaxView
---------------

Depth illusion by 3D head tracking and off-axis projection on iPhoneX

# Dependencies

* Project made in Unity 2017.3.0f3
* [UnityARKitPlugin](https://bitbucket.org/Unity-Technologies/unity-arkit-plugin)
* XCode (building for iOS)

# Setup

1. Change your build settings to "iOS"
1. Clone this repo and open "HeadTrackScene"
1. Import the UnityARKitPlugin
1. Navigate to the ARKitSettings in Assets/UnityARKitPlugin/Resources/UnityARKitPlugin/ARKitSettings.asset and enable "AR Kit Uses Facetracking" and "App Requires AR Kit"
1. In your project settings make sure that both Portrait and Portrait upsidedown mode are disabled. This app currently optimized for landscape mode only.
1. Add the HeadTrackScene to the scenes in your build within the build settings.
1. Build and run!



![gif](https://static1.squarespace.com/static/5414cc37e4b06505bdaf2198/t/5a98655d8165f58d088976c6/1519936866358/TheVoid_sm2.gif)
![gif](https://static1.squarespace.com/static/5414cc37e4b06505bdaf2198/t/5a986585e4966bbe399d1ff7/1519936905112/EyeTracking_sm2.gif)

Note that this is a monoscopic effect. When using the app IRL, the illusion is best seen with ONE EYE - the other eye closed. (Also works great for video since video is monoscopic). For a stereo effect some type of glasses would be needed (anaglyph or active) and the app adapted for it.

Info on method and code: [TheParallaxView Article]

[TheParallaxView Article]: http://anxious-bored.com/TPV
