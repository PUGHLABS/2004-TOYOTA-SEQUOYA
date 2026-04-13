# 2004 Toyota Sequoia — Project Skills & Context

## Vehicle
- **Year/Make/Model:** 2004 Toyota Sequoia 4X4 Limited
- **VIN:** 5TDBT48A14S230766
- **Engine:** 4.7L V8 2UZ-FE
- **Transmission:** 4-speed automatic A750F (4WD)
- **Color:** Phantom Gray Pearl
- **Owner:** Spokane, WA 99203
- **Customer #:** 8020698 (Findlay/LHM dealer system)
- **Purchased:** 02-22-2022, Spokane WA — $10,000 @ 100,927 mi (do not name the dealer)
- **Current Mileage:** 170,181 mi

## Project
Local HTML service dashboard (`index.html`) consolidating all service records. Goal is 100% verified data from 53 scanned invoice images.

- **Layout:** Dashboard Split View (Layout A) — left panel = recommended work, right panel = service history
- **Theme:** Dark default (`#002451` bg, `#ff7900` accent) with light mode toggle
- **CSS:** Separated into `styles.css` (linked from index.html)
- **Data source:** 53 JPG images in `sequoia pdfs/` + `factory maintence schedule.pdf`

## Primary Dealers
- **Findlay Toyota Spokane** — 1128 W 3rd Ave, Spokane WA 99201 — (509) 455-8770 — current dealer
- **Larry H. Miller Downtown Toyota Spokane** — same address — former name (pre ~mid-2022)
- **Don Ringler Toyota** — Temple, TX — used Dec 2021 (owner was in Texas)

## Key Rules
- Camshaft seals and rear crankshaft seal are **SEPARATE jobs** (different labor, different access)
- Costco tires total = $1,086 (confirmed)
- Steering rack **REPLACED** Oct 2024 — PS hoses still original and separate
- CV axles **REPLACED** Oct 2024 — front diff axle **SEALS** are a separate outstanding item
- Front struts replaced **Oct 2024** (NOT March 2022)
- Timing belt done **March 2022 @ 139,367 mi** (Larry H. Miller)
- Invoice #409384 (Jun 2025) = fuel sending unit replacement, NOT transmission/diff service
- Do not include dealer name for the purchase — just city and state

## Factory Maintenance Schedule (SUV/Truck 4WD)
- **Every 5k:** Oil change + tire rotation
- **Every 5–15k:** Propeller shaft lubrication (4WD — CRITICAL, no records ever found)
- **30k:** Spark plugs (Sequoia explicitly listed), air filter
- **60k:** Initial timing belt inspection
- **90k:** Replace timing belt + spark plugs
- **100k:** Replace engine coolant (then every 50k)

## Outstanding Recommended Work (as of Feb 2026 @ 170,181 mi)
Priority: safety → longevity → cost

1. Brake Fluid Flush — ~$200 (last done Oct 2022 @ ~144,500 mi)
2. PS Pressure Hose — $209.95 (Feb 2026, noted "clean and recheck")
3. PS Return Line — $1,386.05 (Feb 2026)
4. Rear Struts — $883 (Feb 2026 pre-work order)
5. Camshaft Seals (both banks, labor only) — $1,480 (Feb 2026)
6. Rear Crankshaft Seal — $1,808.63 (Feb 2026 pre-work order)
7. Front Differential Axle Seals — $452.70–$516.72 (May 2025 and Feb 2026)
8. Spark Plugs (8 plugs, V8) — ~$400–500 (20k overdue)
9. Engine Coolant — ~$150–200 (20k overdue)
10. Propeller Shaft Lubrication — ~$30 (no records ever found)

## Files
- `index.html` — main dashboard (links to styles.css)
- `styles.css` — all CSS (dark/light theme variables + layout)
- `FSD.md` — original project brief
- `skills.md` — this file
- `sequoia pdfs/` — 53 JPG images of service invoices (all dated 20260412_*.jpg)
- `factory maintence schedule.pdf` — Toyota factory maintenance schedule PDF
