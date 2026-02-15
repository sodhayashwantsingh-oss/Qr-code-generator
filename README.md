# Qr-code-generator
🔳 QR Code Generator

A simple and responsive QR Code Generator Web Application built using HTML, CSS, and JavaScript.
This application allows users to generate QR codes instantly by entering text or a URL.

🚀 Live Demo

(Add your GitHub Pages link here if deployed)

📌 Features

🔤 Generate QR code from text or URL

⚡ Instant QR code generation

📱 Responsive design

🎨 Clean and modern UI

🖼 Download QR code image (if implemented)

❌ Input validation for empty fields

🛠 Technologies Used

HTML5 – Structure of the web page

CSS3 – Styling and layout

JavaScript (Vanilla JS) – Functionality

QR Code API / Library (e.g., qrcode.js or Google Chart API)

📂 Project Structure
QR-Code-Generator/
│
├── index.html
├── style.css
├── script.js
└── README.md

💡 How It Works

User enters text or URL.

JavaScript captures the input value.

A QR code is generated using a QR code library or API.

The QR code is displayed dynamically on the webpage.

Example logic:

function generateQR() {
   let input = document.getElementById("qr-text").value;
   new QRCode(document.getElementById("qr-code"), input);
}

▶ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/QR-Code-Generator.git


Open the project folder.

Double-click index.html.

Start generating QR codes 🎉

No installation required.
