# 🎨 Color Palette Generator – RGB, HEX & HSL

This project extracts dominant colors from images and converts them into RGB, HEX, and HSL formats. It's designed for designers, developers, and data enthusiasts looking to analyze or generate color palettes from any image.

---

## 📂 Project Structure

color-palette-generator-hsl-rgb/ │ ├── images/ # Sample images for color extraction ├── src/ # Python scripts for processing │ └── color_utils.py # Color conversion & extraction functions ├── palettes/ # Generated palettes (optional) ├── requirements.txt # Python dependencies └── README.md # Project documentation


---

## 🧠 Features

- Extracts pixel colors from an image
- Identifies dominant colors using clustering (K-Means)
- Converts RGB values to HEX and HSL
- Displays visual palette preview

---

## 🛠️ Tools & Libraries

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn (for K-Means)

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/color-palette-generator-hsl-rgb.git
   cd color-palette-generator-hsl-rgb

    Install dependencies:

pip install -r requirements.txt

Run the main script:

    python src/color_utils.py --image images/sample.jpg

📸 Output Example

    HEX: #ff5733, #33d4aa

    RGB: (255, 87, 51)

    HSL: (9°, 100%, 60%)

Generated palettes can be saved or visualized as a color bar.
📄 License

Open-source for learning, testing, and creative applications. Attribution appreciated!
