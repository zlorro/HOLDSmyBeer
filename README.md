# 🍺 HOLDSmyBeer
### _Computer Vision for Indoor Climbing — because routes don’t set themselves._

> A playground for experimenting with **object detection**, **LiDAR scans**, and **AR overlays** in indoor climbing.
> Built to teach computers how to spot climbing holds and turn walls into data.

---

## 🧩 What It Is

**HOLDSmyBeer** is a prototyping lab for computer vision in climbing gyms.  
We’re exploring how a phone camera (or LiDAR) can recognize:

- 🧱 **Climbing holds** — detect, classify, and match them to a database  
- 🧗 **Routes** — combinations of holds + wall geometry  
- 🕶️ **Surfaces in AR** — for projecting and installing routes in the real world  

It’s an open sandbox to experiment, not a product (yet).

---

## ⚙️ Tech Stack MVP (for now)

| Layer | Tools |
|-------|-------|
| 🧠 Detection | YOLOv8 (Ultralytics) + OpenCV |
| 💾 Data | Roboflow (datasets) + Google Drive |
| 🧪 Training | Google Colab + free GPU |
| ☁️ Versioning | GitHub |
| 🧱 Backend (later) | Firebase / Xano |
| 🎮 AR Visualization (later) | Unity + AR Foundation |

---

## 🚀 Quickstart (Concept Flow)

1. Capture images of climbing walls 🧱  
2. Annotate holds online via Roboflow  
3. Train a YOLOv8 model in Google Colab  
4. Run detection & visualize results  
5. Push your progress here and brag 🍺  

---

> _“If you can’t climb it — at least train the AI to find it.”_

---

**Maintained by [@zlorro](https://github.com/zlorro)**
