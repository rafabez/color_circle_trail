# Color Circle Trails 🎨✨

**Color Circle Trails** is an interactive visual experience that combines stunning canvas-based particle effects with dynamic audio, powered by the Tone.js library. Explore the magic of vibrant circles that trail your movements and generate unique sounds as you interact. Reset the experience at any time with a simple double-click.

---

## 🌟 Key Features

### ✨ Dynamic Particle Effects
- Particles appear where you move your cursor or touch the screen, leaving colorful trails that shrink and fade gracefully.
- Each particle has a unique size, color, and movement, creating a mesmerizing visual tapestry.

### 🎵 Audio Integration
- Generate real-time sound effects as you interact, with audio pitch based on your cursor's vertical position.
- Powered by the **Tone.js** library, this feature adds an engaging auditory dimension to the visuals.

### 📱 Fully Responsive Design
- The canvas dynamically resizes to fit any screen size, providing a seamless experience on both desktop and mobile devices.

### 🎮 Intuitive User Interactions
- **Mouse**: Move your cursor across the canvas to create trails.
- **Touch**: Drag your finger across the screen on touch devices to interact.
- **Double-Click**: Reset the canvas and start fresh.

---

## 🌐 Live Demo

Experience it live at: [Color Circle Trails Demo](https://rafabeznos.com.br/#/10/color_circle_trail)

---

## 📖 How It Works

### Responsive Canvas
The canvas adjusts to the viewport size dynamically, ensuring that the visuals fit perfectly on any screen. This is achieved using a `resize` event listener in JavaScript.

### Particle System
1. **Creation**:
   - Particles are generated at the cursor's position during `mousemove` or `touchmove` events.
   - Each particle is assigned a random size, color, and speed, making every interaction unique.

2. **Behavior**:
   - Particles shrink over time until they disappear.
   - The system continuously cleans up old particles to maintain performance.

### Dynamic Audio
- A sine wave synthesizer creates sound effects triggered by particle generation.
- The pitch of the sound corresponds to the vertical position of the interaction, providing an immersive auditory experience.

---

## 📂 Project Structure

```plaintext
color_circle_trails/
├── index.html    # Main HTML file with embedded JavaScript
└── README.md     # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/rafabez/color_circle_trails.git
   cd color_circle_trails
   ```
2. Open the `index.html` file in your preferred browser.

### Usage
- **Move your cursor** or **drag your finger** to interact with the canvas.
- Enjoy the combination of visuals and sounds.
- **Double-click** anywhere on the canvas to reset the animation.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for enhancing the project, feel free to:
- Fork the repository.
- Create a feature branch.
- Submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 👨‍💻 Author

Created with 💖 by **[rafabez](https://github.com/rafabez)**. Explore more of my work on [rafabeznos.com.br](https://rafabeznos.com.br/).

---

## 📸 Screenshots

*(Optional: Add screenshots or GIFs to showcase the project)*

---

Enjoy creating with **Color Circle Trails** and let your imagination run wild! 🌈🎶
