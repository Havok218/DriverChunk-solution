# DriverChunk

**DriverChunk** is a lightweight Windows desktop utility (built as an HTA - HTML Application) that scans your system for installed drivers, identifies missing or faulty drivers by vendor, and provides direct links to official driver download pages.

---

## 🚀 Features

- ✅ **Displays Installed Drivers**  
  Lists all signed drivers installed on the system.

- 🧠 **Smart Missing Driver Detection**  
  Checks for devices with error codes and matches them against known vendors.

- 🔍 **System Overview**  
  Displays basic system details including manufacturer, model, OS version, memory, and processor.

- 🌐 **Official Download Links**  
  Provides vendor-specific download links for missing drivers.

---

## 🖥️ How to Use

1. **Download the file:**  
   Extract it.

2. **Double-click the file:**  
   It will launch like a Windows desktop app with a GUI.

3. **View results:**  
   - Top: System Info  
   - Middle: Installed Drivers  
   - Bottom: Missing Drivers (with download links)

---

## 📁 Example Vendors Supported

- Intel  
- AMD  
- NVIDIA  
- Realtek  
- Qualcomm  
- Broadcom

More can be added by editing the VBScript section inside the file.

---

## 🛠 Technical Details

- **Technology**: VBScript + HTML + CSS (inside `.hta`)  
- **WMI Queries Used**:
  - `Win32_ComputerSystem`
  - `Win32_OperatingSystem`
  - `Win32_Processor`
  - `Win32_PnPSignedDriver`
  - `Win32_PnPEntity`

---

## 🔒 Requirements

- Windows 7, 8, 10, or 11  
- Must be run with **HTA support enabled** (enabled by default on Windows)  
- No admin rights required

---

## ⚠️ Disclaimer

This tool **does not install any drivers**. It helps you **identify** missing drivers and provides safe download links. Always ensure you download drivers from official vendor websites.

---

## 📸 Screenshot

![DriverChunk Screenshot](https://via.placeholder.com/900x500?text=DriverChunk+GUI+Placeholder)

---

## 📄 License

This project is released under the MIT License.

---

## 🧠 Future Enhancements (Ideas)

- Export driver list to file  
- Add “Copy Link” buttons  
- Dark mode  
- Auto-refresh on startup  

---
