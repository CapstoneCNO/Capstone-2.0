# Capstone - SEG4910[W] Software Engineering Project*

## Project Title
**AI-Driven Atherosclerosis Plaque Segmentation**

## Overview
This capstone project focuses on the design and development of an AI-powered software pipeline for automated segmentation of regions of interest (ROIs) in atherosclerotic plaque whole-slide images (WSIs). The project supports ongoing cardiovascular research led by Dr. Mireille Ouimet at the University of Ottawa Heart Institute, aiming to accelerate the analysis of arterial tissue samples and improve plaque quantification accuracy.

The solution leverages the Prov-GigaPath_HRSeg framework to handle high-resolution WSI tiling, model training, inference, and full-resolution stitching, ensuring scalability and precision in large pathology datasets.

A full-stack clinical desktop application—built with React, TypeScript, Flask, and Electron—serves as the user interface, streamlining WSI upload, AI-assisted segmentation, and visualization in both research and clinical environments. The platform enables real-time feedback, interactive region labeling, and export of analysis-ready results, promoting efficient collaboration between AI researchers and clinicians.

Researchers can upload WSIs, trigger AI-based segmentation, and inspect outputs with adjustable overlays for region validation and refinement.

## Prerequisites
Before you begin, ensure you have the following software installed globally.
You can do this by installing the package.json dependencies through:  `npm install`

If you encounter any errors, you can do it manually: 
- **Node.js** - [Download Node.js](https://nodejs.org/)
- **npm** (Comes with Node.js)
- **Electron** - Run `npm install -g electron`
- **React** - Note: Typically, React is installed locally per project, but if needed globally, run `npm install -g react`
- **Vite** - Run `npm install -g vite`
- **Bootstrap** - Run `npm install bootstrap`

## Installation
### Setting Up the Python Server
1. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   
2. Run the server:
   ```bash
   python app.py

### Setting Up and Running the Electron + React Application
1. Navigate to the React-Electron app directory:
   ```bash
   cd my-react-electron-app
   
2. Start the application:
   ```bash
   npm run dev:all

## Usage
Access the application at: http://localhost:5173
(Electron will launch automatically)

Server: http://localhost:5000

## Team Members
### Alejandra Carolina González González - PROJECT MANAGER

ID: 300262719

Email: agonz024@uottawa.ca

### Nicholas Beaulieu - QA MANAGER

ID: 300234643

Email: nbeau066@uottawa.ca

### Omar Ouadouha - LEAD DEVELOPER

ID: 300263227

Email: oouad032@uottawa.ca

## Customer
### Dr. Christopher Sun

Assistant Professor, Telfer School of Management, University of Ottawa

Scientist, University of Ottawa Heart Institute

Canada Research Chair in Data Analytics for Health Systems Transformation

Email: sun@telfer.uottawa.ca


