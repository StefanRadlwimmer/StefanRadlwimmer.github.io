---
name: "ZIBIS Box"
image: "/assets/img/portfolio/ZIBIS_Box/header.png"
description: "The Zelisko IBIS vehicle connector is a newly developed on-board-computer for public transport vehicles using the German <b>I</b>ntegrated on<b>B</b>oard <b>I</b>nformation <b>S</b>ystem (IBIS) bus."
website: https://www.zelisko.at/de/products/trafficmanagementsystems/products_1/zibis/ticketmachine_2.jsp
platforms: [Embedded Linux,Raspberry Pi,Hardware]
---

## About
The new ZIBIS vehicle connector combines the previously separate areas of mobile sales solutions with the on-board computer functionality of permanently installed systems.

In the case of mobile solutions in vehicles, it has not been possible to control the exterior and interior displays, validators, TFT monitors, passenger counting systems, etc. in recent years. For this reason ZIBIS was developed.

With ZIBIS it is now possible to control the entire vehicle periphery via Bluetooth or WLAN using mobile solutions such as tablets and / or smartphones with the appropriate software.

The ZIBIS-Box can also be used as an autonomous TTS (Text to Speech) system.

## Work
Because of my year-long experience with C# I was honored to lead the development in Zelisko's newest product: the ZIBIS Box. As all previous products were using C++ I was tasked to develop a complete base framework using .Net Standard and develop a build chain, for the then new .Net Core 2.1 framework. 

This base framework would then be used to pose a good example for future developments and was complemented by full unit and integration test coverage. After six weeks of work I finished the framework and two sample applications - a TTS system and a automated updater via USB - as my internship ended.

- Setup of an base framework in .Net Standard and .Net Core 2.1 for Raspberry Pi.
  - Build Chain: Creating PowerShell scripts for build, package, deployment and debugging.
  - Hardware: GPIO, serial com ports, I2C.
  - Utilities: EventHandler, ThreadPool, OS specific file systems.
  - Unit & Integration tests.
- Development of 2 applications based on the .Net Core Framework.
    - TTS system with serial (IBIS) bus.
    - Auto updater via USB.

## Used Software and Technology
- **Programming language:** C# (.Net Standard, .Net Core), Powershell
- **Project management tool:** Team Foundation Server
- **Source control:** Git (Team Foundation Server)
- **Other tools:** Resharper