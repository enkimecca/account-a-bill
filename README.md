# Account-a-Bill

<div align="center">

![Account-a-Bill](https://img.shields.io/badge/Account--a--Bill-Goal%20%26%20Tax%20Tracker-e11d2e?style=for-the-badge&logo=money&logoColor=white)
![Version](https://img.shields.io/badge/version-1.1-0a0908?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Web%20%2F%20iOS%20Safari-000000?style=for-the-badge&logo=safari&logoColor=white)
![Storage](https://img.shields.io/badge/storage-Local%20Only-5ee0a8?style=for-the-badge)

**Dig into your money goals. Track income, expenses, taxes, mileage, time, and cash flow — all offline, in one file.**

</div>

---

## What it is

**Account-a-Bill** is a single-file, privacy-first web app for tracking income goals (or outgoing payment goals), daily progress, tax estimates (2026 federal + state), business mileage, time worked, and effective pay-per-hour.

Everything lives in your browser (localStorage + IndexedDB). No accounts, no servers, no tracking.

### Brand palette
| Token | Hex | Use |
|-------|-----|-----|
| Accent | `#e11d2e` | Primary actions, progress |
| Accent 2 | `#ff5a5f` | Highlights |
| Background | `#07070a` | Deep black |
| Card | frosted glass | Panels |
| Positive | `#5ee0a8` | Made / good |
| Negative | `#ff6b6b` | Spent / short |

---

## Features

### Core Goal Tracking
- Incoming goals (“money to make”) or outgoing (“money to pay”)
- Daily / remaining needed, pace tracking, progress bars
- Sections / sub-budgets with automatic or manual allocation
- Daily results vs goal, history with filters & search

### Tax Tools (2026 figures)
- Worker types: W-2, 1099-NEC, 1099-K, 1099-MISC, self-employed
- Federal brackets + standard deduction + QBI + credits (CTC, care, EITC)
- State brackets, standard deductions, personal exemptions (real 2026 data)
- Tax-only deductions, estimated payments log, mileage at **72.5¢/mi**
- Combined multi-goal tax estimate
- Paystub generator + CSV exports

### New in this update
| Feature | Description |
|---------|-------------|
| **GPS Auto-Mileage** | Start a trip → device GPS tracks distance → end & auto-log as tax-only deduction |
| **Cash Flow Estimator** | Projects remaining need, current-pace surplus/shortfall, and what-if daily rate calculator |
| **Time Tracker + $/hr** | Live timer (start / pause / resume / stop) or manual hours → effective pay-per-hour = money made ÷ hours logged |

### Other
- Monthly income view + quick-add + manual income
- Full backup / restore (JSON file or text)
- Print-friendly paystubs
- Mobile-first (works great on iOS Safari)

---

## Quick Start

1. Open `account-a-bill.html` (or `index.html`) in any modern browser.
2. Tap **+ New goal**.
3. Set name, amount, start & end dates.
4. Log money made / spent / misc / tax-only as you go.
5. Use the **Tax** tab for worker type + state + GPS mileage + payments.
6. Use **Overview** or **Made** for the time tracker and cash-flow tools.

> **Tip:** Download a backup regularly. Clearing Safari website data will erase local storage.

---

## File StructureNo build step. No dependencies. Just open the HTML.

---

## Privacy & Data

- All data stays on-device.
- Triple-write on save: primary key, `.bak` key, IndexedDB.
- Empty states never overwrite existing backups.
- Export full CSV of entries + tax summary anytime.

---

## Browser Notes

| Browser | Notes |
|---------|-------|
| Safari (iOS / macOS) | Primary target. Grant location for GPS. Keep tab open while tracking. |
| Chrome / Edge / Firefox | Full support. |
| Background tracking | Limited by browser (GPS & timer pause or throttle when tab is backgrounded). |

---

## Roadmap / Ideas

- Optional encrypted export
- Multi-device sync via file or QR
- More detailed expense categories
- Dark / light theme toggle (currently dark-only)

---

## License

Personal / private use. Do what you want with it.  
Not tax, legal, or financial advice. Estimates only.

---

<div align="center">

**Account-a-Bill** · Track what you make. Know what you owe.  
Made for people who dig deep.

</div>