# Accessibility Lab

An interactive, single-file workshop for learning and practising web accessibility against **WCAG 2.1 AA**. No build step, no dependencies: open `Accessibility Lab.html` in any modern browser.

## What's inside

| Module | What you do |
|---|---|
| **1. Keyboard and ARIA** | Try keyboard-only patterns: tabs, accordion, modal dialog, menu button, validated form, and a live key-event log. |
| **2. Contrast and zoom** | Check text/background contrast ratios (AA and AAA), get a passing colour suggestion, and simulate zoom, 320px reflow, text spacing and colour-vision deficiencies. |
| **3. Fix the UI** | Compare a broken ("Before") and fixed ("After") sample, and work through a tracker of 14 common WCAG failures with detection tips and code fixes. |
| **4. Audit report** | Rate 18 success criteria as Pass / Fail / N/A, add notes, then generate, copy or print a summary report. |

## Features

- Three themes: Light, Dark and High contrast (starts from your OS preference).
- Fully keyboard operable, with visible focus, skip link, native `<dialog>`, live regions and reduced-motion support.
- Responsive layout and print-friendly report.
- Typography: Constantia, falling back to Lora (Google Fonts), then Georgia.

## Usage

1. Open `Accessibility Lab.html` in a browser (Chrome, Edge, Firefox or Safari).
2. Pick a theme, then move through the four tabs (arrow keys, Home and End work on the tab bar).
3. Finish in **Audit report** and use **Generate report**, **Copy report as text** or **Print**.

The Lora web font needs an internet connection; without it the page uses Constantia or Georgia.

## Limits

This tool teaches and approximates; it does not replace testing with real assistive technology (NVDA, JAWS, VoiceOver, TalkBack) or automated scanners such as axe or Lighthouse. Automated tools catch only part of WCAG, so manual testing is still required.
