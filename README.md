# MayaVerseNetworkingAwesome
List of all Networking Resources for Metaverse

Reference: https://gitlab.com/Juankz/realtime-network-sync-godot/raw/master/README.md
If you want to learn games networking properly I recommend the book [Multiplayer Game Programming: Architecting Networked Games](https://www.amazon.com/Multiplayer-Game-Programming-Architecting-Networked/dp/0134034309) by Joshua Gazler and Sanjay madhav.

This demo itself takes inspiration from the GDC talk [Networking for physics programmers](https://www.youtube.com/watch?v=Z9X4lysFr64) by Glenn Fieddler and the [Fast-Paced Multiplayer article series](https://www.gabrielgambetta.com/client-server-game-architecture.html) by Gabriel Gambetta.

Other very useful resources:
 
Valve wiki: https://developer.valvesoftware.com/wiki/Latency_Compensating_Methods_in_Client/Server_In-game_Protocol_Design_and_Optimization

Networking of Halo Reach: https://www.gdcvault.com/play/1014345/I-Shot-You-First-Networking

Networking System for VR

- [Lightweight and fully managed reliable UDP library.](https://github.com/MidLevel/Ruffles)

Networking Framework

- https://www.socketweaver.com/index.html
- https://normcore.io/
- https://coherence.io/

Tutorials

- https://github.com/tom-weiland/tcp-udp-networking (https://www.youtube.com/playlist?list=PLXkn83W0QkfnqsK8I0RAz5AbUxfg3bOQ5)
- https://wirewhiz.com/prototyping-multiplayer-on-a-single-pc/ https://archive.ph/UjrNt https://web.archive.org/web/20191205084408/https://wirewhiz.com/prototyping-multiplayer-on-a-single-pc/
- https://docs.google.com/presentation/d/1D_bCbN8VOYtRKtdm4c38gk8kiyziBzVIYztBYhVy4EE/edit#slide=id.p
  https://github.com/hach-que/gcap2019_demos
  https://www.youtube.com/watch?v=HwrM6vlbdxQ
- If you have anytime you can check this repo https://github.com/netcode-io/yojimbo.net.
It is a wrapper for C# and I have created a simple game client and server with that repo for Unity. The result is perfect, it works. May be it helps you.

Here you can find the example repos.
https://github.com/erdinckaya/prometheus - for Client
https://github.com/erdinckaya/themis - for Server

Last time I checked, the only thing that is missing is yojimbo.net didn't implemented secure connection, however you can define your secure server to establish secure connection.

VRTK v4.0.0 Beta + SteamVR 2.2 and Oculus 

- Virtual Reality with VRTK4: https://www.apress.com/it/book/9781484254875
- FusedVR: Getting Started with SteamVR 2.0 and VRTK: https://www.youtube.com/watch?v=DAAOtAJ6YE8
- Unity Scripting with VRTK beta v4: https://www.youtube.com/watch?v=4APODj6rd1s
- https://github.com/zachRudz/VRTK_Examples/blob/master/README_interactables.md
- https://github.com/mattxreality/VR-OculusTemplate

--

# New System using Photon

XR Toolkit

- https://skarredghost.com/2020/09/25/steamvr-unity-xr-interaction-toolkit-input/
- Github Project: https://github.com/Vytek/multiplayeroculusquest
- Valem course on Youtube: 
 - https://www.youtube.com/watch?v=KHWuTBmT1oI
 - https://www.youtube.com/watch?v=DB5bajOMdUQ
- Udemy course: https://www.udemy.com/course/multiplayer-virtual-reality-vr-development-with-unity/
- Avatars: https://readyplayer.me/

# Using CSharp ENET

Tutto su ENET:

https://github.com/rthompsonj/EnetPrototype

MiniNet:

- https://discord.com/channels/515987760281288707/589124849029480457/710693272242356295
- https://github.com/nxrighthere/ENet-CSharp/releases/tag/2.4.3
- https://github.com/SoftwareGuy/ENet-CSharp
- https://github.com/JohannesDeml/ENetUnityMobile
- https://github.com/javawork/ENet-CSharp-Unity-Example
- https://github.com/Vytek/ENETCSharpTestClient
- https://github.com/Vytek/TestENETCSharp

# Using Normcore

- https://normcore.io/documentation/xr-guides/xr-avatars-and-voice-chat.html
- https://gist.github.com/Godatplay/5fe4335d518afc40f95be7a4ed47ae07
- [Unity + Normcore Player Lobby and Name Sync](https://www.youtube.com/watch?v=J78uxCPO4rs)
- https://github.com/mikethevrguy/normcore-steamvr-tutorial-demo
- https://github.com/mikethevrguy/Normcore-SteamVR-Tutorial
- https://www.youtube.com/watch?v=ImoVyfCLXAc&list=PL8U6r3HT6h9pxdCbGzy4kVttJw4rs4FTU
- https://arvrjourney.com/how-to-setup-a-basic-vr-multiplayer-ball-toss-using-normcore-d86f1476e87c
- [How To Add Multiplayer Features To VR Games | Normcore And Unity XR Toolkit](https://www.youtube.com/watch?v=T9UNM88YICc)
- [Test repo for Normal's "Normcore 2.0", using Unity XR Rig locomotion](https://github.com/tedbarnett/NormcoreXR)
- https://github.com/dilmerv/XRToolKitWithNormcore

# Using Lidgren

- [LidgrenAndUnityExample](https://github.com/joeythelantern/LidgrenAndUnityExample)

# Enviroment

- https://github.com/nothke/AtmosphericScattering/tree/package
- https://assetstore.unity.com/packages/templates/tutorials/simple-day-and-night-cycle-system-66647
- https://github.com/EnricoMonese/DayNightCycle
- https://github.com/adrianpolimeni/RealTimeVolumetricClouds
- https://github.com/charliebratches/Grass-Shader

All about SteamVR 2.x

- VERY IMPORTANT: https://www.youtube.com/playlist?list=PLrk7hDwk64-YPtAkAwIOhlJuQzC2sP25G
- [Unity SteamVR Setup For Unity 2019 | Unity VR Tutorial 2020](https://www.youtube.com/watch?v=7WL19SiZ98g)
- [Book Versione 2 Building VR with Unity and SteamVR 2](https://github.com/psychicparrot/BuildingVRWithUnityAndSteamVR)
- https://medium.com/@sarthakghosh/a-complete-guide-to-the-steamvr-2-0-input-system-in-unity-380e3b1b3311
- https://medium.com/@setzeus/tutorial-steamvr-2-0-laser-pointer-bbc816ebeec5
- https://medium.com/@MrsDragos/steam-vr-updates-how-to-setup-teleport-mechanics-40b76001ae5a
- (Mirror) https://archive.ph/MxWFP
- https://github.com/ValveSoftware/steamvr_unity_plugin
- https://valvesoftware.github.io/steamvr_unity_plugin/ 
- https://wirewhiz.com/how-to-use-steamvr-2-0-input-in-unity/ 
- https://www.raywenderlich.com/9189-htc-vive-tutorial-for-unity
- https://connect.unity.com/p/steamvr-2-0-starter-migration-action-sets 
- https://medium.com/@danielle.co3tz33/steamvr-2-2-0-new-input-system-tutorial-3fef5e275828
- https://github.com/yusufalibrahim1994/SteamVR-Test-Two

?create \steamvr2v3 - VRTK v3 isn't compatible with SteamVR 2.x but v4 is. The supported SteamVR version 1.2.3 for VRTK v3 can be downloaded here https://github.com/ValveSoftware/steamvr_unity_plugin/releases/download/1.2.3/SteamVR.Plugin.unitypackage Provisional SteamVR V2 support for VRTK v3.3 has been provided by community support and can be found at: https://github.com/WildStyle69/SteamVR_Unity_Toolkit/tree/feat/steamvr2-input-system
Molto importante:


Video
* https://www.youtube.com/playlist?list=PLmc6GPFDyfw-zhd2OA6tE9nDYeJUmA8rW
* https://www.youtube.com/playlist?list=PLmc6GPFDyfw83KiqUHZceuThGKoyO4hkt
* https://www.youtube.com/playlist?list=PLmc6GPFDyfw9oYXHuQnskDaldAszkU8aG
* https://www.youtube.com/playlist?list=PLmc6GPFDyfw-fku8fzGxucvEm1J3oDNix
* Playlist: https://www.youtube.com/c/VRwithAndrew/playlists
