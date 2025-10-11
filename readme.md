<img src="https://github.com/alessgorgo/Peek/blob/main/public/img/banner.png" alt="Peek" />
<a href="https://github.com/alessgorgo/Peek/blob/main/license"><img src="https://img.shields.io/badge/Peek%20License-606060" alt="License" /></a>
<a href="https://github.com/alessgorgo/Peek/stargazers"><img src="https://img.shields.io/github/stars/alessgorgo/Peek?color=gray&logo=github" alt="Github star" /></a> <br>

# Peek - Advanced macOS Network Monitor

**Peek** is a lightweight yet powerful macOS application designed to provide detailed, real-time insights into your network connection. It lives discreetly in your menu bar, offering at-a-glance monitoring of network packets, connection speed, and other key statistics without interrupting your workflow.

***

### 📸 Screenshots

Here’s a look at Peek in action. The interface is designed to be clean, intuitive, and deeply integrated with the macOS aesthetic.


| Screenshot | Description |
| :--: | :-- |
| <img src="https://github.com/alessgorgo/Peek/blob/main/public/img/speed-monitoring.png" alt="Peek" width="600px"/> | The **Main Interface** provides a comprehensive overview of your network activity, including real-time upload/download speeds and data packet counts. |
| <img src="https://github.com/alessgorgo/Peek/blob/main/public/img/packets-and-status-monitoring.png" alt="Peek" width="600px"/> | The **Detailed Statistics View** breaks down network traffic over time, showing you historical data and trends for in-depth analysis. |
| <img src="https://github.com/alessgorgo/Peek/blob/main/public/img/customize.png" alt="Peek" width="600px"/> | The **Preferences Panel** will soon allows you to customize Peek, with options for appearance, data refresh intervals, and startup behavior. |


***

### 📚 Table of Contents

* [Key Features](#-key-features)
* [Installation](#-installation)
* [Usage Guide](#-usage-guide)
* [Technical Specifications](#%EF%B8%8F-technical-specifications)
* [Privacy and Security](#-privacy-and-security)
* [Troubleshooting](#%EF%B8%8F-troubleshooting)
* [Development Roadmap](#%EF%B8%8F-development-roadmap)
* [License](#-license)

***

### 🎯 Key Features

* **Real-Time Network Monitoring**: Keep a close eye on your upload and download speeds with live data refreshed every second.
* **Menu Bar Integration**: Access network statistics directly from your menu bar for ultimate convenience and minimal distraction.
* **Detailed Packet Information**: Go beyond simple speed tests with detailed package counts (sent and received) and data flow analysis.
* **Lightweight and Efficient**: Peek is built with performance in mind, ensuring it has a minimal impact on your system’s resources.
* **Privacy First**: All data is processed locally on your machine. Nothing is ever sent to or stored on external servers.
* **Native SwiftUI Interface**: A clean, modern, and responsive UI built with the latest Apple technologies for a seamless macOS experience.

***

### 🔧 Installation

As Peek is distributed as a pre-compiled binary (`.app` file), installation is simple and straightforward.

1. **Download the Latest Release**: Navigate to the [GitHub Releases](https://github.com/your-username/peek/releases) page and download the `Peek.app.zip` file.
2. **Unzip the File**: Double-click the downloaded `.zip` file to extract the application.
3. **Move to Applications**: Drag `Peek.app` to your `/Applications` folder.
4. **Run the App**: Double-click the app to launch it.
5. **Grant Permissions**: On the first launch, macOS may ask for permissions to monitor network activity. This is required for Peek to function correctly.

***

### 🚀 Usage Guide

#### Menu Bar Widget

The core of Peek resides in your menu bar, providing instant access to real-time network statistics.

* **At-a-Glance View**: See your current upload and download speeds directly in the menu bar.
* **Expanded View**: Click the menu bar icon to open a more detailed pop-up with packet information, uptime, and more.
* **Context Menu**: Right-click the icon for quick access to preferences or to quit the application.


#### Main Application Window

For a more in-depth look at your network, open the full application window. Here you will find:

* **Live Charts**: Visualize your network activity over time with dynamic, in-day charts showing traffic and packet counts.
* **Connection Details**: View your local IP address, public IP, gateway, and other connection-specific information.
* **Customization**: Use the preferences pane to adjust the layout and choose what information is displayed.

***

### ⚙️ Technical Specifications

* **Language**: **Swift 5**
* **UI Framework**: **SwiftUI** (ensuring a modern, native macOS experience)
* **Architecture**: The app utilizes a modern **MVVM (Model-View-ViewModel)** pattern to ensure a clean separation of concerns between the UI, business logic, and data models.
* **Network Monitoring Technology**: Peek leverages Apple's native **NetworkExtension framework** for efficient, low-level monitoring of network traffic. This allows for high accuracy and performance with minimal system overhead.

***

### 🔒 Privacy and Security

Your privacy is a core principle of this project. Peek is designed with the following commitments:

* **Local-Only Processing**: All network analysis and data processing happen exclusively on your Mac. No data is ever transmitted to or stored on any external servers.
* **No User Accounts or Tracking**: Peek does not require you to sign up, create an account, or provide any personal information. There are no tracking analytics.
* **Transparent Permissions**: The application only requests the permissions it absolutely needs to function. You can manage these permissions at any time in `System Settings > Privacy & Security`.

***

### 🛠️ Troubleshooting

If you encounter any issues, here are a few common solutions.


| Issue | Solution |
| :-- | :-- |
| **App Won't Launch or Shows an "Unidentified Developer" Warning** | This is standard macOS security. Right-click the `Peek.app` icon, select "Open," and confirm you want to run it. You only need to do this once. |
| **No Data is Displayed in the App** | Ensure you have granted Peek the necessary network permissions in `System Settings > Privacy & Security`. A restart of the app may be required after granting permissions. |
| **Reported Speeds Seem Inaccurate** | Peek reports speeds based on raw network data packets from your network interface. This may differ from online speed tests, which measure throughput to a specific remote server and can be affected by latency and server load. |

If your issue persists, please feel free to [open an issue](https://github.com/your-username/peek/issues) on this repository.

***

### 🗺️ Development Roadmap

Peek is under active development. Here are some of the features planned for future releases:

* [ ] **Customizable Alerts**: Set up notifications for high network usage, connection drops, or unusual activity.
* [ ] **Per-Process Monitoring**: Identify which applications and processes are using the most bandwidth.
* [ ] **Historical Data Export**: Allow users to export network activity logs to a CSV or JSON file for further analysis.
* [ ] **Customizable Themes**: Introduce themes, including a dedicated dark mode, to personalize the app's appearance.
* [ ] **Plugin System**: Create an API to allow third-party developers to build and share plugins for extended functionality.

***

### 📜 License

Peek is released as **Freeware**. You are free to download and use this application for both personal and commercial purposes at no cost.

However, you may not modify, decompile, or redistribute the application without explicit permission from the author. For full details, please see the [License](LICENSE) file included in this repository.
