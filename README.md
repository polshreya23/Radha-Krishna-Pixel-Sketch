# 🎨 Radha Krishna Pixel Sketch Animation

A beautiful Python Tkinter application that recreates a **Radha Krishna image** through a cinematic two-stage animation.

The program first draws a **pencil sketch** of the image pixel by pixel and then gradually fills it with glowing colors before finally revealing the original high-quality image.

---

## 📸 Preview

### Animation Stages

1. ✏️ Pencil Sketch Drawing
2. 🌈 Pixel-by-Pixel Color Fill
3. ✨ Final High-Resolution Image Reveal

---

## ✨ Features

- Cinematic pencil sketch animation
- Pixel-by-pixel color rendering
- Neon glow effects
- Smooth animation using Tkinter
- Automatic image scaling for any screen size
- Fullscreen viewing mode
- ESC key support to exit
- Lightweight and easy to run

---

## 🛠 Technologies Used

- Python 3
- Tkinter
- Pillow (PIL)

---

## 📂 Project Structure

```
Radha-Krishna-Pixel-Sketch/
│
├── main.py
├── radha_krishna_original.jpg
├── README.md
└── requirements.txt
```

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Radha-Krishna-Pixel-Sketch.git
```

---

### 2. Open the project folder

```bash
cd Radha-Krishna-Pixel-Sketch
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install pillow
```

---

## ▶️ Run the Project

```bash
python main.py
```

The application will automatically open in fullscreen mode.

Press **ESC** anytime to close it.

---

## ⚙️ How It Works

### Stage 1 — Pencil Sketch

- Converts the image into grayscale.
- Detects edges using Pillow.
- Draws thousands of tiny pencil strokes on the canvas.
- Creates the effect of hand sketching.

---

### Stage 2 — Color Fill

After the sketch is complete,

- Random color blocks begin filling the image.
- Bright pixels receive custom glow colors.
- The image slowly comes to life.

---

### Stage 3 — Final Reveal

The completed sketch is replaced with the original high-quality image for a smooth cinematic finish.

---

## 🎨 Glow Color Mapping

| Dominant Color | Glow |
|---------------|------|
| Blue | Cyan |
| Pink/Magenta | Pink |
| Orange/Yellow | Gold |
| Purple | Purple |
| Others | Original Color |

---

## ⚡ Customization

You can easily modify these values inside the code.

```python
PENCIL_POINTS_PER_FRAME = 180
COLOR_BLOCKS_PER_FRAME = 120
BLOCK_SIZE = 3
FRAME_DELAY = 10
```

Increasing the values makes the animation faster.

Reducing them makes it slower and more cinematic.

---

## 📌 Requirements

- Python 3.10+
- Pillow

---

## 📷 Image

Replace

```
radha_krishna_original.jpg
```

with your own image to generate a new animation.

The program automatically resizes it to fit your screen.

---

## 🚀 Future Improvements

- Multiple sketch styles
- Different brush effects
- Video export support
- GIF export
- Adjustable animation speed
- Music synchronization
- Particle effects
- Image selection through file dialog

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork the repository and submit a Pull Request.

---

## 📜 License

This project is released under the MIT License.

---

## 👩‍💻 Author

**Shreya Pol**

Computer Engineering Student

Interested in Python, AI, Computer Vision, and Creative Programming.

If you found this project helpful, don't forget to ⭐ star the repository!
