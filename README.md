# skill-solis

An [agent skill](SKILL.md) for the **Solis 26 tractor** (International Tractors Limited / Sonalika; 9+9 speed transmission, Mitsubishi diesel) and the **implements/attachments** used with it. The skill focuses on the tractor as the main machine and references each attachment separately.

Each source manual — text **and** all informative diagrams, icon legends, warning pictograms, and tables converted to text — is reorganized into one navigable knowledge base for operating, servicing, and troubleshooting the equipment. Equipment is separated into per-part folders under `references/`:

- **Solis 26 tractor** (main) — official Operator Manual, Pub. No. S2618T/J20/28, Aug 2020 (92 pages, 8 chapters).
- **Quicke Multigrab C / CS** grab bucket — front-loader attachment by Ålö AB (Quicke), doc 60081299 E (English section, 7 chapters).

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
└── quicke-multigrab-c/                     # ATTACHMENT — grab bucket (front loader)
    ├── 00_OVERVIEW.md                          Part hub: identity, key specs, safety, section index
    ├── 01_PREFACE.md                           Using the manual; type-plate fields
    ├── 02_SAFETY.md                            Decals, signal words, hazards
    ├── 03_DESCRIPTION.md                       What it is; bolt-on accessories
    ├── 04_DRIVING_INSTRUCTIONS.md              Designated use, pre-op checks, parking
    ├── 05_LUBRICATION_AND_MAINTENANCE.md       Greasing, storage, hydraulics
    ├── 06_DATA.md                              Dimensions, weights, recommendation matrices
    └── 07_WARRANTY_AND_CONFORMITY.md           Warranty; EU/UK Declarations of Conformity
source/
├── Solis-26-99-user-manual.pdf                                          Tractor manual
└── 60081299 E Multigrab C … .pdf                                        Grab-bucket manual (14 languages)
```

## Usage

Start at [`SKILL.md`](SKILL.md). It opens with the **equipment list**, then the tractor's consolidated reference & section index (each chapter: when to use it, a summary, and what every section covers), a summary of each **attachment**, an answer protocol, and tractor quick-reference tables (specs, fluids, intervals, torques, warning lights, fuses). Open the matching file under [`references/solis-26/`](references/solis-26/) for tractor detail, or start at the attachment's overview (e.g. [`references/quicke-multigrab-c/00_OVERVIEW.md`](references/quicke-multigrab-c/00_OVERVIEW.md)) for an implement.

> ⚠️ This is a community-distilled reference, not an official publication. Always defer to the original manuals and an authorized dealer for safety-critical procedures and exact specifications for your specific unit.

## License

[MIT](LICENSE) — for the distillation/formatting. The underlying manual content is © its respective manufacturers (International Tractors Limited / Sonalika for the Solis 26; Ålö AB / Quicke for the Multigrab C).
