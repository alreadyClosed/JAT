# [ JAT_FRAMEWORK ] v5.0
> **John's Awesome Tools** • A clean, terminal-inspired workstation for OSINT, Cybersecurity, and Research.

<p align="center">
  <img src="https://img.shields.io/badge/Status-v5.0_STABLE-success?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/UI-Terminal_Dark-f0883e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Theme-Neon_Orange-f0883e?style=for-the-badge" />
</p>

<p align="center">
  <b>🌍 Live Site</b><br>
  https://alreadyclosed.github.io/JAT/
</p>

---

## 🖥️ Overview
**JAT** is a lightweight, single-page interface designed for quick access to web-based tools. It organizes 70+ resources into a searchable, categorized layout that works directly in any browser without extra setup.

### 🔍 Key Features
- **Modal Descriptions:** Click a tool to see a pop-up with its specific purpose and metadata before launching.
- **Smooth Expansion:** Categories expand using CSS Grid transitions for a clean, non-snapping experience.
- **Terminal Aesthetic:** Uses Consolas typography with a high-contrast Black and Neon Orange theme.
- **Filter Search:** Real-time search that highlights matching tools, searches through hidden tags, and manages category states automatically.
- **Adaptive Grid:** Responsive layout that keeps tool links organized regardless of screen size.
- **Automatic Counting:** Tracks and displays the number of tools within each category.

---

## 🛠️ Tech Stack
- **Frontend:** HTML5 & CSS3 (Custom Variables & Grid)
- **Logic:** Vanilla JavaScript (Zero-Waste, No libraries or dependencies)
- **Theme:** GitHub-inspired Dark mode with Neon Orange accents.

---

## 📂 Framework Structure
| Category | Focus |
| :--- | :--- |
| **OSINT** | Open Source Intelligence and Investigations |
| **NETWORK & RECON** | Domain, DNS, and infrastructure mapping |
| **WEB SECURITY** | Request analysis and CMS testing |
| **EXPLOITATION** | Shell generators and vulnerability databases |
| **POST-EXPLOITATION** | Privilege escalation and wordlists |
| **REVERSE ENGINEERING** | Debugging and file analysis |
| **CRYPTOGRAPHY** | Encoding, hashing, and decryption |
| **LEARNING & CTF** | Training platforms and security documentation |
| **SYSTEM & UTILITIES** | OS flashing and system optimization |
| **OPERATING SYSTEMS** | Quick links to security-focused distributions |

---

## 🚀 Usage
1. **Clone the repository:**
```
git clone https://github.com/alreadyClosed/JAT.git
```

2. **Run:**
   Open `index.html` in any web browser. 

3. **Search:**
   Use the search bar at the top to filter tools. Typing a keyword will filter the list and expand relevant folders automatically.

---

## 📝 Configuration
To add or remove links, edit the `myTools` array in the script section. Note the updated format for v5.0:
```
const myTools = [
    ["CATEGORY", "Tool Name", "https://url-link.com", "Short Description", "search tags"],
];
```

---
<p align="center">
  <b>Credits:</b> All tools linked belong to their respective creators.
</p>

---
<p align="center">
  <i>"Locally Hosted Workstation"</i><br>
  <b>[ JAT_FRAMEWORK ]</b>
</p>
