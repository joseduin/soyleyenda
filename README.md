# Soy Leyenda - Web Reader

This project is a web application designed to read the novel "I Am Legend" ("Soy Leyenda") by Richard Matheson directly from your browser. It was developed to offer a comfortable, responsive, and locally accessible reading experience on any device.

## 📖 About the Project

The application loads the complete content of the book and presents it in a clean interface organized by chapters. It uses **AngularJS** for dynamic data handling and **Bootstrap** along with **AdminLTE** to ensure a responsive design that looks good on desktops, tablets, and mobile devices.

### Features
- **Complete Reading**: Contains the full novel divided by chapters.
- **Responsive Design**: Adapts to mobile, tablet, and desktop screens.
- **Simple Navigation**: Chapter index for quick access.
- **Local Mode**: Works perfectly offline once downloaded (depending on cached external libraries or if downloaded locally).

## 🚀 How to Run Locally

To view the project on your device:

### Option 1: Open Directly (Basic)
1. Download the repository or project files.
2. Double-click the `index.html` file.
3. The book should open in your default browser.

*Note: Some browsers may restrict local script execution. If you don't see the content, try Option 2.*

### Option 2: Using a Local Server (Recommended)
To ensure all components load correctly (especially if you plan to access it from your mobile on the same WiFi network):

1. **With Python (if installed):**
   - Open a terminal in the project folder.
   - Run: `python3 -m http.server` (or `python -m SimpleHTTPServer`).
   - Open your browser at `http://localhost:8000`.

2. **With VS Code (Live Server):**
   - Install the "Live Server" extension.
   - Right-click on `index.html` and select "Open with Live Server".

3. **Node.js (http-server):**
   - If you have Node.js, you can use `npx http-server .`

## 📱 View on Mobile

If you use **Option 2** and your computer and mobile are on the same WiFi network:
1. Find your computer's local IP address (e.g., `192.168.1.5`).
2. In your mobile browser, type that IP followed by the port (e.g., `http://192.168.1.5:8000`).
3. Enjoy reading on your device!

## 🛠️ Technologies

- HTML5
- CSS3 (Bootstrap & AdminLTE)
- JavaScript (AngularJS 1.x)
