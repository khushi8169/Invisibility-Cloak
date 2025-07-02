# Invisible Cloak using OpenCV

Create your own **Harry Potter-style invisible cloak** using Python and OpenCV! This fun and beginner-friendly computer vision project detects a specific color (like green) and replaces it with the static background to create the illusion of invisibility in real time.

---

## Technologies Used

* **Python 3**
* **OpenCV (cv2)**
* **NumPy**

---

## How It Works

1. Captures the static background without the subject.
2. Detects a specific color (e.g., green) in the live video stream.
3. Replaces the detected region with the previously captured background.
4. Applies image processing techniques to remove noise and improve quality.
5. Result: The person wearing the cloak appears *invisible* on screen!

---

## Try It Yourself

1. Wear a **green-colored cloth** (you can modify the HSV values for red, blue, etc.).

2. Make sure the background is captured **without you** in the frame.

3. Run the script:

   ```bash
   python cloak.py
   ```

4. Watch yourself disappear in real time! 🪄

---

## Features

* Real-time invisibility effect
* Customizable color detection (via HSV)
* Noise removal using morphological operations
* Smooth blending of foreground and background

---

## Customization

* 🎨 **Change cloak color**: Modify `lower_green` and `upper_green` HSV values in the script to use red, blue, or any other color.
* 📹 **Record Output**: Add `cv2.VideoWriter` to save the cloaked video.
* 🧪 **Live HSV Range Tuner**: Add trackbars to experiment with different HSV values live.

---

## What You Learn

* Real-time image segmentation
* Color detection using HSV
* Morphological filtering (open, close, dilation)
* Bitwise image operations in OpenCV
* Basics of computer vision with Python

---
