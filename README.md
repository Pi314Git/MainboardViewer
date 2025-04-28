# Mainboard 3D Viewer

## Overview
The **Mainboard 3D Viewer** is a web-based application that provides an interactive 3D exploration experience of a computer motherboard. *(Made with the help of Claude Sonnet 3.5/3.7)*

This tool is designed for educational purposes, allowing users to understand the various components of a motherboard through visualization and detailed descriptions. The application features the **ASUS ROG STRIX X370-F GAMING** motherboard as its 3D model, providing a detailed look at this **ATX form factor** board.

## Features
- **Interactive 3D Model**: Rotate, zoom, and pan to explore the motherboard from any angle.  
- **Component Highlighting**: Select components from the sidebar to highlight them on the 3D model.  
- **Detailed Information**: Access descriptions and technical details for each motherboard component.  
- **Form Factor Comparison**: Visual comparison of different motherboard form factors (ATX, Micro-ATX, Mini-ITX, etc.).  
- **Responsive Design**: Works on desktops and tablets with varying screen sizes.  

## Components Documented
- AM4 Socket / CPU Socket
- CPU Power Connectors
- Motherboard Power Connectors
- DIMM Slots (RAM)
- PCIe Slots
- M.2 Slot
- SATA Connectors
- Chipset
- VRM
- BIOS Battery with inclusion of BIOS-CHIP, CMOS-Storage / (FLASH)-ROM Explanation
- Fan Headers
- RGB Headers
- Front Panel Connectors
- I/O Panel

## Technical Details
The application is built using:
- **[THREE.js](https://threejs.org/)**: For 3D rendering and interactive controls.  
- **JavaScript**: For application logic and interactivity.  
- **HTML5/CSS**: For UI layout and styling.  
- The 3D model is loaded as a **GLB file**, and the application uses **OrbitControls** from THREE.js to enable intuitive navigation around the model.

## Credits
- **3D Model**: ASUS ROG STRIX X370-F GAMING motherboard - [Sketchfab Model](https://sketchfab.com/3d-models/rog-strix-x370-f-motherboard-56bd8923fdf341fd8d81b717055a61dd#download)  
- **THREE.js Library**: Various JS components - [THREE.js](https://threejs.org/)  
- **Motherboard Specifications**: [ASUS ROG STRIX X370-F GAMING](https://rog.asus.com/motherboards/rog-strix/rog-strix-x370-f-gaming-model/)  

---
This project aims to make learning about motherboard components engaging and interactive through 3D visualization!

