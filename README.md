# skill-solis

An [agent skill](SKILL.md) distilled from the official **Solis 26 tractor Operator Manual** (International Tractors Limited / Sonalika; 9+9 speed transmission, Mitsubishi diesel — Publication No. S2618T/J20/28, Aug 2020).

The full 92-page manual — text **and** all informative diagrams, icon legends, warning pictograms, and tables converted to text — is reorganized into one navigable knowledge base for operating, servicing, and troubleshooting the tractor.

## Structure

```
SKILL.md                  Hub: overview, a consolidated reference & section index,
                          an answer protocol, and quick-reference tables
references/
├── 01_INTRODUCTION_AND_IDENTIFICATION.md   Front matter, serial/plate locations, universal symbols
├── 02_WARRANTY_AND_SAFETY.md               Warranty terms + full safety notes & decals
├── 03_INSTRUMENTS_AND_CONTROLS.md          Controls, instrument panel, switches, fuses, seat
├── 04_OPERATION.md                         Start/drive/stop, PTO, hydraulics, speed chart, ROPS
├── 05_MAINTENANCE.md                       Service schedule, fluids, filters, electrical, greasing
├── 06_TECHNICAL_SPECIFICATIONS.md          Full datasheet + matching implements
├── 07_DOS_AND_DONTS.md                     System-by-system do's & don'ts
└── 08_TROUBLESHOOTING_AND_INDEX.md         Fault diagnosis, service record, A–Z index
source/
└── Solis-26-99-user-manual.pdf             Original source manual
```

## Usage

Start at [`SKILL.md`](SKILL.md). It opens with a consolidated reference & section index (each chapter: when to use it, a summary, and what every section covers), followed by an answer protocol and quick-reference tables (specs, fluids, intervals, torques, warning lights, fuses). Open the matching file under [`references/`](references/) for the full chapter detail.

> ⚠️ This is a community-distilled reference, not an official ITL/Sonalika publication. Always defer to the original manual and an authorized dealer for safety-critical procedures and exact specifications for your specific unit.

## License

[MIT](LICENSE) — for the distillation/formatting. The underlying manual content is © International Tractors Limited.
