# Benny & Liam Time

**Benny & Liam Time** is a lighthearted web project built around an inside joke between two friends, Benny (from Melbourne) and Liam (from Brisbane). When daylight saving time begins, their clocks go out of sync — Melbourne moves an hour ahead while Brisbane stays put. To fix this, they decided to meet halfway, creating their own timezone: **Benny & Liam Time** — which by coincidence, perfectly matches **South Australian time (UTC+10:30)**.

---

## 🕒 Concept

The site displays **Benny & Liam Time** as the central reference point and compares it to all major Australian time zones. It updates live every second, automatically adjusting for daylight saving transitions using the browser’s built-in `Intl.DateTimeFormat` API.

The goal of the project is to visualise this in-between timezone idea in a polished, functional way.
---

## 💡 Features

* **Real-time clock** for Benny & Liam Time (BLT timezone)
* Additional clocks for every major Australian region:

  * Melbourne (VIC)
  * Brisbane (QLD)
  * Sydney (NSW)
  * Adelaide (SA)
  * Perth (WA)
  * Hobart (TAS)
  * Darwin (NT)
  * Canberra (ACT)
  * UTC for comparison
* Displays time zone abbreviation (AEST, ACDT, etc.) and UTC offset
* Auto-adjusts for daylight saving changes
* Clean, responsive design with system light/dark theme support

---

## ⚙️ Technical Overview

The site is built as a **single-page HTML application** — no frameworks, no dependencies. Everything runs natively in the browser using standard web technologies:

| Technology           | Purpose                               |
| -------------------- | ------------------------------------- |
| **HTML5**            | Page structure                        |
| **CSS3**             | Styling and responsive layout         |
| **JavaScript (ES6)** | Time calculations and dynamic updates |

It relies on the **IANA timezone database** via JavaScript’s `Intl` API to ensure accurate offsets and abbreviations across time zones.

---

## 🎨 Design Philosophy

The look and feel of the project aim to reflect a balance between functionality and playfulness — simple gradients, subtle glows and rounded elements evoke a soft, modern vibe while keeping the focus on the clocks.
---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

**A tribute to Benny & Liam’s creative problem-solving.** Made in Tasmania 🇦🇺
