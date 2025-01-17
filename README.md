
# Interactive Particle Animation with Social Links

This project showcases an **interactive particle animation** built using `threejs-toys`, along with integrated social media links for **Telegram** and **YouTube**. The project is designed to provide an engaging and visually appealing experience.

---

## Features

- **Dynamic Particle Animation**: Interactive particles follow the cursor and change properties dynamically on click.
- **Responsive Design**: Works seamlessly across all devices and screen sizes.
- **Social Media Links**: Easy access to Telegram and YouTube with beautifully styled links.
- **Customizable**: Fully customizable colors, animations, and styles.

---

## Project Structure

```
.
index.html        # Main HTML file
style.css         # CSS file for styling
script.js         # JavaScript file for animations and interactivity
README.md         # Documentation
```

---

## Preview

### Particle Animation

![Particle Animation Preview](https://via.placeholder.com/800x400?text=Particle+Animation+Preview)

### Social Links

- **Telegram**: [Join my Telegram](https://t.me/+7yc_oGHnLJhlOWVl)
- **YouTube**: [Subscribe to my YouTube Channel](https://www.youtube.com/@codewith_muhilan?sub_confirmation=1)

![Social Links Preview](https://via.placeholder.com/800x400?text=Social+Links+Preview)

---

## Getting Started

Follow these steps to set up and run the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/interactive-particle-animation.git
   cd interactive-particle-animation
   ```

2. **Open the project**:
   Open `index.html` in your browser.

3. **Enjoy the animation**:
   - Move your cursor to see the particle effects.
   - Click anywhere to dynamically change particle properties.

---

## Customization

### Particle Animation
Modify the animation properties in `script.js`:

```javascript
const pc = particlesCursor({
    colors: [0xFFD700, 0xFF5733], // Custom colors
    coordScale: 0.5,              // Adjust scale
    noiseIntensity: 0.005,        // Noise effect
    pointSize: 2                  // Particle size
});
```

### Social Links
Update the links in `index.html` to your own:

- **Telegram**:
  ```html
  <a id="source-link" class="meta-link" href="https://t.me/your-telegram-link" target="_blank">
  ```
- **YouTube**:
  ```html
  <a id="yt-link" class="meta-link" href="https://www.youtube.com/your-channel-link" target="_blank">
  ```

---

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling and layout.
- **JavaScript (ES6+)**: For interactivity and animations.
- **Three.js**: For rendering the particle effects.
- **Font Awesome**: For icons used in social links.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- **Three.js Toys**: For the particle animation library.
- **Font Awesome**: For the beautiful icons.
- **Developer Community**: For inspiration and resources.

---

Feel free to contribute by submitting issues or pull requests! 