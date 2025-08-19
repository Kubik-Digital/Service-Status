# KUBIK Infrastructure Status

A lightweight status dashboard for monitoring the live availability of KUBIK Digital’s infrastructure, which is hosted on **GitHub**, **Microsoft Azure**, and **Google Cloud**.  

This project fetches the live status from [GitHub Status](https://www.githubstatus.com) and displays the health of dependent services used by KUBIK projects.

## Features
- 🚦 Global status indicator (all systems / degraded / outage).
- 📡 Real-time check of GitHub services (API, Actions, Pages).
- 🖼️ Clean, responsive dashboard UI.
- 🔄 Auto-refresh every 60 seconds + manual refresh button.
- ⚡ Fast and dependency-free (pure HTML, CSS, JS).

## Projects Monitored
- **ERP Bridge** → GitHub API, GitHub Actions  
- **Static Websites** → GitHub Pages  
- **Automations** → GitHub API, GitHub Actions  

## How It Works
- Fetches data from the [GitHub Status API](https://www.githubstatus.com/api/v2/summary.json).
- If all project services are operational → only shows a ✅ "Operational" badge.  
- If issues exist → shows per-service breakdown (API, Pages, Actions).  
- Automatically refreshes every minute or manually via the refresh button.  
