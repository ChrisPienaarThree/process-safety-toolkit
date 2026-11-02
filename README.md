# Process Safety Analysis Toolkit

Six browser tools for recording and calculating a process hazard analysis (PHA), with Excel workbooks,
guides and worked examples:

- **What-If / Checklist Analysis** – What-If / Checklist study (CCPS) between the HAZID and the HAZOP: checklist library, What-If worksheet, hand-over to the HAZOP.
- **HAZOP Study Manager** – study, team, PSI, nodes, deviations with causes, safeguards (Safeguard / IPL, LOPA flag), a LOPA study list and recommendations; imports the HAZOP workbook.
- **LOPA Study Manager** – layer of protection analysis of the HAZOP's LOPA study list: explicit or implicit LOPA, five receptors, IPL credit adjudication (seven tests including cyber), a sourced rules check, SCAI register, ALARP record and bow-tie export; results go back to the HAZOP.
- **Fault Tree & PFD Calculator** – exact top-event probability, time-averaged PFDavg, common cause, cut sets,
  importance, uncertainty and an IEC 61508 SIF calculator.
- **Event Tree Analysis** – outcomes of an initiating event against frequency targets.
- **Bow Tie Analysis** – threats, barriers, consequences, barrier condition and criticality.

**Open the toolkit:** https://chrispienaarthree.github.io/process-safety-toolkit/

- The Launch Centre opens each tool on the page (with its quick start, examples and saving notes) or in its own tab.
- Works in any modern browser. In Google Chrome or Microsoft Edge you can link a study to a file on your computer
  (File ▸ Save as… (link file)); every change is then written to it. Other browsers: Download / Import backup.
- Your work stays in your own browser and in the files you save. Nothing is sent anywhere.
- To use it offline (for example from a USB stick), download this repository as a ZIP, unzip it and open
  `START HERE.html`.

All example data are **illustrative** – replace them with site and vendor data before use. The calculators are
teaching and screening tools, not a substitute for a competent PHA team or a verified SIL calculation.

Course material for process safety and PHA / HAZOP training (Istec Training).

## Licence

- **Software** (the HTML, CSS and JavaScript of the tools and the Launch Centre): MIT licence, see [`LICENSE`](LICENSE).
- **Documents and content** (guides, reference, workbooks, worked examples): CC BY 4.0, see [`LICENSE-DOCS.md`](LICENSE-DOCS.md).
- **Excluded:** `Examples/Steel Works Gas Network PHA/` is not licensed; see [`LICENSE-DOCS.md`](LICENSE-DOCS.md).
- **Third-party components:** SheetJS (Apache 2.0) and the bundled fonts (SIL OFL 1.1), see [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md).
