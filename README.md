# 🎯 Discord Vanity Sniper

<p align="center">
  <img src="https://raw.githubusercontent.com/zentir0g/discord-vanity-sniper/refs/heads/main/imagse.png" alt="Vanity Sniper Demo" width="800">
</p>

> **📸 Screenshot Instructions:** Save your screenshot as `screenshot.png` in the same folder as `snipe.exe` and it will appear here automatically.

---

## 📖 About

The ultimate Discord vanity URL sniper that gives you the edge in claiming rare and valuable vanity URLs. Built with **HTTP/2** technology for lightning-fast claim speeds and equipped with automatic monitoring systems to never miss an opportunity.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| ⚡ **HTTP/2 Support** | Ultra-fast request handling for competitive sniping |
| 🎯 **Multi-Vanity Tracking** | Monitor unlimited vanity URLs simultaneously |
| 🔍 **Auto Availability Check** | Automatically scans for available vanities every 60 seconds |
| 👁️ **Real-time Monitoring** | Instantly detects guild updates and deletions |
| 🔐 **MFA Support** | Seamless Discord MFA verification handling |
| 📢 **Webhook Alerts** | Real-time notifications on every claim attempt |
| 💬 **DM Notifications** | Direct messages when you successfully claim a vanity |
| 🦶 **Auto-kick** | Automatically kicks intruders during sniping sessions |
| ⏸️ **Invite Pause** | Temporarily disable server invites when needed |

---

## 🚀 Quick Start

No dependencies required! Just download and run `snipe.exe`

---

## ⚙️ Configuration

### 1️⃣ Create `config.json`

```json
{
    "token": "YOUR_DISCORD_TOKEN",
    "channelId": "CHANNEL_ID_FOR_COMMANDS",
    "serverId": "YOUR_SERVER_ID",
    "userToDm": "USER_ID_TO_DM_ON_CLAIM",
    "password": "YOUR_DISCORD_PASSWORD",
    "webhookUrl": "YOUR_WEBHOOK_URL"
}
```

### 2️⃣ Create `vanity.txt`

Add your target vanities (one per line, `#` for comments):

```
# Cool vanities to snipe
discord
nitro
gaming
fortnite
spotify
```

---

## 🎮 Command List

| Command | What It Does |
|---------|---------------|
| `.help` | Shows all available commands |
| `.mfa on/off` | Enables/disables MFA verification |
| `.sniper on/off` | Turns the sniper on or off |
| `.claim <vanity>` | Manually claims a vanity URL |
| `.targets` | Lists all your target vanities |
| `.check` | Manually checks all vanities |
| `.checkstart` | Starts automatic checking (every 60s) |
| `.checkstop` | Stops automatic checking |
| `.claimed` | Shows all successfully claimed vanities |
| `.reload` | Reloads vanities from `vanity.txt` |
| `.autokick` | Toggles auto-kick on member join |
| `.pause` | Disables invites for 24 hours |
| `.vanity` | Lists vanity URLs in your servers |
| `.leave <vanity/id>` | Leaves a server |
| `.delete` | Deletes current server vanity |
| `.restart` | Restarts the bot |

---

## ⚠️ IMPORTANT

> ### 🔴 VPN REQUIRED IF NOT WORKING
> 
> **If the tool doesn't work properly, USE A VPN!** Discord often rate-limits or blocks certain IP addresses. A VPN will bypass these restrictions and get you sniping again.

---

## 🔧 Troubleshooting Guide

| Issue | Solution |
|-------|----------|
| ❌ Tool not working | **Use a VPN** - This solves 90% of problems |
| ❌ MFA Errors | Run `.mfa on` before starting the sniper |
| ❌ Rate limited | Tool has built-in delays, but VPN helps too |
| ❌ Can't claim vanity | Make sure your server has **Tier 3 boost** |

---

## 📝 Requirements

- ✅ Discord account with vanity URL permissions
- ✅ Server with **Tier 3 boost** (required for vanity URLs)
- ✅ Windows OS (for `snipe.exe`)

---

## 🙏 Credits

**Developer:** Harry Uchiha

---

## 🔗 Links

- **GitHub:** [https://github.com/zentir0g/discord-vanity-sniper](https://github.com/zentir0g/discord-vanity-sniper)
- **Support Server:** [https://discord.gg/zentirog](https://discord.gg/zentirog)

---

## 📜 Disclaimer

```
This tool is for educational purposes only.
Not affiliated with or endorsed by Discord Inc.
Using self-bots violates Discord's Terms of Service.
The author is not responsible for any consequences.
Use at your own risk.
```

---

<p align="center">
  <b>Happy Sniping! 🎯</b>
</p>
