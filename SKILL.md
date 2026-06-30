---
name: solis-26-tractor
description: Use this skill for any question about the Solis 26 tractor (International Tractors Limited / Sonalika; 26 HP-class, 9+9 speed transmission, Mitsubishi diesel) — operation, starting/cold-start, controls & instruments, maintenance schedules, fluids/oils/coolant and capacities, lubrication & greasing, fuses & electrical, PTO, hydraulics & 3-point linkage, ROPS, tyres & ballasting, troubleshooting/fault diagnosis, technical specifications, matching implements, warranty, and safety. Based on the official Solis 26 Operator Manual (Pub. No. S2618T/J20/28, Aug 2020). Triggers on questions about Solis/Sonalika tractor operation, service intervals, oil/fuel/coolant specs, torque values, warning lights, or any control, warning, or fault on this tractor.
---

# Solis 26 Tractor — Operator Manual Skill

**Source:** _Operator Manual — Solis 26 (Tractor with 9+9 Speed Transmission)_, International Tractors Limited (ITL) / Sonalika, Hoshiarpur, India. Publication No. **S2618T/J20/28**, Revision 1, **August 2020**. Part Code **300190111A**. Written in compliance with **ISO 3600**. (92 pages, 8 chapters.)

The original PDF lives in [`source/Solis-26-99-user-manual.pdf`](source/Solis-26-99-user-manual.pdf). Every chapter has been distilled — text **and** all informative diagrams, icon legends, warning pictograms, and tables converted to text — into the files under [`references/`](references/).

---

## Overview

The **Solis 26** is a compact ~26 HP utility tractor built by **International Tractors Limited (Sonalika)** in India and sold internationally under the *Solis* brand. It uses a **3-cylinder Mitsubishi diesel** engine, a **9 forward + 9 reverse** constant-mesh transmission (3-speed gear shifter × High/Mid/Low range), oil-immersed brakes, power steering, a 540/540E rear PTO, and a position-controlled 3-point hydraulic linkage (≈600 kg lift). It ships standard with a foldable **ROPS** safety frame and seat belt.

This skill is the complete, navigable knowledge base for **operating, servicing, and troubleshooting** that tractor. Use it to answer operator questions precisely, with the manual's exact procedures, intervals, capacities, and torque values.

---

## How to Answer (use every time)

1. **Safety first.** If the question touches operation, maintenance, fluids, electrics, or anything near moving parts, lead with the relevant **WARNING / CAUTION / DANGER** from [`references/02_WARRANTY_AND_SAFETY.md`](references/02_WARRANTY_AND_SAFETY.md). Never give a procedure that skips a safety step the manual states.
2. **Find the exact section.** Use the **Topic → Reference index** below to open the right file, then **lead with the manual's exact procedure, values, intervals, torques, and capacities** — quote them precisely, keeping both metric and the manual's imperial conversions where given.
3. **Cite the location** (chapter + section + page) so the user can verify in the source PDF.
4. **Operator vs dealer.** Distinguish operator-serviceable tasks from those the manual routes to an **authorized dealer/workshop** (valve clearance, FIP/injection, oil-pressure faults, hydraulic pump/valve, internal repairs). Say which it is.
5. **Don't invent specs.** If a value isn't in the references, say so — don't guess. Recommend confirming with an ITL/Solis dealer, quoting the **Chassis No. + Engine No.**
6. **Engine variants.** Some values differ between the **Stage III** and **Stage V** emission variants (rated rpm, low idle, injection timing). Note the variant when it matters.

---

## The Tractor at a Glance

| Item | Value | Detail in |
|---|---|---|
| Model / type | Solis 26 — tractor with **9F + 9R** speed transmission | Ch.1 / Ch.6 |
| Engine | **Mitsubishi MVS3L2**, 3-cyl, 4-stroke, naturally aspirated, water-cooled, OHV diesel | Ch.6 |
| Displacement / bore × stroke | **1318 cc**, 78 × 92 mm, compression **22:1**, firing order **1-3-2** | Ch.6 |
| Rated engine speed | **2700 rpm** (Stage III) / **2500 rpm** (Stage V); low idle ~1000 rpm | Ch.6 |
| Transmission | Constant-mesh / synchromesh; single mechanical clutch; 9F+9R (gear × H-M-L) | Ch.4 / Ch.6 |
| PTO | **Type-I**, 540 @ 2565 ERPM and **540E** @ 2083 ERPM (rear) | Ch.4 / Ch.6 |
| Hydraulic lift capacity | **600 kg** (1322.8 lb); position-control 3-point linkage | Ch.4 / Ch.6 |
| Brakes / steering | Oil-immersed brakes; hydrostatic **power steering** | Ch.4 / Ch.6 |
| Turning circle (min) | **5.14 m** LHS / **5.09 m** RHS | Ch.6 |
| Tyres | Front **6.00 × 12**, Rear **8.30 × 20** | Ch.4 / Ch.6 |
| Dimensions | Wheelbase 1570 mm · length 2945 mm · width 1245 mm · height-to-ROPS 2442 mm · ground clearance 240 mm | Ch.6 |
| Weight (with driver) | **1120 kg** (front 425 kg / rear 580 kg) | Ch.6 |

> **NOTE:** Per the manual, "all dimensions & specifications are for guidance purpose" and ITL may modify without notice. Always confirm against the statutory plate and your dealer for your exact unit.

---

## Fluids, Capacities & Grades (quick reference)

| System | Capacity | Grade / spec | Change interval |
|---|---|---|---|
| Engine oil | **4.2 L** (1.11 US gal) | SAE **10W40** (15W40 in hot climate) | First **50 h**, then **every 250 h** (R every service) |
| Transmission / hydraulic | **23 L** (4.75 US gal) | SAE **80W** | **1000 h** |
| 4WD front axle | **2.7 L** (0.71 US gal) | **EP-80** | **50 / 500 / 1000 / 1500 h** |
| Fuel (HSD diesel) | tank **29 ± 3 L** (7.66 US gal); keep ≥ 6 L to avoid air-lock | HSD per **IS:1460-2000**, density 0.840 g/cm³ | — |
| Coolant | radiator + reserve to FULL line | antifreeze **Glysantin G40** (mix 10–60% by temperature) | flush ~yearly / 1000 h |

> Fuel storage: use **black iron cans only — never galvanized** (it reacts and spoils the injection pump/injectors). No diesel-alcohol mixtures. Fill at end of day's work to limit condensation. Full lubricant viscosity-vs-temperature chart and the oil & lubrication chart are in **Ch.5**.

---

## Service Intervals (the short version)

Service points: **50 h** (first) → **250 → 500 → 750 → 1000 → 1250 → 1500 h**, then repeat every **250 h**.
Schedule legend: **R** Replace · **C** Check · **CT** Check & Tight · **CA** Check & Adjust · **CL** Clean · **W** Wash · **G** Grease.

| Task | Interval |
|---|---|
| Engine oil + oil filter | **R every service** (first 50 h, then 250 h) |
| Air cleaner element | Clean first 50 h, then 250 h / when clog lamp glows; **replace at 750 h** (or after 3 cleanings) |
| Hydraulic suction strainer | Clean / **replace at 750 h** |
| Transmission oil | **1000 h** |
| Front-axle (4WD) oil | **50 / 500 / 1000 / 1500 h** |
| Fuel tank clean-out | **500 h** |
| Engine-oil system flush | yearly / **1000 h**, whichever first |
| Grease all points | per schedule (see 10 points below) |

The **full two-part maintenance schedule table** (every component × every interval) is in [`references/05_MAINTENANCE.md`](references/05_MAINTENANCE.md).

---

## Key Torques, Adjustments & Pressures

| Item | Value |
|---|---|
| Rear wheel nut torque | **130 Nm** (103 lbf-ft) |
| Front wheel nut torque | **72 Nm** (53 lbf-ft) |
| Clutch pedal free play | **25–30 mm** (0.98–1.18 in) |
| Brake pedal free play | **25–30 mm** (0.98–1.18 in) |
| Alternator V-belt deflection | **10–12 mm** at ~98 N / 10 kgf push midway (Ch.7 states "≤ 10 mm") |
| Tyre pressure — **field** | Front **20–22 PSI** · Rear **14–16 PSI** |
| Tyre pressure — **haulage** | Front **22–24 PSI** · Rear **16–18 PSI** |
| Front ballast (default / max coupling load) | 2 × 15 kg = **30 kg** default; max vertical load on coupling/rear hitch **248 kg-f** |
| Differential lock | use straight only; **disengage before turning**; never engage above **6 km/h** on turns |
| Greasing points (10) | Clutch actuator shaft ×2, brake pedal shaft ×2, lift rods ×2, front axle pivot pin ×1, power-steering cylinder ×1, tie rod ×2 |

---

## Instrument & Warning Lights (operator quick guide)

| Indicator | When it glows | Action |
|---|---|---|
| **Battery charge** | With ignition ON / engine off = normal. **Glows while running = charging fault** | Stop and get charging system checked |
| **Engine oil pressure** | Low oil pressure | Stop engine immediately; check oil level/system |
| **Air cleaner clogging** | Filter choked | Clean air cleaner element with compressed air |
| **Coolant temperature gauge** | RED = overheating (GREEN = normal) | Reduce load; **never open a hot radiator cap** |
| **Fuel gauge** | RED zone = low | Refill (keep ≥ 6 L to avoid air-lock) |
| **Glow plug / cold start** | Pre-heat active | Wait until it goes off before cranking |
| **PTO monitor** | PTO engaged | Be aware rotating PTO is live |
| Park brake / turn / high-beam / work-lamp / trailer | status lamps | informational |

> Ignition key: **1 = OFF** (key removable) · **2 = ON + HEAT** (run position; glow plug heats) · **3 = START** (auto-returns to ON). **Crank max 5–8 s**; wait 5–10 s (1 min after every 2 failed attempts) before re-cranking, or you may damage the starter. **Never use ether / starting fluid.** Full instrument-panel and dashboard detail in [`references/03_INSTRUMENTS_AND_CONTROLS.md`](references/03_INSTRUMENTS_AND_CONTROLS.md).

---

## Fuse Box (ratings)

Fuse box is on the upper radiator bracket. **Never fit a higher-rated fuse or a wire in place of a fuse** (fire risk).

| Circuit | A | Circuit | A |
|---|---|---|---|
| Horn | 10 | Combi. Switch | 20 |
| Plough Lamp | 15 | Mobile Charger | 15 |
| Park | 10 | Battery Aux | 15 |
| Safety Controller | 20 | Revolving Light | 10 |
| LO Beam | 15 | Flasher | 15 |
| HI Beam | 15 | Brake | 15 |
| IGN. Aux | 15 | Aux.1 | 10 |

Relays (5-pin, terminals 30/85/86/87/87A): **PTO Auto, OPC, OPC Switch, Engine Stop, Aux. Start**. Full box layout + diagram in **Ch.5 §5.22**.

---

## Safety Essentials

**Signal-word hierarchy** (know which is which when quoting the manual):

| Word | Meaning |
|---|---|
| **DANGER** | Will result in death / very serious injury |
| **WARNING** | Could result in death / very serious injury |
| **CAUTION** | May result in minor injury |
| **IMPORTANT** | Property / equipment damage |
| **NOTE** | Useful information |

- **OPC (Operator Presence Control):** leave the seat with PTO ON and the engine **auto-stops in ~5–7 s**; restart needs all levers neutral + brake pressed.
- **ROPS + seat belt:** wear the belt **only with ROPS up and locked**; never with ROPS folded. A damaged ROPS must be **replaced, not repaired**. Never weld/drill/bend it; never hitch a pull-chain to it (back-flip risk) — **pull only from the drawbar**.
- **Mount/dismount** from the **left** using three-point contact; never from a moving tractor.
- **Towing a disabled tractor:** never faster than **10 km/h**, with someone steering and braking it.
- **Battery acid:** flush skin with water, eyes 10–15 min, get medical help; never add water to electrolyte.
- **Hot radiator:** never remove the cap hot — open to the safety catch (~⅓ turn) first.
- **Fire (PASS):** Pull, Aim low, Squeeze, Sweep. At the first sign of fire, get off and stay clear.
- **Lightning = DANGER:** hear thunder → shut down and move to a sturdy building.
- Noise at operator's ear **< 86 dB**; vibration **< 1.25 m/s²**.

Full warnings, PPE list, all themed safety notes, and the six on-tractor **safety decal locations** are in [`references/02_WARRANTY_AND_SAFETY.md`](references/02_WARRANTY_AND_SAFETY.md).

---

## Identification (for parts & service)

Always quote **Chassis No.** and **Engine No.** when ordering parts or contacting the dealer.

- **Chassis serial number:** punched on the **right side of the front axle bracket**; also engraved on the statutory plate.
- **Engine serial number:** stamped on the upper FIP mount, **right side of the cylinder block**; also on the engine rocker-cover sticker.
- **Statutory plate:** on the **left-hand fender** (chassis no., permissible masses, towable-load matrix).
- **ROPS certificate plate:** riveted on the ROPS (EEC type-approval, ROPS serial, model).

Directional convention used throughout the manual: **Left/Right** = as seated facing forward; **Front** = radiator end; **Rear** = drawbar end.

---

## References

Each chapter of the manual is a single self-contained reference. Open the one that matches the question.

- [**01 — Introduction & Identification**](references/01_INTRODUCTION_AND_IDENTIFICATION.md) — Front matter (cover, preface, ITL contacts, ISO 3600 compliance) plus how to use the manual, directional terminology, chassis/engine serial-number and statutory/ROPS plate **locations**, and the complete legend of **~30 universal symbols**. *(pp.1–15)*
- [**02 — Warranty & Safety**](references/02_WARRANTY_AND_SAFETY.md) — Warranty terms, pre-delivery/installation, warranty procedure, parts warning, "if you move", service after warranty; then the **full Safety Notes** — every themed warning/caution/note (PPE, starting, tipping, fluids, fuel/fire, maintenance, ROPS, loader work, lightning, noise/vibration) and the **six safety-decal locations** with pictograms. *(pp.16–37)* — **the safety-critical chapter.**
- [**03 — Instruments & Controls**](references/03_INSTRUMENTS_AND_CONTROLS.md) — All **15 operator controls** (callout diagram → table), the **14 instrument-panel indicators** (icon legend + descriptions), dashboard switches (hazard, combination, ignition, beacon, PTO external), fuse box, battery & cut-off, **seven-pin trailer socket pin-out**, lights, registration plate, and driver-seat adjustments. *(pp.38–49)*
- [**04 — Operation**](references/04_OPERATION.md) — OPC logic, engine start/stop & cold-weather start, every primary control (clutch, gears, shuttle, PTO, hydraulics/DCV, response valve, H-M-L, diff-lock, steering, brakes), the **full speed chart**, tyre/ballast/**load-carrying** data, three-point-linkage setup, and foldable-ROPS procedure. *(pp.50–66)*
- [**05 — Maintenance**](references/05_MAINTENANCE.md) — The **full periodic service schedule** (50–1500 h, R/C/CT/CA/CL codes), fuel/engine-oil/coolant servicing, filters & air cleaner, clutch/brake free-play, axle/transmission oil changes, **lubricant viscosity chart**, electrical (battery, alternator, starter, **full fuse table**), greasing points, lifting points, and long-idle storage — with all capacities, intervals, and tension/torque values. *(pp.67–82)*
- [**06 — Technical Specifications**](references/06_TECHNICAL_SPECIFICATIONS.md) — The complete **datasheet** (engine, transmission, hydraulics, brakes, steering, PTO, tyres, dimensions, weight) plus the **matching-implements** recommendation table (sizes + operating ERPM for ~10 compatible implements). *(pp.83–85)*
- [**07 — Do's and Don'ts**](references/07_DOS_AND_DONTS.md) — System-by-system **DO's and DON'Ts** (engine, transmission, clutch, hydraulics, brakes, front axle/steering, tyres, electrical) plus fuel-saving, oil-saving, better-performance and safe-operation guidance, with a consolidated intervals/specs quick table. *(pp.86–88)*
- [**08 — Troubleshooting, Service Record & Index**](references/08_TROUBLESHOOTING_AND_INDEX.md) — Diagnostic tables (**Problem → Cause → Remedy** for engine, hydraulic, brakes, electrical, fuel consumption), the blank dealer **service-record** log fields, and the manual's full **A–Z alphabetical index** with page numbers. *(pp.89–92)*

---

## Topic → Reference Index (where to find it)

| If the question is about… | Go to |
|---|---|
| Model, serial numbers, plates, symbols, "what is this tractor" | **01** |
| Warranty, what's covered, safety rules, warning labels, PPE, ROPS safety | **02** |
| What a control/lever/switch does, warning lights, gauges, trailer socket, seat | **03** |
| How to start / drive / stop, PTO, hydraulics, gears, speeds, ballasting, linkage | **04** |
| Service intervals, oil/fuel/coolant change, filters, greasing, fuses, battery, belt | **05** |
| Exact specs, dimensions, weights, capacities, compatible implements | **06** |
| Best-practice tips, what NOT to do, fuel/oil saving | **07** |
| Something is wrong / won't work / diagnosing a fault; service log | **08** |

> When a value appears in more than one place (e.g. service intervals in **05** and **07**, specs in **06** and the at-a-glance table above), treat **Ch.5 / Ch.6** as authoritative and reconcile to them.

---

## Complete Manual Index (every section, with what it covers)

Every section of the manual, grouped by chapter, with a one-line description to help locate the right topic. Each chapter heading links to its full reference.

### [Chapter 1 — Introduction & Identification](references/01_INTRODUCTION_AND_IDENTIFICATION.md)

| Section | What it covers |
|---|---|
| 1.1 Using Operator Manual | How to use the manual; LH/RH/front(radiator)/rear(drawbar) direction convention; keep with tractor; attachment & language notes |
| 1.2 Chassis Serial Number | Where the chassis number is punched — right side of the front axle bracket |
| 1.3 Engine Serial Number | Where the engine number is stamped — FIP mount on RH cylinder block; also on the rocker-cover sticker |
| 1.4 Statutory Plate | LH-fender plate: chassis no., permissible axle masses, towable-load matrix |
| 1.5 ROPS Certificate Plate | EEC type-approval plate on the ROPS (serial, model, approval mark) |
| 1.6 Universal Symbols | Legend of the ~30 ISO pictograms used on instruments and controls |

### [Chapter 2 — Warranty & Safety](references/02_WARRANTY_AND_SAFETY.md)

| Section | What it covers |
|---|---|
| 2.1 Introduction | Purpose and scope of the warranty & safety chapter |
| 2.2 Warranty, Pre-delivery and Installation | What the warranty covers; dealer pre-delivery & installation duties |
| 2.3 Warranty Procedure | How to raise/process a warranty claim |
| 2.4 Parts Warning | Use genuine ITL parts; non-genuine parts can void warranty |
| 2.5 If You Move | Notify the dealer/company of an address or ownership change |
| 2.6 Service After Warranty | Continue servicing at authorized centres once warranty ends |
| 2.7 Guidelines about Safety Sign | Signal-word hierarchy (DANGER/WARNING/CAUTION/IMPORTANT/NOTE); keep decals legible |
| 2.8 Safety: Prepare For Safe Operation | Required PPE — hard hat, goggles, ear muffs, mask, gloves, boots, hi-vis |
| Safety Notes | The full set of themed operating & maintenance warnings (tipping, fluids, fuel/fire, handholds, mired tractor, ROPS, etc.) |
| Safety While Operating Loader Attachments | Loader rules — trained operator over 18, never lift people, stability cautions |
| Safety From Lightning Strike | DANGER-level: on thunder/lightning, shut down and shelter in a sturdy building |
| Noise & Vibration Levels | Operator-ear < 86 dB, bystander < 85 dB, whole-body vibration < 1.25 m/s² |
| Safety Warning & General Information Labels on Tractor | The six on-tractor safety decals and their locations |

### [Chapter 3 — Instruments & Controls](references/03_INSTRUMENTS_AND_CONTROLS.md)

| Section | What it covers |
|---|---|
| 3.1 Tractor Controls | Cabin layout of the 15 numbered controls (steering, pedals, levers) |
| 3.2 Instrument Panel | Layout and icon legend of the 14 dashboard indicators/gauges |
| 3.2.1 Park Brake Indicator | Glows when the parking brake is engaged |
| 3.2.2 Battery Charge Indicator | Charging-system status lamp; glowing while running = charging fault |
| 3.2.3 Air Cleaner Clogging Indicator | Glows when the air filter is choked — clean the element |
| 3.2.4 Left Turn Indicator | Left turn-signal tell-tale |
| 3.2.5 Engine RPM cum Hour Meter | Tachometer plus running-hours meter, with safe-operating zone |
| 3.2.6 Right Turn Indicator | Right turn-signal tell-tale |
| 3.2.7 High Beam Indicator | Glows with headlamp high beam |
| 3.2.8 Cold Start Indicator | Glow-plug pre-heat lamp for cold starting |
| 3.2.9 Oil Pressure Indicator | Low engine-oil-pressure warning — stop engine |
| 3.2.10 PTO Monitor Lamp | Glows when the PTO is engaged |
| 3.2.11 Turn Trailer Lamp | Trailer turn-indicator tell-tale |
| 3.2.12 Temperature Gauge | Coolant temperature (green normal / red overheating) |
| 3.2.13 Fuel Gauge | Tank level (red/amber/green); keep at least 6 L |
| 3.2.14 Work Lamp Indicator | Work-lamp-on tell-tale |
| 3.3 Dashboard Controls | Hazard switch, combination switch, ignition-key positions, beacon switch, PTO external switch |
| 3.4 Fuse Box | Fuse-box location (upper radiator bracket) |
| 3.5 Battery | Battery location and the cut-off switch |
| 3.6 Seven Pin Socket | Trailer socket pin-out (7 pins with wire colours) |
| 3.7 Tractor Light | Head, tail, beacon, plough and plate lights |
| 3.8 Registration Plate | Number-plate mounting and its lamp |
| 3.9 Driver's Seat | Seat adjustments — slide, suspension, height, weight (50–120 kgf), belt, armrest |

### [Chapter 4 — Operation](references/04_OPERATION.md)

| Section | What it covers |
|---|---|
| 4.1 Operator Presence Control (OPC) | Auto-stop safety logic when the operator leaves the seat |
| 4.2 Boarding & Leaving the Tractor | Mount from the LH footrest using three-point contact |
| 4.3 Engine | Engine operation overview |
| 4.3.1 Starting the Engine | Normal start sequence and pre-start checks (gear/range neutral, clutch pressed) |
| 4.3.2 Cold Weather Starting | Glow-plug heat start below 0 °C; never use ether/starting fluid |
| 4.3.3 Running in | Break-in precautions for a new tractor |
| 4.3.4 Turning off the Engine | Correct shutdown procedure |
| 4.3.5 Stopping and Parking | Stopping and parking the tractor safely |
| 4.4 Under Hood Muffler | Hot under-bonnet muffler — burn caution |
| 4.5 Opening the Bonnet | Bonnet release knob and gas strut |
| 4.6 Accelerator Pedal | Foot throttle operation |
| 4.7 Clutch Pedal | Clutch pedal operation |
| 4.8 2WD / 4WD Lever | Engaging/disengaging four-wheel drive |
| 4.9 Hand Throttle Lever | Hand-set engine speed |
| 4.10 Gear Shifter Lever | Three-position main gear selector |
| 4.11 Shuttle Lever | Forward / Neutral / Reverse direction control |
| 4.12 Power Take off (PTO) | 540/540E PTO engagement, shaft guards, driveline, external control switch |
| 4.13 Hydraulic Coupling Devices | Quick-release couplers and DCV lever for remote cylinders |
| 4.14 Response Valve (Transport Lock) | Locks the implement and sets its lowering speed for transport |
| 4.15 Speed Range Selector (H-M-L) Lever | High/Mid/Low range — combines with gears for 9 speeds |
| 4.16 Differential Lock Pedal | Engage diff-lock (straight only; disengage on turns, ≤ 6 km/h) |
| 4.17 Power Steering | Hydrostatic steering; inoperative when the engine is off |
| 4.18 Service Brake | Foot service brakes (independent left/right) |
| 4.19 Parking Brake | Hand parking-brake lever |
| 4.20 Speed Chart | Travel speeds per gear/range across the rear-tyre options |
| 4.21 Wheels and Tyres | Reading tyre markings; recommended field/haulage pressures |
| 4.22 Check Wheel Nut Bolt | Wheel-nut torques (rear 130 / front 72 Nm) and load-carrying capacity |
| 4.23 Ballasting the Front Axle | Front weights (2 × 15 kg) for stability and traction |
| 4.24 Hydraulic Control Lever | Position-control lever for raising/lowering the linkage |
| 4.25 Three Point Linkage | Top link, lift rods and lower links — setup and levelling |
| 4.26 Safety Frame: Roll Over Protection Structure (ROPS) | Roll-over frame and seat belt; folding/unfolding procedure |

### [Chapter 5 — Maintenance](references/05_MAINTENANCE.md)

| Section | What it covers |
|---|---|
| 5.1 Maintenance Schedule | Full periodic service table (50–1500 h) with R/C/CT/CA/CL/W/G codes |
| 5.2.1 Fuel Tank Filling | Filling the diesel tank |
| 5.2.2 Fuel Requisites | Diesel specification (HSD per IS:1460-2000) |
| 5.2.3 Fueling | Refuelling precautions |
| 5.2.4 Fuel Storage | Store in black-iron cans only — never galvanized |
| 5.3.1 Checking Engine Oil Level | Dipstick check (RH side, on level ground) |
| 5.3.2 Replacement of Oil Filter & Engine Oil | Oil + filter change (4.2 L, SAE 10W40) |
| 5.4 Replacement of Fuel Filter | Changing the fuel-filter element |
| 5.5 Air Bleeding of Fuel System | Bleeding air from the fuel lines/FIP |
| 5.6 Radiator | Cooling-system service overview |
| 5.6.1 Coolant Level in Radiator (When Hot) | Checking coolant; opening a hot cap safely |
| 5.6.2 Radiator Draining & Flushing (When cold) | Draining/flushing coolant; antifreeze mix ratios |
| 5.6.3 Radiator Fins Cleaning | Cleaning the radiator fins |
| 5.6.4 Radiator Mesh Cleaning | Cleaning the front mesh screen |
| 5.6.5 Radiator Cap | Use only the genuine pressure cap |
| 5.7 Inspection of Hoses | Checking hoses for leaks and wear |
| 5.8 Air Cleaner Maintenance | Clean/replace the air-filter element; intervals and max air pressure |
| 5.9 Clutch Pedal | Clutch free-play (25–30 mm) |
| 5.10 Brake Pedal Free Play | Brake free-play specification |
| 5.11 Brake Pedal | Brake pedal location and operation |
| 5.12 Brake Pedal Free Play | Adjusting brake free-play (25–30 mm) |
| 5.13 Steering Cylinder Knuckle Joints | Inspecting/greasing the steering knuckle joints |
| 5.14 Oil Changes in 4WD Front Axle | Front-axle oil change (2.7 L EP-80) |
| 5.15 Oil Changes for Transmission, Rear Final Drives and Power Lift Hydraulic Circuits | Transmission/hydraulic oil change (23 L SAE 80W) |
| 5.16 Recommended Oil grades & Application range | Lubricant viscosity-vs-temperature chart |
| 5.16.1 Cleaning of Suction Strainer | Cleaning/replacing the magnetic hydraulic suction strainer |
| 5.17 General Maintenance of Electrical System | Wiring and connection care |
| 5.18 Battery and its Maintenance | Electrolyte level/specific gravity, top-up, removal procedure |
| 5.19 Starter Motor | Starter-motor location and care |
| 5.20 Alternator | Charging alternator overview |
| 5.20.1 Checking V-belt | Inspecting the V-belt condition |
| 5.20.2 Adjusting V-belt tension | Setting belt deflection (10–12 mm) |
| 5.21 Fuses in Fuse Box | Fuse ratings and protected circuits; relay layout |
| 5.22 Long Idle Period | Precautions for long-term storage/lay-up |
| 5.23 Greasing Points | The 10 grease points and their schedule |
| 5.24 Jack Up the Tractor - Lifting Points | Approved jacking and support points |
| 5.25 Oil and Lubrication Chart | Summary of all lubricants, grades and capacities |

### [Chapter 6 — Technical Specifications](references/06_TECHNICAL_SPECIFICATIONS.md)

| Section | What it covers |
|---|---|
| 6.1 Technical Specifications | Full datasheet — engine, transmission, hydraulics, brakes, steering, PTO, tyres, dimensions, weight |
| 6.2 Matching Implements | Recommended implement types/sizes and their operating ERPM |

### [Chapter 7 — Do's and Don'ts](references/07_DOS_AND_DONTS.md)

| Section | What it covers |
|---|---|
| Chapter 7: Do's and Don'ts | System-by-system do's & don'ts plus fuel-saving, oil-saving and performance guidance |

### [Chapter 8 — Troubleshooting, Service Record & Alphabetical Index](references/08_TROUBLESHOOTING_AND_INDEX.md)

| Section | What it covers |
|---|---|
| Troubleshooting | Problem → Cause → Remedy tables (engine, hydraulic, brakes, electrical, fuel consumption) |
| Service Record | Blank dealer service-log fields for recording services |
| Alphabetical Index | The manual's A–Z topic index |
