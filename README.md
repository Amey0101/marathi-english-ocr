# marathi-english-ocr

Marathi & English Web OCR 📝
A lightweight, browser-based Optical Character Recognition (OCR) tool that extracts Marathi and English text from images. Built with plain HTML, CSS, JavaScript, and powered by Tesseract.js.
✨ Features
 * Bilingual Support: Extract English, Marathi, or both languages simultaneously from a single image.
 * Drag & Drop Interface: Easily upload images by dragging them into the drop zone or clicking to browse.
 * Real-time Progress: Visual progress bar and status text showing the initialization and recognition phases.
 * 100% Client-Side: All image processing happens directly in your browser. Your images are never uploaded to a server, ensuring complete privacy.
 * No Installation Required: Runs entirely from a single HTML file.
🚀 How to Use
 * Clone or Download:
   git clone https://github.com/yourusername/marathi-english-ocr.git
 * Open the App: Simply double-click the OCR.html file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
 * Select Languages: Check the boxes for English, Marathi, or both depending on the text in your image.
 * Upload an Image: Drag and drop an image file into the dashed box or click to select a file from your device.
 * Extract Text: Click the "Recognize Text" button and wait for the progress bar to complete. The extracted text will appear at the bottom of the page.
🛠️ Tech Stack
 * HTML5 / CSS3 / JavaScript (Vanilla)
 * Tesseract.js (Loaded via CDN for optical character recognition)
⚠️ Important Note
While the application processes images locally, it requires an active internet connection the very first time you use it to download the Tesseract.js core engine and the specific language training data (eng.traineddata and mar.traineddata). These are cached in your browser for subsequent uses.
🤝 Contributing
Contributions, issues, and feature requests are welcome. Feel free to fork the repository and submit a pull request!
📝 License
This project is open-source and available under the MIT License.
