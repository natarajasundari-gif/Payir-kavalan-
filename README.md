# பயிர் காவலன் | Crop Guardian AI

பயிர் காவலன் (Crop Guardian AI) is a farmer-focused crop disease identification and awareness application designed to make crop health information simple and accessible, especially for users with limited technical experience.

The application provides a simple mobile-first interface where farmers can scan or upload crop images, identify visible symptoms, view disease information, understand possible risks, and access basic treatment and prevention guidance.

## Features

### 🌱 Crop Disease Identification

* Scan an affected crop using the camera.
* Upload a crop image from the gallery.
* Designed to provide AI-based disease identification.
* Displays the identified crop and suspected disease.

### 🔍 Symptom-Based Identification

Farmers can identify possible problems based on visible symptoms such as:

* Leaf spots
* Yellowing
* Wilting
* Fruit rot
* Stem damage
* Visible pests

### 🌦️ Disease & Weather Alerts

The application provides a disease-risk section containing:

* Temperature
* Humidity
* Rainfall
* Disease risk level
* Crop-specific outbreak information

This is intended to help farmers understand environmental conditions that may contribute to disease spread.

### 🩺 Diagnosis & Treatment Information

The diagnosis section displays:

* Crop name
* Disease name
* Disease category
* Scientific name
* Suggested immediate actions
* Treatment guidance

The current interface includes an example diagnosis for tomato Early Blight caused by *Alternaria solani*.

### 📚 Crop Disease Guide

A horizontally scrollable disease guide provides examples for common crops such as:

* Tomato
* Paddy
* Potato
* Cotton

Each crop is accompanied by an example disease and its common name.

### 🌐 Tamil & English

The application supports both:

* தமிழ்
* English

Tamil is the default language. The selected language is stored using browser `localStorage`, so the preference can be retained between visits.

### 📖 Simple "How to Use" Guide

The interface explains the basic workflow in four steps:

1. Photo
2. AI Analysis
3. Result
4. Protect

This is designed to keep the application easy to understand for first-time users.

## User Interface

The application follows a mobile-first design with:

* Farmer-friendly navigation
* Tamil-first content
* Large action buttons
* Simple cards
* Clear disease information
* Bottom navigation
* Responsive layout for smaller screens

The main application container is designed around a mobile width of up to 480px.

## Technology Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Google Fonts

  * Noto Sans Tamil
  * Noto Serif Tamil

### Browser Storage

* `localStorage`

Currently, language preference is stored locally in the browser.

## Project Structure

A basic implementation can be organized as:

```text
crop-guardian/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   └── icons/
│
├── backend/
│   ├── main.py
│   ├── ml/
│   ├── services/
│   └── database/
│
└── README.md
```

The exact backend structure can be expanded as the AI disease-detection system is integrated.

## Application Workflow

```text
Farmer
   ↓
Take Photo / Upload Image
   ↓
Crop Disease Analysis
   ↓
Disease Identification
   ↓
Disease Information
   ↓
Treatment / Prevention Guidance
   ↓
Protect the Crop
```

## Target Users

The application is primarily designed for:

* Farmers
* Small-scale farmers
* Users with limited technical knowledge
* Agricultural workers
* Rural communities

The interface uses simple language and visual elements to reduce the technical barrier for farmers.

## Safety & Agricultural Guidance

The application is intended as an informational and decision-support tool.

For severe or uncertain crop disease outbreaks, users should consult the appropriate local agricultural department or qualified agricultural expert. The current interface also directs farmers to their local agricultural department for severe disease outbreaks.

## Current Status

The current project contains the mobile-first frontend prototype and interaction for:

* Tamil/English language switching
* Crop scanning interface
* Gallery upload interface
* Disease-risk information
* Symptom selection
* Diagnosis display
* Treatment guidance
* Crop disease guide
* How-to-use guide
* Farmer advisory section

The AI model, backend API, database, and real-time agricultural data can be connected to these frontend components as the application is developed further.

## Future Improvements

Possible future improvements include:

* Real-time crop image disease prediction
* Integration with the trained PlantVillage-based model
* Camera and gallery image processing
* Weather API integration
* Location-based disease alerts
* Disease history for farmers
* More Tamil agricultural content
* Additional crop and disease classes
* Offline support
* Farmer-friendly treatment recommendations
* Backend database integration
* Disease outbreak forecasting

## Vision

பயிர் காவலன் aims to make crop disease identification easier for farmers by combining computer vision, agricultural information, weather-based risk awareness, and a simple Tamil-friendly interface.

**"Identify early. Act quickly. Protect the crop."**
