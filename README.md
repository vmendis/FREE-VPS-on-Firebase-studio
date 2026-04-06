# 🚀 Free VPS on Firebase Studio

Create a **free 24/7 VPS** using **Firebase Studio** (formerly Google Project IDX) — no credit card required!

This repository provides everything you need to turn a Firebase Studio workspace into a powerful, always-on virtual private server.

> **Note:** Firebase Studio offers free workspaces (up to 3 by default, more with Google Developer Program membership). This method gives you a persistent Linux environment with root access.

## ✨ Features

- Fully free VPS (no billing)
- Root access
- Persistent storage
- Easy installation of services (Docker, Pterodactyl Panel, etc.)
- Auto-start options for the VM
- Customizable via Nix (`dev.nix`)

## 📋 Prerequisites

- A Google account
- Access to [Firebase Studio](https://firebase.studio/) (free)
- (Optional) Cloudflare account for domain + SSL

## 🛠️ Step-by-Step Setup

### 1. Create a New Workspace in Firebase Studio

1. Go to [Firebase Studio](https://firebase.studio/)
2. Click **"Create new workspace"**
3. Choose **"Import from GitHub"**
4. Paste your repository URL (this repo)
5. **Important:** Keep the workspace name simple (avoid special characters)

### 2. Run the VPS Installation Script

Once the workspace loads, open the **Terminal** and run:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/vps.sh)
