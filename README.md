# 🏛️ TradAR — AR Heritage Module

**TradAR (AR Heritage Module)** is an Augmented Reality (AR) system designed to transform how users explore cultural and historical sites. By leveraging marker-based AR, the module overlays interactive digital content onto the real world, creating an immersive and educational experience.

Instead of relying on static descriptions or physical tour guides, TradAR turns heritage exploration into a dynamic, visual, and multi-sensory journey.

---

## 🚀 Tech Stack

This project integrates multiple technologies across AR, 3D design, and mobile development:

- **Unity3D**
  Core engine for rendering, interaction logic, and AR scene orchestration.

- **ARCore**
  Handles motion tracking, environmental understanding, and camera integration on Android devices.

- **Vuforia (Marker-Based AR)**
  Enables detection and recognition of predefined markers to trigger AR content.

- **Blender**
  Used for creating and optimizing 2D/3D assets representing heritage sites.

- **Text-to-Speech API**
  Provides audio narration for an accessible and engaging storytelling layer.

---

## ⚙️ How It Works

The system follows a straightforward but powerful pipeline:

1. The user launches the **AR Heritage module** inside the application.
2. The device camera scans a predefined AR marker (printed or digital).
3. Once detected, **Vuforia** identifies the marker and signals Unity.
4. **Unity + ARCore** render the associated AR content in real time.
5. A **2D/3D model** or **interactive info card** appears anchored in the real world.
6. The user receives:
   - 📖 Textual information
   - 🔊 Optional voice narration explaining historical and cultural context

---

## ✨ Features

- 🎯 **Marker-Based AR Visualization**
  Reliable and efficient detection using predefined visual markers.

- 🧱 **2D & 3D Heritage Models**
  Digitally reconstructed cultural assets for realistic representation.

- 🌍 **Real-World Overlay**
  Seamless blending of virtual objects into the physical environment.

- 📚 **Multimodal Information Delivery**
  Combines text and audio for enhanced accessibility and engagement.

- ⚡ **Optimized Performance**
  Smooth rendering pipeline with user-friendly interaction design.

---

## 🎯 Project Purpose

TradAR aims to bridge the gap between technology and cultural education by:

- Making heritage exploration **interactive and engaging**
- Reducing dependency on **physical guides and static displays**
- Enhancing accessibility through **visual and auditory storytelling**
- Encouraging users to **connect with history using modern tools**

---

## 🧠 Why This Matters

Cultural heritage is often underrepresented in digital spaces. TradAR demonstrates how Augmented Reality can:

- Digitally preserve historical knowledge
- Improve educational experiences
- Make learning **intuitive, immersive, and memorable**

---

## 📦 Repository Usage

This repository contains the core implementation of the AR Heritage Module, including:

- Unity project files
- AR marker configurations
- 2D/3D assets
- Integration logic for ARCore and Vuforia
