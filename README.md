# AMA Campus Object Scanner & Approval System

A complete, self-contained single-file HTML application designed for **AMA Computer College - Lipa Campus**, providing secure item registration, administrative approval, unique QR code generation/printing, and a real-time guard scanner module for campus entry and exit clearance.

## 🚀 Features

* **User Request Portal**: Students, faculty, staff, and visitors can submit item pass requests with detailed information (Name, Role, ID Number, Item Model, Category, and Purpose).
* **Admin Approval Dashboard**: Securely protected by password authorization (`AMACCLIPA2026`), allowing administrators to review, approve, or reject pending item requests in real time.
* **Unique QR Code Generation & Printing**: Approved items automatically generate a unique tracking reference (e.g., `AMA-OBJ-XXXXXX`) and render an official printable campus pass complete with AMA Lipa branding.
* **Guard Scanner & In/Out Log Module**: Equipped with live camera scanning (via `html5-qrcode`) and manual token entry. Guards can verify clearance status and log items as **IN** or **OUT** with timestamps.
* **Data Persistence**: Fully functional client-side storage utilizing `localStorage` to retain records across page refreshes.

---

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
* **UI Framework**: Bootstrap 5 (`v5.3.2`)
* **Icons**: FontAwesome (`v6.4.0`)
* **Libraries**: 
  * `qrcode.js` (Dynamic QR generation)
  * `html5-qrcode` (Live camera stream scanning)

---

## 🔒 Security & Default Credentials

* **Admin Password**: `AMACCLIPA2026`

---

## 📦 Installation & Usage

Since this is a **self-contained single-file application**, no complex backend setup or package installation is required!

1. Download or clone this repository.
2. Save the file as `index.html`.
3. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
