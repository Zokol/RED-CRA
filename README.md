# RED-CRA research project 2023->

My RED-CRA research project was started in 2023, aiming to form methods and tools for practical IoT evaluation.

## Research questions
1) How vulnerable the common intrenet-connected consumer electronics are?
2) How to detect these vulnerabilities with minimal resources?
3) Does the upcoming regualion actually have any effect in the security of these devices?
   
This repository contains my notes of the state of regulation around 2023-2024, as well as the tools and methods developed during the research.
First phase of my research ended by February 2025, with the publication of the findings at Disobey 2025.

Disobey 2025 talk: https://www.youtube.com/watch?v=gXucurU5_iY

## Regulation documents

### RED
* 18031-1: Network connected device
* 18031-2: Devices handling personal information, smart toys, etc..
* 18031-3: Devices handling financial assets

![Mindmap of RED 18031 requirements](https://github.com/Zokol/RED-CRA/blob/main/RED%20evaluation.png)

### CRA
https://www.european-cyber-resilience-act.com/Cyber_Resilience_Act_Annex_1.html

## Tools

### ITM3

IoT Meter 3, three dimensional metrics for quality of cybersecurity in internet-connected devices

Contains the metrics, as well as guidelines for collecting evidence from the devices

Project home: https://github.com/Zokol/ITM3

### pcapMapper

Started as a simple python-script to find geoIP of pcap-traffic.

Now does a bit more, producing for example statistics and visualization from network packet capture

Project home: https://github.com/Zokol/pcapMapper

### NetNote

I needed a simple browser-based tool to inject notes into the network traffic.

Mostly used for notekeeping during testing of physical devices, allowing forming connection between user actions (registering a device via mobile app) and the collected network traffic. 

Project home: http://note.juva.lu

Source: https://github.com/Zokol/note
