# Indian Currency Recognition WebApp

<p align="left">
  <a href="https://universe.roboflow.com/daniel-raj-c/currency-recognition-model-g16wl">
    <img src="https://app.roboflow.com/images/download-dataset-badge.svg" alt="Download Dataset">
  </a>
  <a href="https://universe.roboflow.com/daniel-raj-c/currency-recognition-model-g16wl/model/">
    <img src="https://app.roboflow.com/images/try-model-badge.svg" alt="Try Model">
  </a>
</p>

This is a web-based demonstration app for detecting and classifying Indian currency notes using a Roboflow-trained instance segmentation model. The app enables real-time inference directly from uploaded images or webcam input, labeling each note with its denomination.

> 🎯 Model URL: [Currency Recognition Model - Roboflow](https://app.roboflow.com/daniel-raj-c/currency-recognition-model-g16wl)

---

## 🔍 Features

- 🧠 Real-time inference using Roboflow API
- 📷 Upload images or use your webcam
- 🧾 Detects and labels Indian currency notes
- 🔲 Instance segmentation with bounding boxes
- ⚡️ Fully browser-based (no backend server needed)

---

## 🧠 Model Details

- **Model Type**: Instance Segmentation
- **Platform**: [Roboflow](https://roboflow.com/)
- **Classes**:
  - ₹0, ₹1, ₹2, ₹5, ₹10, ₹20, ₹50, ₹100, ₹200, ₹500
- **Use Case**: Currency recognition for education, accessibility tools, low-vision user aid, kiosk automation, etc.

---

## 🚀 Live Demo

> 🌐 GitHub Pages link ([Click-here](https://danielrajchristeen.github.io/Indian-Currency-Recognition-Model/))

You can test this model directly from your browser using:
- **Uploaded images**
- **Live webcam feed**

---

## 🛠️ How to Use

### 🔗 Clone the Repository

```bash
git clone https://github.com/yourusername/currency-recognition-webapp.git
cd currency-recognition-webapp
````

### 🖥️ Open the App

Simply open `index.html` in your browser:

```bash
start index.html     # For Windows
open index.html      # For macOS
xdg-open index.html  # For Linux
```

---

## 🛠️ Project Structure

```
currency-recognition-webapp/
├── index.html        # Main webpage
├── script.js         # JS logic (Roboflow API + webcam)
├── style.css         # Basic styling
├── sample-image.png  # Example image (optional)
└── README.md         # This file
```

---

## 🔐 Setup API Access (Important)

Replace the placeholder API key in `script.js` with your actual Roboflow API key:

```js
const model = await roboflow.load({
  model: "currency-recognition-model",
  version: 1,
  api_key: "YOUR_ROBOFLOW_API_KEY"
});
```

Get your API key from: [https://app.roboflow.com](https://app.roboflow.com)

---

## 📡 Deploying to GitHub Pages

You can host this app **for free** using GitHub Pages:

1. Push the repo to your GitHub account
2. Go to **Settings → Pages**
3. Select the branch (e.g., `main`) and root folder
4. Save and access your live demo via the generated URL

---

## 🤝 Credits

* **Roboflow** – For providing tools to build and host the model
* **Daniel Raj Christeen** – Developer of this demo project

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

### 🙌 Contributions

Feel free to open issues, fork, or create pull requests to enhance this project!

---

### 🌟 Don't forget to ⭐ the repository if you found this useful!

Let me know if you'd like me to:

- Generate the `index.html`, `script.js`, and `style.css` templates
- Help you deploy it directly to GitHub Pages
- Customize the README for academic portfolio or LinkedIn use

I'm happy to help!

---

### Thank you for the supports 🙏
