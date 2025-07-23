# DVHOST VirBack

A lightweight CLI tool to automate MySQL database backups from multiple **Virtualizor** servers and send them directly to a **Telegram bot**.

📦 Repository: [github.com/dev-ir/DVHOST-VirBack](https://github.com/dev-ir/DVHOST-VirBack)

---

## ✅ Features

- Auto-detect Virtualizor MySQL credentials from `universal.php`
- Schedule backups for multiple servers
- Store backups in `/DVHOST_Backup/`
- Send backups via Telegram (Bot Token & Chat ID)
- Cron integration with adjustable interval (2–24 hours)
- Interactive CLI menu:
  - Add new server
  - List and manage configured servers
  - Edit or remove backup jobs

---

## ⚙️ Requirements

- `bash`, `jq`, `curl`, `mysqldump`, `crontab`
- A Telegram bot + Chat ID

---

## 🚀 How to Use

```bash
sudo bash dvhost_virback.sh
