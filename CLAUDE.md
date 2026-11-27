# Project: JONASAN KABU (JNK)

## Overview
- Japanese stock study dashboard hosted on GitHub Pages (`index.html` + `stocks.json`).
- Backend for stock addition is Google Apps Script (GAS) Web App (`GAS_WEB_APP_URL`).

## UI & Design Rules for `index.html`
- Brand title: `JONASAN KABU (JNK)` (logo badge: `JNK`).
- Keep UI minimal and mobile-friendly (especially iPhone / Safari).
- Keep only essential links (Yahoo! Finance, IR/PDF link) and core chart controls (`5m`, `1h`, `1M`, `1Y`, `5Y`, candlestick/line, stock selector, `+ 追加` modal).
- Keep chart height compact (around 360px on desktop, 235px on mobile) so it does not look overly tall on iPhone.
- Always preserve the existing `GAS_WEB_APP_URL` value inside `index.html` unless explicitly instructed to change it.

## Git Workflow
- After editing `index.html` or other files, always run `git status`, `git add .`, `git commit -m "<clear Japanese message>"`, and `git push origin main`.
- Report the commit hash and push result clearly.
