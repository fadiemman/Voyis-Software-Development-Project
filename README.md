# 🚀 Voyis 3D Viewer with GIS Integration

A lightweight **web-based** application to visualize **3D Point Cloud Data** and **GIS Maps** using an interactive interface. This project supports **PCD, XYZ, and GeoJSON** file formats, with features like **altitude-based color filtering, time-series animation, and metadata display.**

![Voyis 3D Viewer](assets/voyis-logo.png)

---

## 📌 Features
✔️ **3D Point Cloud Visualization** using `three.js`  
✔️ **GIS Mapping** with `leaflet.js`  
✔️ **Interactive UI** with pan, zoom, and rotation  
✔️ **Dynamic Altitude-Based Color Filtering**  
✔️ **Time-Series Animation for GIS Data**  
✔️ **Metadata Display** (e.g., Coordinates, Tags, Timestamps)  
✔️ **Dark Mode & Light Mode Toggle**  
✔️ **Upload Support**: `.pcd`, `.xyz`, `.geojson`, `.json`  

---

## 🛠️ Installation & Setup

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/fadiemman/Voyis-Software-Development-Project.git
cd Voyis-Software-Development-Project
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Run the Development Server**
```sh
npm run dev
```
👉 The app will start at: **`http://localhost:5173/`**

---

## 📂 Folder Structure
```
/Voyis-3D-Viewer
├── src/                
│   ├── components/     
│   ├── styles/         
│   ├── utils/          
|   |── context/
|   |── pages/
│   ├── assets/         
├── public/             
├── package.json        
├── vite.config.js      
├── README.md           
```

---

## 📸 Screenshots
### **Main Interface**
![Main UI](assets/main-interface.jpg)

### **3D Point Cloud Viewer**
![3D Viewer](assets/3D-point-cloud.jpg)

### **GIS Map with Metadata**
![GIS Map](assets/gis-map.jpg)

---

## 📦 Build for Production
```sh
npm run build
```
This creates an optimized production build inside the `/dist` folder.

---

## 🤝 Contributing
Contributions are welcome!  
- Open an issue for bug reports or feature requests.  
- Feel free to fork the project and submit pull requests.

---

### **🎉 Thank you for using Voyis 3D Viewer!**
If you find this project useful, consider giving it a ⭐ on **GitHub**! 🚀

