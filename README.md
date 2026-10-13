# ACCL VRM — Production Performance / OEE Loss Diagnostic

Single-file HTML dashboard for **ACCL — Cement Grinding (VRM)** covering **VRM-1 & VRM-2**, shifts A–D.

## Features
- **Toggle:** Last day (12-Oct-2026) and Month-to-date (Oct 2026)
- OEE KPIs (Availability / Performance / Quality / Overall OEE) vs target **75%**
- Where time is going (planned / available / down)
- OEE by mill + Find-the-bottleneck (OEE factor constraint)
- Top production losses + loss by category (min)
- **Opportunity Loss = NPT min ÷ ideal cycle time (min/MT)** → lost output (MT)
- Production & OEE trend (last 16 days)
- Shift Action Board — NPT reasons with **responsible team** tagging
- Shift OEE and Gemba walk

## Data source
`Production Report` and `VRM Breakdown` tabs of the ACCL VRM OEE sheet.

## Usage
Open `ACCL_VRM_OEE_Dashboard.html` in any browser. Use the toggle to switch reporting period. Print (Ctrl+P) to PDF for a one-pager.

## Notes
- OEE = Availability × Performance × Quality.
- OEE target = 75% (management target); A/P/Q targets 90/95/99% are benchmarks.
- Data through 12-Oct-2026.
