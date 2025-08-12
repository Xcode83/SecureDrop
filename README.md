#  SecureDrop 

<div align="center">
 <img width="1920" height="933" alt="Screenshot From 2025-08-13 02-50-06" src="https://github.com/user-attachments/assets/92a32fba-e1e1-4374-99f1-14d6310fe290" />


</div>

<div align="center">

**A cutting-edge, peer-to-peer (P2P) file sharing application built with modern web technologies.**

SecureDrop allows you to transfer files of any size directly from your device to another, completely bypassing server uploads. Your data remains private, secure, and is never stored anywhere in the cloud.

</div>

<div align="center">

[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![PeerJS](https://img.shields.io/badge/PeerJS-EF6C00?style=for-the-badge&logo=webrtc&logoColor=white)](https://peerjs.com/)

</div>

---

## ✨ Features

-   **True Peer-to-Peer Transfer:** Files are sent directly between browsers using WebRTC. No servers, no middlemen.
-   **Ultimate Privacy:** Your files are never uploaded or stored. The connection is direct, private, and secure.
-   **No File Size Limits:** Transfer large files without worrying about server upload limits.
-   **Simple & Instant Sharing:** Generate a unique link or a QR code for the receiver to instantly start the download.
-   **Sleek, Modern UI:** A beautiful, responsive dark-mode interface built for a seamless user experience.
-   **Automatic Download:** The file download starts automatically on the receiver's end once the transfer completes.

---

## 📸 Screenshots

A glimpse into the SecureDrop experience. The entire interface was designed to be clean, intuitive, and visually stunning.


1. <img width="1920" height="941" alt="Screenshot From 2025-08-13 02-50-20" src="https://github.com/user-attachments/assets/0821bac3-1eda-4d88-98fd-11b02a398c91" />

*
2. <img width="1920" height="934" alt="Screenshot From 2025-08-13 02-50-33" src="https://github.com/user-attachments/assets/543fe2b1-fff2-4163-af86-60c57287ef85" />

*



---

## ⚙️ How It Works: The Technology Explained

Traditional file sharing requires uploading a file to a central server, which then allows others to download it. This creates privacy risks and potential bottlenecks.

SecureDrop avoids this entirely by using **WebRTC** (Web Real-Time Communication), a powerful API built directly into modern browsers.

1.  **Signaling:** The sender initiates a session and receives a unique ID from a public PeerJS signaling server. This server's only job is to introduce two peers to each other.
2.  **Handshake:** The receiver uses this ID (via the shared link or QR code) to signal their presence to the sender.
3.  **Direct Connection:** Once the handshake is complete, the signaling server's job is done. A direct, encrypted peer-to-peer connection is established between the two browsers.
4.  **Data Transfer:** The file is broken into chunks and streamed directly from the sender's browser to the receiver's browser. The data never passes through any other server.

---

## 🛠️ Tech Stack

This project was built using a curated set of modern, high-performance tools to ensure a smooth and robust experience.

-   ⚡ **Vite:** A next-generation frontend toolchain that provides a blazing-fast development experience.
-   ⚛️ **React:** The core library for building the dynamic and responsive user interface.
-   🔵 **TypeScript:** For writing robust, type-safe JavaScript that scales.
-   💨 **Tailwind CSS:** A utility-first CSS framework for rapid and beautiful UI design.
-   🤝 **PeerJS:** A library that simplifies the complex WebRTC peer-to-peer connection logic.
-   🔗 **react-qr-code:** A lightweight React component for generating QR codes.
-   🎨 **react-icons:** For including high-quality SVG icons in the UI.

---

## 📄 Project Status

This repository serves as a **showcase and portfolio piece** for the SecureDrop project. 
The source code for this project is currently private.

---

<div align="center">
  <h3>Connect with me</h3>
  <p>
    Created with ❤️ by <a href="https://github.com/Xcode83">**Biswajit Sahoo (Xcode83)**</a>
  </p>
</div>
