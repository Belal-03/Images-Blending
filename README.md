# 🖼️ Alpha Compositing (Alpha Blending) Project

This project demonstrates **alpha blending**, a technique used to combine a foreground image with a background image using transparency (alpha) values. The resulting image simulates partial or full transparency, creating a realistic and visually appealing composite.

---

## 🎯 Overview

**Alpha compositing**, also known as **alpha blending**, is a fundamental technique in image processing and computer graphics. It blends two images based on alpha values (transparency levels), allowing for effects like translucency, ghosting, overlays, and layer merging.

The final composite image is computed as:

output_pixel = alpha * foreground_pixel + (1 - alpha) * background_pixel

## 🧰 Features

- Loads two input images (foreground and background).
- Applies alpha blending with customizable transparency.
- Displays and optionally saves the final composite image.
- Supports alpha channel or manual blending factor.

---

## 📁 Input

Use any two images:
- **Background image** (e.g., `background.png`)
- **Foreground image** (e.g., `foreground.png`)

Ensure both images are the same size, or apply resizing before blending.

---

## 🧮 How It Works

1. Read both images using OpenCV or PIL.
2. Resize if the dimensions mismatch.
3. Apply alpha blending pixel-by-pixel or via matrix operations.
4. Display the composite result.
5. Save it if needed.
تحرير
