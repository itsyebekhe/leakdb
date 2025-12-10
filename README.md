
# 👻 Ghost DB Search Dashboard

A modern, high-performance web interface for searching encrypted datasets via Cloudflare Workers. Designed with 2025 UI trends, featuring Glassmorphism, dark aesthetics, and full Persian (RTL) support.

![UI Preview](https://img.shields.io/badge/UI-Glassmorphism-blueviolet) ![Status](https://img.shields.io/badge/Status-Active-success) ![Language](https://img.shields.io/badge/Lang-Persian_RTL-orange)

## ✨ Features

*   **2025 Design Language:** Deep slate background (`#020617`), ambient lighting effects, and frosted glass cards.
*   **Zero Dependencies:** Runs entirely in the browser using CDNs. No `npm install` or build steps required.
*   **Fully Responsive:** Optimized for both mobile devices and desktop screens.
*   **Smart Search UI:**
    *   **Scope Selection:** Filter by National Code, Mobile, Name, or All.
    *   **Live Feedback:** Animated loading states and result cards (Found, Ambiguous, Not Found).
    *   **Error Handling:** Visual cues for server errors or connection issues.
*   **Persian Optimized:** Uses the **Vazirmatn** font and full RTL layout.

## 🛠 Technologies Used

*   **HTML5 & Vanilla JavaScript** (ES6+)
*   **[Tailwind CSS](https://tailwindcss.com/)** (via CDN) - For styling and layout.
*   **[Lucide Icons](https://lucide.dev/)** (via CDN) - For modern, lightweight SVG icons.
*   **[Vazirmatn Font](https://github.com/rastikerdar/vazirmatn)** - For beautiful Persian typography.

## 🔍 Search Logic

The dashboard supports the following search inputs:
*   **Full Name:** Enter full names with spaces (e.g., `Ali Reza`). The backend handles Persian/Arabic character normalization automatically.
*   **Mobile Number:** Enter full numbers (e.g., `09123456789`).
*   **National Code:** Enter the 10-digit ID.

## 🎨 Customization

*   **Colors:** The theme is built using Tailwind's `indigo` and `slate` palettes. You can change `bg-indigo-600` to `bg-blue-600` or `bg-emerald-600` in the HTML to change the primary color.
*   **Social Links:** Update the `href` attributes in the footer section to point to your own Telegram or X (Twitter) accounts.

## 📄 License

Open Source. Feel free to modify and distribute.
