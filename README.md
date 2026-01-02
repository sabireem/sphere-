# Sphere - 3D Interactive Hand-Tracked Experience

Sphere is a high-performance, web-based 3D application that combines interactive particle systems with real-time hand-tracking technology using MediaPipe and React Three Fiber.

![Sphere Preview](public/preview.png)

## 🌟 Features

- **Gesture Interaction**: Control 3D particles using hand movements captured via webcam.
- **Dynamic Physics**: Particles respond to hand gestures (attraction/repulsion) and follow complex 3D shapes.
- **Predefined Shapes**: Seamlessly transition between Saturn, Heart, and Sphere formations.
- **Hand Gesture Controls**:
  - **Pinch (Thumb & Index)**: Zoom in and out of the scene.
  - **Left/Right Movement**: Rotate the particle system.
  - **Hover**: Repel particles near your index finger.
- **Responsive Design**: Optimised for various screen sizes and modern web browsers.

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- A modern web browser with webcam access

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sabireem/sphere-.git
   cd sphere
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

The application will be available at `http://localhost:5173`.

## 🛠️ Technical Stack

- **React** (v19): Component-based UI framework.
- **Three.js** & **React Three Fiber**: 3D rendering engine and its React bindings.
- **React Three Drei**: Useful helpers for Three.js.
- **MediaPipe Hands**: Real-time hand landmark detection.
- **Vite**: Ultra-fast frontend build tool.

## 📁 Project Structure

```text
sphere/
├── src/
│   ├── App.jsx        # Main application logic, hand tracking integration, and 3D scene
│   ├── App.css        # Interactive UI styling
│   ├── main.jsx       # Application entry point
│   └── index.css      # Global styles
├── public/            # Static assets (logos, images)
├── index.html         # HTML template with MediaPipe CDN links
└── vite.config.js     # Vite configuration
```

## 🎮 Interaction Guide

| Control | Action |
| :--- | :--- |
| **Pinch Fingers** | Zoom In / Out |
| **Move Hand L/R** | Rotate Scene |
| **Index Finger Hover** | Interact with Particles |
| **Shape Buttons** | Change Particle Formation |
| **+/- Buttons** | Manual Zoom |
| **Rotate Buttons** | Manual Rotation |

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to get started.

## 📄 License

This project is open-source. Created by Sabi.
