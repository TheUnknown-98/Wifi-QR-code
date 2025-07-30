# WiFi QR Code Generator

A modern Python GUI tool to generate scannable WiFi QR codes.  
Easily share your WiFi credentials by letting others scan a QR code instead of typing passwords.

---

## ✨ Features
- Generate QR codes for **WPA**, **WEP**, or **Open** networks  
- **Show/Hide password** toggle  
- **Hidden SSID** support  
- **Responsive dark UI** with `ttkbootstrap`  
- **Save QR codes** as PNG images  

---

## 📦 Requirements
Install the required dependencies:
```bash
pip install ttkbootstrap pillow qrcode
```

---

## ▶️ Usage
1. Run the app:
   ```bash
   python wifi_qr_generator.py
   ```
2. Enter your WiFi details (SSID, password, and security type)  
3. Click **Generate QR Code**  
4. Optionally **Save** the QR as a PNG file  

---

## 🛠 Tech Stack
- **Python 3**  
- **Tkinter + ttkbootstrap** (GUI)  
- **Pillow** (Image handling)  
- **qrcode** (QR code generation)  
