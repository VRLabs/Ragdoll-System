<div align="center">
# Ragdoll System

[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-lightblue.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

[![Generic badge](https://img.shields.io/discord/706913824607043605?color=%237289da&label=DISCORD&logo=Discord&style=for-the-badge)](https://discord.vrlabs.dev/)
[![Generic badge](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dvrlabs%26type%3Dpatrons&style=for-the-badge)](https://patreon.vrlabs.dev/)

Turn yourself into a floppy ragdoll or falling statue

![Ragdoll-Freeze](https://github.com/VRLabs/Ragdoll-System/assets/76777936/42bb5b1a-05a3-42fe-ba40-e749cbc4a7b4)
![Ragdolll](https://github.com/VRLabs/Ragdoll-System/assets/76777936/bf5fd723-3971-4858-a430-f125bfde6456)



### ⬇️ [Get it on Booth!](https://vrlabs.booth.pm/items/2911183)
### ⬇️ [Get it on Gumroad!](https://vrlabs.gumroad.com/l/ragdoll-system)

</div>

---

## How it works
* The system generates a second armature, which is constrained to your humanoid bones
* The main armature's meshes can be hidden, and this second armature is enabled, allowing this armature to "ragdoll", as well as perform the other features

## Install guide

https://github.com/VRLabs/Ragdoll-System/assets/76777936/c73da405-2d6a-4927-bec6-d1e9c2a5b675

* Place the Ragdoll.cs script on your avatar and change any settings. Some settings have tooltips for explanation. 
* Click ``Generate Ragdoll System``.
* If needed, adjust the colliders after generation using their ``Edit Collider`` buttons.
* Press ``Finish Setup``.

* Your ragdoll may slightly bounce or jitter locally. Other players do not see this.
* If using Lyuma's emulator, disable the mirror and shadow clones before testing.

## How to use

* The system automatically adds a ``Ragdoll`` sub menu to your radial menu. 
* In this menu, you can select one of the features to start it, and select it again to stop it.

## Performance stats

```c++
Rigidbodies:        13
Constraints:        23
Parameter Memory:   3-8 (depending on features)
Contact Receivers:  2
Contact Senders:    1
FX Animator Layers: 3-7 (depending on features)
Audio Sources:      9
Colliders:          1
Particle Systems:   1
Mesh Renderers:     1
Skinned Renderers:  As many as your avatar has
Material slots:     As many as your avatar has

```

## Credit

[ksivl](https://github.com/ksivl)

​

<div align="center">

[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/VRLabs.png" width="50" height="50">](https://vrlabs.dev "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Discord.png" width="50" height="50">](https://discord.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Patreon.png" width="50" height="50">](https://patreon.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Twitter.png" width="50" height="50">](https://twitter.com/vrlabsdev "VRLabs")

</div>

