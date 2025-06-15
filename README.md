# 🎨 CartoonifyCam

Turn your live webcam feed or uploaded images into cartoon-style artwork with just one click — no training, no datasets, just OpenCV magic!

---

## 🚀 Features

- 📷 Capture photos directly from your **webcam** (Colab compatible)
- 🧠 Real-time cartoonification using **OpenCV filters**
- 💡 Clean edges and smooth color blending
- 🖼️ Supports high-resolution output (up to 960x720 or more)
- ✅ No ML models or datasets required

---

## 🛠️ How It Works

The app uses a combination of:
- **Grayscale conversion**
- **Median blur** for noise reduction
- **Adaptive thresholding** for edge detection
- **Bilateral filtering** for color smoothing
- Final touch with **Gaussian blur** for a comic feel

---

## 📂 Files

| File Name                  | Description                           |
|----------------------------|---------------------------------------|
| `cartoonify_cam_colab.ipynb` | Main notebook for Google Colab         |
| `cartoonified_output.jpg`   | Saved result from last execution      |

---

## 🧪 Try It Out in Google Colab

1. Upload the notebook
2. Run each cell one by one
3. When prompted, click 📷 **Capture** to take a webcam shot
4. Wait 1–2 seconds for cartoonified output
5. Download your image!

---

## 📸 Sample Output

> Input  
![input](input_sample.jpg)

> Cartoonified  
![output](cartoonified_output.jpg)

---

## 📦 Requirements

```bash
pip install opencv-python pillow
```

Or in Colab, use

```bash
!pip install opencv-python pillow

```

---

## 🪪 License
This project is licensed under the MIT License.

---

## 🙌 Credits
Created with ❤️ by Lucky Joy Tutika
🔗 [linkedin.com/](https://www.linkedin.com/in/lucky-joy-tutika/)
