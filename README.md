# 🌐 wormhole - Simple Localhost Exposure Tool

[![Download wormhole](https://img.shields.io/badge/Download-wormhole-%239966CC?style=for-the-badge)](https://github.com/ipongvery/wormhole)

---

## 🛠 About wormhole

wormhole is an open-source tool that helps you share your computer’s local web servers with others through the internet. It works with one simple command. You don’t need to understand networks or complex setups. The tool uses fast technology to create a secure tunnel from your computer to the web. It runs on Windows and works quietly in the background.

Made with Go and Cloudflare Workers, wormhole is designed to keep your connection safe and stable. You can show your work, share websites you build, or give access to apps running on your PC.

---

## 🚀 Getting Started

This guide will show you how to get wormhole running on Windows. Follow the steps carefully to set up and use the tool without any issues.

### System Requirements

- Windows 10 or later
- Internet connection
- Basic ability to use the Windows command prompt (we’ll guide you through this)
- About 10 MB of free disk space

---

## ⬇️ Download and Installation

You need to visit the link to download the software. It will take you to the official GitHub page where you can get the latest version for Windows.

[![Download here](https://img.shields.io/badge/Download%20here-wormhole-%2355AAFF?style=for-the-badge)](https://github.com/ipongvery/wormhole)

### Steps to download

1. Open your web browser and go to:  
   https://github.com/ipongvery/wormhole

2. Look for a section called **Releases** or **Download**.

3. Find the file that ends with `.exe`. This is the program file for Windows.

4. Click the file to start downloading.

5. Once the download finishes, open your `Downloads` folder.

6. Double-click the `.exe` file to start the installation.

7. Follow the instructions on the screen. Accept the terms and choose the installation folder (default is fine).

---

## ▶️ How to Run wormhole

After installation, you need to open the Command Prompt to use wormhole. Don’t worry; these steps will guide you through it.

### Open Command Prompt

1. Press the **Windows key** on your keyboard.

2. Type `cmd` and press **Enter**.

You should see a black window with white text. This is called the command prompt.

### Start your server or app

Make sure you have a program or website running locally. For example, if you use software that runs a website on your computer at a web address like `http://localhost:3000`, you can share this with others.

### Run wormhole to share your local website

1. In the command prompt, type:

   ```
   wormhole 3000
   ```

   Replace `3000` with the port number your app uses. The port is the number at the end of your `localhost` address.

2. Press **Enter**.

wormhole will create an internet address (a URL) you can share with others. This address lets people visit your local website from their browsers.

---

## 🔧 Using wormhole

### About the internet address

When you run wormhole, it gives you a URL that looks like this:

```
https://randomstring.wormhole.workers.dev
```

Anyone with this link can see your local site. The connection is protected by Cloudflare’s security.

### Stop sharing

To stop sharing, just go back to the command prompt and press **Ctrl + C**. This will close the tunnel.

### Running with different ports

You can share different apps or services by changing the port number. For example:

```
wormhole 8080
```

If your local server uses port 8080, this command will share that instead.

---

## ⚙️ Troubleshooting and Tips

### If wormhole is not recognized

If you see an error like `'wormhole' is not recognized`, it means the program is not added to your system's path.

Try these steps:

1. Close the command prompt and open a new one.

2. Try running wormhole again.

3. If the error continues, restart your computer.

4. If it still won’t work, check if the installation folder contains `wormhole.exe`. You can run it from that folder by typing the full location in the command prompt, such as:

   ```
   "C:\Program Files\wormhole\wormhole.exe" 3000
   ```

### Firewall or antivirus may block wormhole

Some security software might block wormhole’s connection. If this happens:

- Look for alerts from your antivirus or firewall program.

- Allow wormhole to connect in those alerts.

- If unsure, temporarily disable your security software and try again.

---

## 🧰 Additional Notes

- wormhole works only while your local server or app is running.

- The internet address changes every time you open wormhole.

- Avoid sharing sensitive or private content over wormhole unless you trust the people you share with.

- You can share any website or app running on your computer that listens to a local port.

---

## ❓ Need Help?

Visit the official page for documentation and updates:

[https://github.com/ipongvery/wormhole](https://github.com/ipongvery/wormhole)

You can open issues or ask questions on the GitHub page if you find problems or need support.