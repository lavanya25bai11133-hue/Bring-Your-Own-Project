# Bring your own project: AI-Powered Color Correction for Color Blindness

An accessible computer vision tool designed to help individuals with color vision deficiencies (CVD) perceive color differences more effectively in real-time.

## 🎯 The Aim
The primary goal of this project is to develop a deep-learning-powered filter that adjusts digital images and video feeds to enhance contrast and color visibility for users with Protanopia, Deuteranopia, and Tritanopia.

## ⚠️ The Problem
Most digital content is designed for trichromatic vision. For the millions of people with color blindness, critical information—such as UI elements, maps, or educational graphics—can become indistinguishable. 
* **The Gap:** Standard "color-blind modes" are often static and don't always adapt well to complex, high-contrast digital environments.

## 💡 The Solution
VisionBridge uses a **U-Net architecture** to perform image-to-image translation. 
1. **Simulation:** It analyzes how an image looks to someone with a specific type of CVD.
2. **Correction:** The model applies a compensating shift in the color spectrum, enhancing the "lost" contrast so that the user can distinguish between previously identical-looking shades.
3. **Interface:** Powered by **Gradio**, the tool provides an easy-to-use web interface where users can upload images or use a webcam to see corrected results instantly.

## 🚀 Key Uses
* **Web Accessibility:** Helping users navigate color-coded websites.
* **Education:** Assisting students in viewing scientific charts or historical maps.
* **UI/UX Testing:** Allowing designers to simulate and then fix accessibility issues in their prototypes.
## How to test the code
* 1. Download the color_blindness.ipynb file.
* 2. Open it on Google colab and run all the code.
* 3. Then the web interface will come.
* 4. Upload your image,Select your colour blindness type and then hit submit.
* 5. You will get your results.
