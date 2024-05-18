---
title: "Extended Reality Tool for CFD-Aided Design and Development of a Shell-Tube Heat Exchanger"
excerpt: "AR based tool for CFD aided heat exchanger design<br/><img src='/images/reactor.png'>"
collection: portfolio
---


![CFDXR](/images/simulation menu with model.png)

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/watch?v=-olkPf3L3b8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Project Overview
This project showcases the integration of Extended Reality (XR) technologies with Computational Fluid Dynamics (CFD) simulations to enhance advanced education and research in chemical engineering. The main highlight is a user-friendly Augmented Reality (AR) interface that allows interactive exploration and analysis of fluid dynamics in a shell and tube heat exchanger.

### Key Features
- **Immersive AR Experience:** Provides an engaging and intuitive interface using Microsoft HoloLens 2.
- **Real-Time Interaction:** Enables real-time interaction with CFD simulations, offering immediate insights and feedback.
- **Educational Tool:** Facilitates learning through visual and interactive elements, making complex simulations accessible to users with varying levels of expertise.
- **Open-Source Integration:** Leverages open-source software to ensure cost-effectiveness and flexibility.

## Table of Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [XR Features](#xr-features)
- [Research Goals](#research-goals)
- [Methodology](#methodology)
- [Implementation](#implementation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Abstract
This project introduces a digital environment that integrates interactive CFD simulations tailored for advanced education in chemical engineering. The architecture employs a client-server network, establishing an automated bidirectional connection linking CFD solvers and a game engine. A modular software approach ensures the creation of enduring and interconnected digital applications. To address computational complexities and resource-intensive features, a content delivery network alleviates the burden of intricate calculations from end-user devices. A case study involving a shell and tube heat exchanger assesses the application’s performance, with results scrutinized for the efficacy of AR in visualizing simulations. Discussions center on the system’s applicability and outline potential future research and application directions.

## Introduction
The European Union (EU) is funding large-scale research projects to integrate digital tools into education and training, aiming to develop digitally skilled workers. This study highlights the increasing significance of computing tools in engineering and education, focusing on CFD, computer-aided engineering (CAE), and process modeling tools. These tools are fundamental in solving practical fluid flow problems and require complex models to address various unit operations. However, commercial CFD solutions are often expensive and require specialist expertise, posing barriers to widespread adoption.

## XR Features
The primary focus of this project is to harness the potential of XR technologies, specifically Augmented Reality, to create an interactive and immersive learning environment. Key XR features include:

### Immersive Visualization
- **3D Models:** Interactive 3D models of the shell and tube heat exchanger, generated from CFD simulation data.
- **Holistic View:** Users can view and manipulate the heat exchanger from different angles, providing a comprehensive understanding of its structure and function.

### Real-Time Interaction
- **Gesture Controls:** Use of HoloLens 2’s gesture recognition to interact with simulation data, such as rotating models, zooming in and out, and selecting different flow paths.
- **Live Data Visualization:** Real-time updates and visualization of CFD results, allowing users to see changes dynamically as they interact with the model.

### Educational Enhancements
- **Interactive Tutorials:** Step-by-step guided tutorials within the AR environment to help users understand the principles of heat exchangers and fluid dynamics.
- **Annotations and Overlays:** Informative overlays and annotations to explain key components and phenomena within the heat exchanger.

### Collaboration
- **Multi-User Support:** Potential for collaborative learning and research, where multiple users can interact with the same AR environment simultaneously.
- **Remote Access:** Capability for remote users to connect to the AR environment, facilitating distance learning and remote collaboration.

## Research Goals
The main objectives of this project are:
1. **Creating a User-Friendly AR Interface:** Develop an AR interface that enhances accessibility for users with varying levels of expertise. This includes user-friendly controls and interactive elements to create an engaging simulation environment.
2. **Incorporating Open-Source Software:** Utilize open-source CFD software to reduce costs associated with proprietary solutions, ensuring compatibility with the AR interface.
3. **Specialized Tool for Heat Exchangers:** Develop a tool specifically for the research and investigation of shell and tube heat exchangers, leveraging CFD simulations within a game engine environment.

## Methodology
The methodology involves server automation using open-source visual-based programming tools, notably Node-red, which facilitates seamless interconnection and automation of the simulation process. Communication between the AR device and server is managed using the MQTT protocol, ensuring efficient and reliable data transfer.

## Implementation
The implementation employs Microsoft HoloLens 2 as the AR hardware interface, integrating various software tools:
- **CFD Simulations:** OpenFOAM for fluid dynamics simulations, automated in Node-RED.

![Proposed architechure](/images/Client-server architechure new.png)

- **3D Visualization:** ParaView and Blender for transforming simulation data into interactive models.
- **AR Application Development:** Unity, along with MRTK, for designing the user interface and enabling real-time insights into the heat exchanger's behavior.

## Results
The case study demonstrates the effectiveness of the AR application in visualizing CFD simulations of a shell and tube heat exchanger. The use of AR significantly enhances user comprehension and interaction with simulation data, providing precise and captivating experiences.
![SimulationMenu](/images/simulation menu with model.jpg)
![HeatMap](/images/Temperature heatmap.jpg)
![TwoHandInteraction](/images/two hand interaction.jpg)
## Conclusion
The study successfully integrates AR with CFD simulations, making advanced fluid dynamics accessible to a broader audience. Future research may explore further enhancements in AR technology and its application in other engineering fields.

## Future Work
- Enhance the AR interface with more interactive features.
- Expand the application to other types of heat exchangers and engineering systems.
- Investigate the integration of VR technologies for more immersive experiences.
- Conduct user studies to gather feedback and improve the user experience.


---

© 2024 Jeswin Kannampuzha Francis. All rights reserved.
