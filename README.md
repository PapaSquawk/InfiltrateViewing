# Better Infiltrate Viewing Experience (BIVE)
Proof of concept for a better Infiltrate's viewing experience: Having the contestant wear a virtual reality headset and stream what they see to a larger screen for a general audience.

Three main components of this proof of concept will consist of a virtual reality environment for desktop applications, an eye tracker, and a real-time render of used keyboard keys. 

The first component will be to allow the contestant to operate their workstation to successfully compete in the competition; accomplished by emulating a desktop workstation in VR. The emulation will allow the contestant to orient applications windows in 3D space which will effectively function as a multi-monitor setup and give the viewing audience context on to which window the contestant is viewing. This effect will give more insight into the thought process of how the contestants are solving their binaries.

The second component will be an eye tracker of each contestant only visible to the larger audience. The eye tracker will allow the viewers to see what the contestant is focusing on within the various windows in their virtual environment; providing more context into the contestant's exploitation process.

The third component will be a real-time render, only visible to the larger audience, of which keyboard keys the contestant is pressing. This will allow the audience to better view which hotkeys and macros the contestant is using that is not normally visible when viewing from afar.

Toolkit selection: The Unity3d toolkit appears to be the toolkit with the most 3rd party support in terms of open source additions that would be make this proof of concept easier to develop and see its overall practicality. The XR Interaction Toolkit [https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@0.9/manual/index.html] and the VRTK toolkit [https://vrtoolkit.readme.io/docs/summary ] for the Unity3d engine provides an SDK with already built-in functions that will assist the development of the proof concept. (The toolkits for general VR development)

VR headset selection: One of the most widely supported headsets that has built-in eye tracking is the HTC Vive Pro Eye. The Pro Eye also has its own toolkit called the Tobii XR SDK that has Unity support to showcase its eye tracking capabilities (i.e heatmaps, duration of glances, etc). [https://vr.tobii.com/sdk/develop/unity/getting-started/vive-pro-eye/]
