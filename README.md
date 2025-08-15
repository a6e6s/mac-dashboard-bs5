# macOS-Styled Admin Dashboard

A fully responsive, web-based admin dashboard that mirrors the aesthetic and usability of a macOS desktop environment. This project is built with HTML, Tailwind CSS, and vanilla JavaScript.

## ✨ Features

A breakdown of the desktop and mobile features included in this dashboard.

### Desktop Interface (Screen width > 768px)

* **Window Management**:
    * **Draggable Windows**: Click and drag the title bar to move windows around. The movement is optimized using CSS `transform` for a smooth, lag-free experience.
    * **Resizable Windows**: Grab the handle in the bottom-right corner to resize windows.
    * **Window Controls**: Standard red, yellow, and green "traffic light" buttons to close, minimize, and maximize windows.
    * **Maximize on Double-Click**: Double-click a window's title bar to toggle its maximized state.
    * **Focus Management**: Clicking on any window brings it to the front with a highlighted border.
* **Dock**:
    * **App Launcher**: A macOS-style dock at the bottom to launch and switch between applications.
    * **Hover & Active Effects**: Icons magnify on hover, and a glowing dot indicates an open application.
    * **Minimize to Dock**: Clicking the active app's icon in the dock minimizes the window with a "genie" animation.
* **Menu Bar**:
    * **Dynamic App Title**: Displays the name of the currently active application.
    * **System Tray**: Includes a live-updating clock, a theme switcher (light/dark mode), a notification icon that opens a slide-in drawer, and a user profile icon with a dropdown menu.
* **Animations**:
    * **Genie Effect**: Windows animate into and out of the dock when minimizing and restoring.
    * **Smooth Transitions**: Fluid animations for opening menus, drawers, and interacting with UI elements.

### Mobile Interface (Screen width < 768px)

* **App Grid**: The desktop interface is replaced with a touch-friendly grid of app icons.
* **Full-Screen Apps**: Applications open in full-screen mode for an optimized mobile experience.
* **Simplified Navigation**: The "close" button functions as a "back" button to return to the home screen.

---

## 🚀 How to Run

1.  Download the project files.
2.  Open the `index.html` file in your web browser.
3.  That's it! No build steps or dependencies are required.

---

## 🛠️ Built With

* **HTML5**
* **Bootstrap 5** & **Bootstrap Icons**
* **Vanilla JavaScript**