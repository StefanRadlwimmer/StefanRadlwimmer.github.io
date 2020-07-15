---
name: "Master Thesis: Open Locomotion"
image: "/assets/img/portfolio/Open_Locomotion/header.png"
description: "Master Thesis in cooperation with Cyberith in which I defined and implemented an industrial standard for VR locomotion devices like the Cyberith Virtualizer."
website: https://aixr.org/insights/open-locomotion-standardization/
release-date: "In active development"
platforms: [Virtual Reality,Hardware,Framework]
---

## About
Lacking a uniform implementation for Locomotion Devices and only releasing proprietary programing interfaces these smaller startup companies have become somewhat dependent on integrating their devices into more common VR platforms like Valve’s SteamVR to reach a bigger audience. 

This dependency often implies technical limitations as most platforms are designed to serve controller input and are not specialized to the needs of each Locomotion device. Also, past experiences show, that this lack of specialization has led to technical issues after an update to the platform resulting in problems or inoperability for customers of Locomotion Devices.

[Read more on LinkedIn...](https://www.linkedin.com/in/stefan-radlwimmer/detail/treasury/education:354544198)

![](/assets/img/portfolio/Open_Locomotion/OpenLocomotion_Before_After.png)

## Work

In my thesis I covered a wide spectrum of essential information about VR Locomotion Devices and existing VR platforms, whose capabilities and limitations were described and evaluated. Thereafter I defined a new specialized industrial standard – OpenLocomotion – which aims to solve current industry issues for VR Locomotion Devices. 

After specifying the standard, I developed an OpenLocomotion compliant prototype framework.

- Open Locomotion Standard
	- Standardized description of physical human locomotion
	- Uniform implementation for Virtual Reality Locomotion
	- Expandable while staying backwards compatible 
	- Standalone standard without any dependencies
- Open Locomotion Platform
	- 4 Device Drivers (Cyberith Virtualizer, Wizdish ROVR, Keyboard, Gamepad)
	- Prototype Framework joining Drivers and Runtime
	- 2 Engine Plugins (Unity and Unreal 4)
- Prototype Framework
	- Syntactic similar to OpenVR
	- Abstract Architecture
	- Backwards Compatibility
	- Multi-Language Support
		- C++, C#, Python

## Used Software and Technology
- **Programming language:** C, C++, C#, Python
- **Game engine:** Unreal Engine 4.18-4.23, Unity 2017-2019
- **Project management tool:** GitLab
- **Source control:** GitLab
- **Other tools:** Resharper