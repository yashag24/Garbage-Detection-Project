# 🚮 Garbage Detection Project 🗑️📸

This project detects roadside garbage using **MobileNetV2** and sends **notifications** when garbage is detected. The system stores images in **MongoDB**, processes them using a trained model, and triggers **email alerts** if garbage is found. 📩⚡

---

## 🛠 Setup Instructions 🚀

### 1️⃣ Install Dependencies 📦
Run the following command to install required packages:

```bash
pip install -r requirements.txt
```

### 2️⃣ Configure Environment Variables 🔧
Create a `.env` file in the project root and add the following details:

```ini

# 📧 Email Notification Configuration  
FROM_EMAIL=your-email@gmail.com  
EMAIL_PASSWORD=your-email-password  
TO_EMAIL=receiver-email@gmail.com 
MODEL_PATH=yourModelPath
STREET_NAME=yourStreetName
```

---

## 🏗️ Project Workflow 🔄

1️⃣ **Camera** captures an image 🎥  
2️⃣ Sends the image to your **backend** via API 🌐  
3️⃣ Backend processes the image and runs the **MobileNetV2 model** 🧠  
4️⃣ If classified as **Garbage**, trigger a **notification** 📲🚨  

---

## ✨ Features ✨

✅ **Real-time garbage detection** 🏙️  
✅ **Stores images securely in MongoDB** 🗄️  
✅ **Email alerts when garbage is found** 📧  
✅ **Geolocation tracking of detected garbage** 📍  
✅ **Easy setup & deployment** 🚀  

---

## 🤝 Contributing 🤝

Feel free to submit issues or pull requests! Let's make this project better together. 💡✨

