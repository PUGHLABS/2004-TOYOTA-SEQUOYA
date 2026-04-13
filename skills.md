# 2004 Toyota Sequoia — Project Skills & Context

## Vehicle
- **Year/Make/Model:** 2004 Toyota Sequoia 4X4 Limited
- **VIN:** 5TDBT48A14S230766
- **Engine:** 4.7L V8 2UZ-FE
- **Transmission:** 4-speed automatic A750F (4WD)
- **Color:** Phantom Gray Pearl
- **Owner:** in Spokane WA 99203
- **Customer #:** 8020698 (Findlay/LHM dealer system)
- **Purchased:** ~02-22-2022, Spokane WA — $10,000 @ 100,927 mi
- **Current Mileage:** 170,181 mi

## Project
This is a local HTML service dashboard (`index.html`) that consolidates all service records for Jeff's Sequoia. The goal is accurate, 100% verified data from 53 scanned invoice images.

- **Layout:** Dashboard Split View (Layout A) — left panel = recommended work, right panel = service history
- **Theme:** Dark default (`#002451` bg, `#ff7900` accent) with light mode toggle
- **CSS:** Separated into `styles.css` (linked from index.html)
- **Data source:** 53 JPG images in `sequoya pdfs/` folder + `factory maintence schedule.pdf`

## Primary Dealers
- **Findlay Toyota Spokane** — 1128 W 3rd Ave, Spokane WA 99201 — (509) 455-8770 — current dealer
- **Larry H. Miller Downtown Toyota Spokane** — same address (1128 W 3rd Ave) — former name (pre ~mid-2022)
- **Don Ringler Toyota** — Temple, TX — used when Jeff was in Texas (Dec 2021)

## Key Rules
- Camshaft seals and rear crankshaft seal are SEPARATE jobs (different labor, different access)
- Costco tires total = $1,086 (user confirmed)
- The steering rack was REPLACED Oct 2024 — PS hoses are still original and separate
- CV axles were REPLACED Oct 2024 — front diff axle SEALS are a separate item still outstanding
- Front struts were replaced Oct 2024 (NOT March 2022 as originally assumed)
- Timing belt was done March 2022 @ 139,367 mi (Larry H. Miller)
- Invoice #409384 (Jun 2025) = fuel sending unit, NOT transmission/diff service

## Factory Maintenance Schedule (SUV/Truck 4WD — from PDF)
- **5k:** Oil change + tire rotation
- **15k:** Inspect differential fluid, steering, driveshaft
- **30k:** Spark plugs (Sequoia explicitly listed), air filter, fuel filter inspect
- **50k:** Replace spark plugs, inspect timing belt
- **60k:** Initial timing belt inspection
- **90k:** Replace timing belt + spark plugs
- **100k:** Replace engine coolant (then every 50k)
- **Every 5-15k:** Propeller shaft lubrication (4WD models — CRITICAL, no records found)

## Outstanding Recommended Work (as of Feb 2026)
Priority order per safety → longevity → cost:
1. Brake Fluid Flush — ~$200 (last done Oct 2022 @ 144,500 mi)
2. PS Pressure Hose — $209.95 (quoted Feb 2026, "clean and recheck" noted)
3. PS Return Line — $1,386.05 (quoted Feb 2026)
4. Rear Struts — $883 (quoted Feb 2026 pre-work order)
5. Camshaft Seals (both banks, labor only) — $1,480 (quoted Feb 2026)
6. Rear Crankshaft Seal — $1,808.63 (quoted Feb 2026 pre-work order)
7. Front Differential Axle Seals — $452.70–$516.72 (quoted May 2025 and Feb 2026)
8. Spark Plugs (8 plugs, V8) — ~$400–500 (19k overdue as of Feb 2026)
9. Engine Coolant — ~$150–200 (19k overdue)
10. Propeller Shaft Lubrication — ~$30 (no records ever found)

## Files
- `index.html` — main dashboard (links to styles.css)
- `styles.css` — all CSS (dark/light theme variables + layout)
- `script.js` — empty, not used (JS is inline in index.html)
- `FSD.md` — original project brief
- `skills.md` — this file
- `sequoya pdfs/` — 53 JPG images of service invoices (all dated 20260412_*.jpg)
- `factory maintence schedule.pdf` — Toyota factory maintenance schedule PDF
