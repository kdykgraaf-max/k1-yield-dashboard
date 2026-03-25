# K1 Proto Yield Dashboard — v2

**Live:** https://blockcell.sqprod.co/sites/k1-yield-dashboard/
**GitHub:** https://github.com/kdykgraaf-max/k1-yield-dashboard

## Overview
K1a Proto Build yield dashboard covering 3 PCBA types (SPE, MLB, Sensor) + FATP.
Proto build is the 1st build for K1a product (Jan–Mar 2026) at Wistron MYS.

## Version History
- **v2** (2026-03-25) — Full FATP station data, pareto charts, and FA/CA tables populated from FA Tracker + MIL doc. Persistent Gist save/load with PAT token. All 4 product areas fully functional.
- **v1** (2026-03-25) — Initial dashboard with SPE/MLB/Sensor data, FATP placeholder.

## Features
- 🔬 Yield Intelligence Summary with PCBA comparison chart
- 📈 FPY & LPY Over Time per PCBA type (SPE, MLB, Sensor, FATP)
- 📊 Retest Rate & Failure Rate by Station (collapsible detail tables)
- 📉 Dynamic Pareto Charts (Top 10/All with cumulative line) — 8 paretos total
- 📋 Collaborative FA/CA Action Tables with root cause categories, numbered CAs, DRI contacts
  - Pre-populated from MIL doc, FA Tracker, and Yield Bridge & MIL report
  - Editable Risk/FA/CA/DRI cells
  - 💾 Save for Everyone (GitHub Gist persistence with PAT)
  - 🔄 Reload Latest
  - 📜 Version History with preview & restore
- 📸 Export to Image (html2canvas)
- 📊 Export to Excel (xlsx.js)
- 🗂️ Sidebar Navigation with yield badges per PCBA
- ☀️/🌙 Light/Dark Mode

## Data Sources
- [K1 Proto SMT ATE - SPE (Final)](https://docs.google.com/spreadsheets/d/1gETsJTjs3BINow7GBkVpx4mCgFpdoOhih23Y8eLsAmc) — Cut-off: Feb 13, 2026
- [K1 Proto SMT ATE - MLB (Final)](https://docs.google.com/spreadsheets/d/14rcp886vhlcXHSjAvRqR5cJfTObh_Ui3v66ckLN39DQ) — Cut-off: Feb 25, 2026
- [K1 Proto SMT ATE - Sensor (Final)](https://docs.google.com/spreadsheets/d/1TL5RjYiPAyAyJAVvaasm4YtZrQmalRx6bzja2a6DNTo) — Cut-off: Feb 12, 2026
- [K1 Proto FATP (Final)](https://docs.google.com/spreadsheets/d/1id7ZF_wlE2DXr0dptFbMxyHpu_d4z348) — Cut-off: Mar 18, 2026
- [K1 Proto Yield Bridge & MIL](https://docs.google.com/document/d/1oEKgefrrKCtogRtFGaIgIkpTl2uRLWYITVexFr2Cen0) — FA/CA source
- [K1 Proto FA Tracker](https://docs.google.com/spreadsheets/d/1hBt_Z4eCtPBH9QZNdQFmp9gf3Rc7Az_P0l2s4QYDelo) — Detailed failure analysis
- [Source Folder](https://drive.google.com/drive/folders/1ssXqBGIJU_BL7yXAMbbbPo3edATShSmH)
