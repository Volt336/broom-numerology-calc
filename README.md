# Broom's Numerology Calc

Broom’s Numerology Calc is a set of offline Pythagorean numerology tools I built for myself and anyone else who wants the classic calculations without an account or server. There are three calculators plus a simple home page:

• Full reading from birth name and date (Life Path, Soul Urge/Heart’s Desire, Personality, Destiny/Expression, Birthday, Personal Year)  
• Personal Day calculator that also shows Personal Month and Year for any date, plus the next week  
• Deeper Meanings calculator for Life Cycles, Pinnacles (with age timeline), Challenges, Maturity Number, and Karmic Lessons

Every formula is shown step by step so you can see exactly how the number was reached. Master numbers 11, 22, and 33 are kept when they appear. Readings can be saved in the browser’s local storage, exported as text or JSON backup, printed in color or ink-saver mode, and turned into a PDF from the browser’s print dialog. Nothing is sent anywhere; it all runs in the browser.

This is my first real web app. I’m still learning as I go, so the code is straightforward HTML, CSS, and vanilla JavaScript with no frameworks. The look matches the dark navy and antique gold branding I’ve been using.

## Files

- `index.html` — home page with links to the three calculators
- `numerology-calculator.html` — full Pythagorean reading
- `personal-day-calculator.html` — Personal Year / Month / Day
- `deeper-meanings-calculator.html` — Life Cycles, Pinnacles, Challenges, Maturity Number, Karmic Lessons

Keep all four files in the same folder so the navigation links work.

## How to use

Just open `index.html` in any modern browser. Everything runs locally. You can also host the files on GitHub Pages or any static host.

### On iPhone / iPad (Safari)
1. Open the page in Safari.
2. Tap the Share button.
3. Choose **Add to Home Screen**.
4. It will open full-screen like an app. All data stays on your device.

### On Android (Chrome)
1. Open the page in Chrome.
2. Tap the three-dot menu → **Add to Home screen**.
3. Confirm. It appears as an icon and works offline after the first load.

### Windows app coming soon

## Notes

- Saved readings are stored only in that browser’s local storage.
- You can export a JSON backup and import it on another device or browser.
- Clearing site data will remove saved readings.
- No internet connection is required after the pages have loaded once.

---

## Privacy

Nothing you enter is sent anywhere. Saved readings live in your browser's local storage, which is separate for each device and browser. Use Export backup to move them.

## Disclaimer

Numerology is a traditional symbolic system for reflection and entertainment. It is not a scientifically validated predictive method, and nothing here is professional, financial, legal or medical advice.

## License

Copyright (C) 2026 Carl Broom

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. See the `LICENSE` file for the full text.

In plain terms (a summary, not legal advice):

- You may use, study, modify and share this software, including commercially.
- Copies and modified versions must stay under the AGPL-3.0, keep the copyright and license notices, and say what you changed.
- If you run a modified version for other people over a network, you must offer them the corresponding source code.
- The software comes with no warranty.

**Credit:** please keep the footer credit line and copyright notices in every copy and modified version.

**Name and logo:** the "Broom's Numerology Calc" name and logo are my branding. Please do not use them to brand modified versions.
