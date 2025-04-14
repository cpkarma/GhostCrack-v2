# GhostCrack v2 - By Karma Syndicate

**GhostCrack v2** is a multi-functional penetration testing and automation tool, designed for rapid exploitation and validation of web services.

**Whats New?**

- **Combo Mode:** Now cracks cPanel & WHM using a combo list.

- **cPanel Domain Validation:** When checking cPanel, it also checks for valid main domains and saves the results.

- **Alias Removed:** Removed alias "karma_" which means it will upload or create files without name "karma_" added.

**📝 List Format 📝**

**cPanel List Format:** https://domain.com:2083|user|password

**Shell List Format:** https://domain.com/shell.php

**SMTP List Format:** domain.com|587|user@domain.com|password

**WHM List Format:** https://domain:2087|root|password

**Combo List Format:** user@domain.com:password

---

## 🔓 What GhostCrack v2 Cracks

### Shells
- Detects valid web shells.
- Uploads files to shells.
- Crack SMTP credentials from shells.

### cPanel
- Checks for valid cPanel logins.
- Retrieves domains linked to cPanel accounts.
- Cracks SSH access (root/user).
- Uploads files through the cPanel file manager.
- Creates SMTP and webmail accounts.

### SMTP
- Validates SMTP login credentials.
- Optionally sends test emails.

### WHM (Web Host Manager)
- Checks WHM logins.
- Resets cPanel passwords.

### Combo (New Added)
- Crack cPanel from combo.
- Crack root & Reseller WHM.

### Ghost Mode (All-in-One)
- Cracks symlinks, WHM access hashes, cPanel, SMTP, and CMS (WordPress/Joomla) resets from Shells or cPanels.

---

## 👥 Developed By

**Karma Syndicate**  
Website: [https://cpkarma.cc](https://cpkarma.cc)  
Telegram: [@KarmaSyndicate](https://t.me/KarmaSyndicate)  
YouTube: [@KarmaCorps](https://youtube.com/@KarmaCorps)

![alt text](https://raw.githubusercontent.com/cpkarma/img/main/GhostCrackv2.jpg)
