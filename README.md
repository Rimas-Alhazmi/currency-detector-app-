# 💵 Saudi Currency Detector & Fake Note Identifier

A real-time intelligent system that doesn't just recognize **Saudi banknotes** — it detects **fakes too**.  
Built with love, Streamlit, and Computer Vision. 🇸🇦❤️💻

---

## 🎯 What This App Does

Have a mix of bills in your hand?  
This app captures them **live from your camera**, identifies **each denomination**, and even warns you if one is **fake** — all in a split second.

✔️ Detects **multiple banknotes** in a single shot  
✔️ Uses **SIFT + FLANN** for robust image matching  
✔️ Detects **counterfeit notes** via color + edge analysis  
✔️ Instantly shows total value in **SAR, USD, and EUR**  
✔️ Built with **Streamlit** — intuitive and beautiful UI

---

## 📸 How It Works

1. 📷 Capture live image from webcam  
2. 🧠 Detect each note via **contour detection**  
3. 🔍 Extract features using **SIFT**  
4. ⚡ Match against real notes using **FLANN**  
5. 🧪 Run fake detection using:
   - Average color deviation
   - Edge density analysis  
6. 💰 Output total amount + converted values  
7. 🔊 [Future] Add voice alerts and multi-currency options

---

> ⚠️ **Note**: The file `descriptors.pkl` is excluded from this repository due to GitHub’s size limits.  
> After cloning, run:  
> ```bash
> python prepare_descriptors.py
> ```

---

## 🚀 How to Run Locally

1. Install dependencies:
```bash
pip install opencv-python streamlit

Generate descriptors:
python prepare_descriptors.py

Launch the app:
streamlit run app.py

🎓 AI385 - Computer Vision | Spring 2025
🧑‍🏫 Instructors: Dr. Ahmed Elhayek & Dr. Reem Aljuhani
🏛️ University of Prince Mugrin


