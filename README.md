# skill-solis

An [agent skill](SKILL.md) for the **Solis 26 tractor** (International Tractors Limited / Sonalika; 9+9 speed transmission, Mitsubishi diesel) and the **implements/attachments** used with it. The skill focuses on the tractor as the main machine and references each attachment separately.

Each source manual — text **and** all informative diagrams, icon legends, warning pictograms, and tables converted to text — is reorganized into one navigable knowledge base for operating, servicing, and troubleshooting the equipment. Equipment is separated into per-part folders under `references/`:

- **Solis 26 tractor** (main) — official Operator Manual, Pub. No. S2618T/J20/28, Aug 2020 (92 pages, 8 chapters).
- **Quicke Multigrab C / CS** grab bucket — front-loader attachment by Ålö AB (Quicke), doc 60081299 E (English section, 7 chapters).
- **KRPAN 4 EP / 5, 6, 8 ERP** single-drum forest winch — three-point-linkage / PTO implement by KRPAN d.o.o., **translated from the Czech manual** (rev. 03.02.2025, 8 references).
- **Agromasz Ł-103U** front loader (300 kg) — front-mounted loader by Zakład Metalowy "Agromasz" (Poland), **explicitly approved for the Solis 26**, **translated from the German manual** (8 references).

## Structure

```
SKILL.md   Hub: equipment list, per-chapter reference index, answer protocol,
           and tractor quick-reference tables (focused on the Solis 26)
references/
├── solis-26/                               # MAIN — the tractor (8 chapters)
│   ├── 01_INTRODUCTION_AND_IDENTIFICATION.md   Front matter, serial/plate locations, universal symbols
│   ├── 02_WARRANTY_AND_SAFETY.md               Warranty terms + full safety notes & decals
│   ├── 03_INSTRUMENTS_AND_CONTROLS.md          Controls, instrument panel, switches, fuses, seat
│   ├── 04_OPERATION.md                         Start/drive/stop, PTO, hydraulics, speed chart, ROPS
│   ├── 05_MAINTENANCE.md                       Service schedule, fluids, filters, electrical, greasing
│   ├── 06_TECHNICAL_SPECIFICATIONS.md          Full datasheet + matching implements
│   ├── 07_DOS_AND_DONTS.md                     System-by-system do's & don'ts
│   └── 08_TROUBLESHOOTING_AND_INDEX.md         Fault diagnosis, service record, A–Z index
├── agromasz-l-103/                         # IMPLEMENT — front loader (front-mounted; for Solis 26)
│   ├── 00_OVERVIEW.md                          Part hub: identity, specs, safety, section index
│   ├── 01_INTRODUCTION_AND_SAFETY.md           Machine ID; EU declaration; intended use; safety + decals
│   ├── 02_TECHNICAL_DATA_AND_CONSTRUCTION.md   Full spec table; construction diagram
│   ├── 03_INSTALLATION_AND_CONNECTION.md       Subframe fitting; tractor coupling; tool change
│   ├── 04_CONTROL_VALVE.md                     Cab joystick: lever moves → loader actions
│   ├── 05_OPERATION.md                         Pre-op checks; transport; loading technique
│   ├── 06_MAINTENANCE_LUBRICATION_STORAGE.md   Servicing; grease points; storage; options
│   ├── 07_TROUBLESHOOTING_AND_RISK.md          Fault → cause → remedy; residual risk
│   └── 08_SPARE_PARTS_CATALOG.md               Exploded drawings → parts tables
├── quicke-multigrab-c/                     # IMPLEMENT — grab bucket (mounts on a front loader)
│   ├── 00_OVERVIEW.md                          Part hub: identity, key specs, safety, section index
│   ├── 01_PREFACE.md                           Using the manual; type-plate fields
│   ├── 02_SAFETY.md                            Decals, signal words, hazards
│   ├── 03_DESCRIPTION.md                       What it is; bolt-on accessories
│   ├── 04_DRIVING_INSTRUCTIONS.md              Designated use, pre-op checks, parking
│   ├── 05_LUBRICATION_AND_MAINTENANCE.md       Greasing, storage, hydraulics
│   ├── 06_DATA.md                              Dimensions, weights, recommendation matrices
│   └── 07_WARRANTY_AND_CONFORMITY.md           Warranty; EU/UK Declarations of Conformity
└── krpan-forest-winch/                     # IMPLEMENT — forest winch (3-point + PTO)
    ├── 00_OVERVIEW.md                          Part hub: identity, specs, safety, section index
    ├── 01_INTRODUCTION_AND_TECHNICAL_DATA.md   Most-important instructions; full spec table
    ├── 02_SAFETY_SIGNS_AND_SAFE_WORK.md        Decals; safe-work rules; PTO/cardan-shaft setup
    ├── 03_USE_AND_CABLE_HANDLING.md            Attaching, skidding, wire-rope handling & damage
    ├── 04_ADJUSTMENT_AND_GUIDE_PULLEY.md       Clutch, pre-brake, brake; lower guide pulley
    ├── 05_MAINTENANCE.md                       Chain tensioning/lubrication; shaft care; plan
    ├── 06_FAULTS_AND_TROUBLESHOOTING.md        Improper use; fault → cause → remedy
    ├── 07_CLEANING_TRANSPORT_STORAGE.md        Cleaning, transport, disconnection, storage
    └── 08_TORQUE_WARRANTY_CONFORMITY.md        Bolt-torque table; warranty; CE declaration
source/
├── Solis-26-99-user-manual.pdf                Tractor manual
├── 60081299 E Multigrab C … .pdf              Grab-bucket manual (14 languages)
├── Návod_k_obsluze_4_EP_5-8_ERP_… .pdf        Forest-winch manual (Czech)
└── Agromasz Frontlader L103.pdf                Front-loader manual (German)
```

## Usage

Start at [`SKILL.md`](SKILL.md). It opens with the **equipment list**, then the tractor's consolidated reference & section index (each chapter: when to use it, a summary, and what every section covers), a summary of each **attachment**, an answer protocol, and tractor quick-reference tables (specs, fluids, intervals, torques, warning lights, fuses). Open the matching file under [`references/solis-26/`](references/solis-26/) for tractor detail, or start at the attachment's overview (e.g. [`references/quicke-multigrab-c/00_OVERVIEW.md`](references/quicke-multigrab-c/00_OVERVIEW.md)) for an implement.

> ⚠️ This is a community-distilled reference, not an official publication. Always defer to the original manuals and an authorized dealer for safety-critical procedures and exact specifications for your specific unit.

## License

[MIT](LICENSE) — for the distillation/formatting (and the English translations of the winch and front-loader manuals). The underlying manual content is © its respective manufacturers (International Tractors Limited / Sonalika for the Solis 26; Ålö AB / Quicke for the Multigrab C; KRPAN d.o.o. for the forest winch; Zakład Metalowy "Agromasz" for the Ł-103U front loader).
