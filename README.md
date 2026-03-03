# Course 4: Basic Server Setup  
## System Administration and IT Infrastructure Services

---

## 📌 Project Overview

This project demonstrates the setup and configuration of a local web server using Microsoft Internet Information Services (IIS) on Windows.

The objective was to:
- Install and enable IIS
- Configure a local server
- Understand web directory structure
- Deploy a custom HTML webpage

---

## 🖥️ Step 1: Enabling IIS

I enabled Internet Information Services (IIS) through Windows Features.

![IIS Enabled](screenshots/1-iis-enabled.png)

---

## 🌐 Step 2: Testing Default Server Page

After installation, I verified the server was running by accessing:

http://localhost

![Default IIS Page](screenshots/2-default-localhost.png)

---

## 📂 Step 3: Web Directory Structure

The default IIS web root directory is:

C:\inetpub\wwwroot

This is where website files are stored.

![wwwroot Folder](screenshots/3-wwwroot-folder.png)

---

## 🚀 Step 4: Deploying Custom Web Page

I created an `index.html` file inside the `wwwroot` directory and added custom HTML and CSS styling.

The server successfully rendered the custom webpage.

![Custom Web Page](screenshots/4-custom-webpage.png)

---

## ✅ Services Configured

- Microsoft IIS Web Server
- Localhost HTTP service
- Static HTML deployment
- Web root directory configuration

---

## 🎯 Conclusion

The successful display of the custom webpage confirms that IIS was properly installed and configured. This demonstrates an understanding of basic server setup, web hosting fundamentals, and file structure management within a Windows environment.
