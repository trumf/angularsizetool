# Screen Measurement Converter

A lightweight, zero-dependency web tool for designers and developers to convert between pixels (px), millimeters (mm), and visual angle (arc minutes). Simply open the HTML file in your browser—no build step or server required.

---

## Features

- **Compute mm per pixel**: Calculate your screen’s mm/px ratio based on physical width (mm) and pixel resolution.
- **Convert values**: Instantly convert any number between px, mm, and arc minutes.
- **Common benchmarks**: One-click conversion for standard values (e.g., 16 px, 5 mm, 20 arc min).
- **Visual feedback**: Highlighted results and toast notifications for errors or successful ratio calculation.
- **Responsive layout**: Adapts to mobile and desktop screen sizes.

---

## Getting Started

1. **Clone or download** this repository.
2. **Open** `index.html` in your favorite web browser.

No additional dependencies or build tools are required.

---

## Usage

1. **Step 1 – Compute Ratio**

   - Enter your screen width in millimeters and the total pixel width.
   - Enter your viewing distance in centimeters.
   - Click **Compute Ratio** to set the conversion factors.

2. **Step 2 – Convert Measurements**

   - Choose which unit to convert:

     - **Pixels → mm & arc min**
     - **mm → px & arc min**
     - **Arc min → px & mm**

   - Enter the value and click **Convert**.

3. **Step 3 – Common Conversions**

   - View instantly computed results for preset values (e.g., 16 px → mm).

---

## Customization

- Edit the CSS variables in `index.html`’s `<style>` block to match your brand colors and typography.
- Adjust default input values or add new presets in the HTML if needed.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for bug fixes and improvements.

---

## License

This project is licensed under the [MIT License](LICENSE).
