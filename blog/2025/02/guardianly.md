---
title: "Guardianly — Personal Safety Navigation App"
date: "2026-06-19"
tags: [Flutter, Dart, Figma, Mapbox, UI/UX]
excerpt: "A personal safety app that helps commuters identify hazards and navigate safer routes."
---

## 🎯 Project Overview

Guardianly is a personal safety navigation app designed to help commuters and travelers identify hazards and navigate safer routes through an interactive map interface. 

The app addresses a real problem: **many navigation apps prioritize speed over safety**, sending users through high-crime areas, poorly lit streets, or dangerous intersections. Guardianly flips this by putting **safety first**.

### The Problem
- Commuters often don't know which routes are unsafe
- Existing navigation apps don't consider real-time hazard data
- Users need a simple way to see and avoid dangers

### The Solution
A mobile app that:
- Displays hazards on an interactive map using **Mapbox**
- Allows users to report incidents in real time
- Provides route suggestions based on safety, not just speed
- Features a clean, intuitive UI designed for quick glances

---

## 🧠 My Role & Responsibilities

| Area | What I Did |
| :--- | :--- |
| **UX/UI Design** | Designed end-to-end wireframes and interactive prototypes in Figma |
| **Frontend Development** | Built the mobile interface using Flutter/Dart |
| **Integration** | Integrated Mapbox for hazard visualization |
| **Collaboration** | Worked with a 3-person cross-functional team (backend + mobile) |
| **Testing** | Tested on Android, iOS, and web simulators |

---

## 🎨 Design Process

### 1. Research & Discovery
I started by researching existing safety apps and conducting informal user interviews with 10+ commuters. Key insights:
- Users want **simple, glanceable information**
- **Color coding** (red/yellow/green) helps quickly assess risk
- The app should not feel "scary" or overwhelming

### 2. Wireframing (Figma)
I created low-fidelity wireframes to map out the user flow and information architecture.

<!-- STAIRCASE GALLERY — Replace image URLs with your own -->
<style>
  .staircase-gallery {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 30px;
    padding: 20px 0;
    max-width: 700px;
    margin: 0 auto;
  }
  .staircase-item {
    width: 100%;
    max-width: 550px;
    transition: all 0.3s ease;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    overflow: hidden;
    cursor: pointer;
  }
  .staircase-item:nth-child(1) { transform: translateX(-20px); }
  .staircase-item:nth-child(2) { transform: translateX(20px); }
  .staircase-item:nth-child(3) { transform: translateX(-10px); }
  .staircase-item:nth-child(4) { transform: translateX(25px); }
  .staircase-item:hover {
    transform: translateX(0) scale(1.05) !important;
    box-shadow: 0 12px 40px rgba(0,0,0,0.3);
    z-index: 10;
    position: relative;
  }
  .staircase-gallery:hover .staircase-item:not(:hover) {
    opacity: 0.5;
    transform: scale(0.95);
    transition: all 0.3s ease;
  }
  .staircase-item img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 12px;
  }
  .staircase-caption {
    padding: 10px 14px;
    background: #f1f3f5;
    font-size: 13px;
    color: #333;
    text-align: center;
  }
</style>

<div class="staircase-gallery">
  <div class="staircase-item">
    <img src="https://raw.githubusercontent.com/MoonyMochiey/Feifei-sPortfolio/main/public/projects/guardianly-wireframe1.png" alt="Guardianly Wireframe 1 — Home Screen">
    <div class="staircase-caption">Home Screen — Quick glance at hazards nearby</div>
  </div>
  <div class="staircase-item">
    <img src="https://raw.githubusercontent.com/MoonyMochiey/Feifei-sPortfolio/main/public/projects/guardianly-wireframe2.png" alt="Guardianly Wireframe 2 — Map View">
    <div class="staircase-caption">Interactive Map — Hazards displayed with color coding</div>
  </div>
  <div class="staircase-item">
    <img src="https://raw.githubusercontent.com/MoonyMochiey/Feifei-sPortfolio/main/public/projects/guardianly-wireframe3.png" alt="Guardianly Wireframe 3 — Route Selection">
    <div class="staircase-caption">Route Selection — Safer alternatives highlighted</div>
  </div>
</div>

### 3. High-Fidelity Prototyping
After user testing the wireframes, I created a polished prototype in Figma focusing on:
- **Accessibility**: Large touch targets, high contrast colors
- **Clarity**: Simple icons, clear hierarchy
- **Speed**: Information at a glance

<!-- Add more images here if you have them -->

---

## ⚙️ Technical Implementation

### Technology Stack
| Technology | Purpose |
| :--- | :--- |
| **Flutter/Dart** | Cross-platform mobile app (iOS, Android, Web) |
| **Mapbox** | Interactive mapping and hazard visualization |
| **Figma** | UI/UX design and prototyping |
| **Git** | Version control and collaboration |

### Key Features Built
- **Interactive Map**: Real-time hazard visualization with Mapbox
- **Hazard Reporting**: Users can report incidents
- **Safe Route Suggestions**: Routes prioritized by safety metrics
- **Responsive Design**: Works on iOS, Android, and web simulators

---

## 🤝 Collaboration & Teamwork

- Worked with a **3-person cross-functional team**
- Aligned design decisions with **backend constraints**
- Used **Git** for version control and collaboration
- Regular **stand-ups** and **design reviews**

---

## 📱 Live Demo & Code

| Link | Purpose |
| :--- | :--- |
| [Live Demo](https://guardianly.netlify.app) | Try the app yourself |
| [GitHub Repo](https://github.com/MoonyMochiey/guardianly) | View the source code |
| [Landing Page](https://guardianly.netlify.app) | Project overview page |

---

## 💡 What I Learned

| Lesson | How I Learned It |
| :--- | :--- |
| **Design isn't just visual** | Had to balance user needs with technical feasibility |
| **Communication matters** | Explaining design decisions to non-designers |
| **Testing is essential** | User feedback revealed issues I hadn't considered |
| **Iteration is key** | Went through 4 design iterations before final version |

---

## 🔗 Related Links

- [Live App](https://guardianly.netlify.app)
- [GitHub Repository](https://github.com/MoonyMochiey/guardianly)
- [Back to Portfolio](/)
