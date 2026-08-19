# Unified Network CIDR Planner

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

A lightweight, interactive visualizer for IPv4 CIDR blocks (/24 to /32). This tool helps network engineers, students, and IT professionals visually map out subnet structures, Network IDs, Broadcast IDs, and usable IP ranges along a proportional 0–255 number line.

## 🚀 Features

* **Interactive CIDR Visualization:** Select any CIDR block from `/24` (256 IPs) down to `/32` (1 IP) to instantly see how the network is divided.
* **Proportional Number Line:** All subnet blocks are proportionally locked to a 0–255 scale, providing true visual intuition for block sizes.
* **Dynamic Layouts:** Seamlessly toggle between **Horizontal** and **Vertical** viewing modes depending on your screen space or preference.
* **Network Planning Toggle:** A master control button to instantly expand or collapse all subnets to view deep IP details simultaneously.
* **Zero Dependencies:** Pure HTML, CSS, and Vanilla JavaScript. No frameworks, build steps, or external libraries required.

## 🛠️ How to Use

1. Clone or download this repository.
2. Open `index.html` (or `network_planner.html`) directly in any modern web browser.
3. Use the dropdown at the top to select a CIDR notation.
4. Click individual colored blocks to expand them and view the **Network ID**, **Broadcast ID**, and a full list of assigned IP addresses.
5. Use the **Network Planning (Toggle All)** button to expand/collapse everything at once.

## 📁 Repository Structure

* `index.html` - The complete, single-file application containing all HTML structure, CSS styling, and JavaScript logic.
* `README.md` - Project documentation.
* `LICENSE` - Open-source licensing information.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check [issues page](https://github.com/yourusername/network-cidr-planner/issues) if you want to contribute.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
