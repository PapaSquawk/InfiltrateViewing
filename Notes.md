# Notes
A commonplace to track ideas, progress, and general information about BIVE.
## Unity3D Progress
The various plugins from the HTC Vive and Oculus can be setup within Unity's personal edition successfully, but encounter a slight issue: 
 - The programs launch externally and the application data is not fed through the Unity engine.
 - This prevents the contestant from directly interacting with the application within a VR environment.

After some tinkering around with fixing the issue in Unity, the idea of using a remote desktop session to stream the contestant's desktop into the VR headset appears more fruitful.

Various applications have already attempted this idea such as the 3rd party [VirtualDesktop](https://www.vrdesktop.net/) or the more feature rich built-in Oculus desktop viewer, [Oculus Dash](https://www.youtube.com/watch?v=SvP_RI_S-bw), that is shipped with their headset. appear to use an RDP session to stream the user's desktop screen into the VR environment. The HTC Vive's desktop viewer does not appear to ship with a desktop viewer as Vive users have to use 3rd party applications to achieve the result.

The native Oculus SDK does allow for development for the Oculus Dash which would alleviate the issue that has been encountered within the Unity solution thus far and appears to be available in their [PC SDK toolkit](https://developer.oculus.com/documentation/native/pc/pcsdk-intro/).
- One issue that may be encountered is that the PC SDK is only available for Windows at the moment, but virtual machines within windows can resolve this as the vast majority of contestants will use a linux distro.
