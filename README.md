<div align="center">

# 🔺 Account a Bill 🔺

### Set a money goal. Track every dollar. Know exactly what is left to make each day.

![Status](https://img.shields.io/badge/status-active-e11d2e?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-any_modern_browser-ff5a5f?style=for-the-badge)
![Storage](https://img.shields.io/badge/data-stays_on_your_device-5ee0a8?style=for-the-badge)
![Tax Year](https://img.shields.io/badge/tax_estimates-2026-6ab7ff?style=for-the-badge)
![Dependencies](https://img.shields.io/badge/dependencies-none-b794f6?style=for-the-badge)

<b>Maintained by <a href="https://github.com/synchancybersecurity">Synchan Cybersecurity</a></b>

</div>

---

## 🟥 What Is Account a Bill?

Account a Bill is a single page web app that turns a money target into a simple daily number. You enter how much you want to make and the date you need it by. The app then tells you how much is still left to make <b>today</b>, and it keeps that number honest as you log income, expenses, and tax items.

It runs entirely in your browser. There is nothing to install, no account to create, and no server collecting your numbers.

---

## 🟧 Features at a Glance

| | Feature | What It Does |
|---|---|---|
| 🎯 | <b>Goals</b> | Set a target amount with a start date and a due date. |
| 📆 | <b>Left to make per day</b> | Spreads what is still unmade across the days that remain, today included. |
| 📤 | <b>Outgoing goals</b> | Track money you owe or plan to pay, with a left to pay per day figure. |
| 💵 | <b>Income log</b> | Record every amount you make, by date. |
| 🧾 | <b>Expenses and miscellaneous costs</b> | Anything you spend raises the amount you need to make. |
| 🧮 | <b>Tax only deductions</b> | Log deductions that affect your taxes without changing your daily goal. |
| 🚗 | <b>Mileage</b> | Enter business miles at the 2026 IRS rate of 72.5 cents per mile. |
| 🧩 | <b>Sections</b> | Split one goal into parts such as rent, gas, and savings, filled automatically or by hand. |
| 📊 | <b>Daily results</b> | See each day as met or short, with the extra you made past your daily goal. |
| 🗂️ | <b>Combined and Monthly tabs</b> | View totals across every goal, or month by month. |
| 🏛️ | <b>Tax estimator</b> | Federal and state estimates with credits, filing status, and payment due dates. |
| 💾 | <b>Backups</b> | Triple saved on your device, plus a downloadable backup file. |
| 🖨️ | <b>Print friendly</b> | A clean light theme for printing. |

---

## 🟨 How the Daily Number Works

The math is deliberately simple, so you can always check it by hand.

```text
Money you need to make  =  Goal target  +  Money spent  +  Miscellaneous costs
Still unmade            =  Money you need to make  -  Money made so far
Left to make per day    =  Still unmade  /  Days left (today included)
```

- Spend more, and the amount you need to make goes up.
- Make more than your daily goal on a good day, and the number for the remaining days goes down.
- The progress bar and the pace line show whether you are ahead of or behind where you should be.

---

## 🟩 Sections

Big goals are easier when they are broken into parts. Each section has its own dollar amount, and the goal total is the sum of all sections.

- <b>Automatic mode.</b> Money you make covers expenses first, then fills each section in order.
- <b>Manual mode.</b> You decide how much goes to each section, and the app shows what is still unallocated.
- Reorder, edit, or delete sections at any time.
- Paste several at once, one per line, with a name followed by an amount.

---

## 🟦 Tax Estimator

Pick a worker type and a state, and Account a Bill estimates what you may owe.

<b>Worker types:</b> W-2 employee, 1099 NEC, 1099 K, 1099 MISC, and self employed.

<b>What it includes:</b>

- 2026 federal income tax brackets and standard deductions for single, married filing jointly, married filing separately, and head of household
- Self employment tax, with the Social Security wage base cap
- The qualified business income deduction
- Child tax credit, other dependent credit, child and dependent care credit, and earned income credit
- State income tax using each state's brackets, standard deduction, and personal exemption
- A log of estimated tax payments, with the next due date and a suggested amount
- A set aside percentage, so you know how much of each dollar to save for taxes

> ⚠️ <b>Important:</b> These figures are rough estimates and are not tax advice. Local taxes, dependents in some states, and several federal extras are not included. Please confirm with a qualified tax professional or the official forms before you file or pay.

---

## 🟪 Your Data and Your Privacy

- Everything is stored in your own browser on your own device.
- Nothing is sent to a server, and the app needs no account.
- Every save writes <b>three copies</b>: the main copy, a second local copy, and an IndexedDB copy. If the main copy ever goes missing, the app offers to restore a saved one.
- You can copy your data as text or <b>download a backup file</b> at any time, and restore from either.

> 💡 <b>Tip:</b> Clearing your browser's website data erases the app's data. Download a backup file once a week, and the app will remind you when it has been a while.

---

## 🚀 Getting Started

<b>Option 1: Open the file</b>

1. Download `index.html` from this repository.
2. Open it in any modern browser.
3. Tap <b>New goal</b>, enter a name, a target amount, and a due date.
4. Log what you make and what you spend each day.

<b>Option 2: Host it with GitHub Pages</b>

1. Open the repository <b>Settings</b> and choose <b>Pages</b>.
2. Under <b>Build and deployment</b>, pick <b>Deploy from a branch</b>.
3. Select your main branch and the root folder, then save.
4. Your app will be live at `https://synchancybersecurity.github.io/account-a-bill/`.

---

## 📁 Project Structure

```text
account-a-bill/
├── index.html    The complete app: markup, styles, and logic in one file
└── README.md     This guide
```

---

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572b6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black)

Plain HTML, CSS, and JavaScript. No frameworks, no build step, and no external services.

---

## 🎨 Design

A frosted glass look over a black faceted backdrop with red light, angled card corners, and a mobile first layout that respects safe areas on phones.

---

## 🤝 Contributing

Ideas and fixes are welcome. Open an issue to describe what you would like to change, or send a pull request with a short explanation of what it improves.

---

<div align="center">

<b>Made with care by Synchan Cybersecurity</b>

<i>Know your number. Hit your goal.</i>

</div>
