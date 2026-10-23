# CEMMS Estate Demo

A public, clickable demo of CEMMS (Coffee Estate Maintenance and Management System). It shows the daily flow on a coffee estate, from morning attendance and evening plucking muster through washing, the three processing routes and packing, with every packed bag traceable back to its harvest dates and divisions.

**Open the demo:** https://smkrmuthu.github.io/estate-demo/

Every estate, division, worker and figure in this demo is invented. Anything you enter is kept only in your own browser; use **Reset** to start again.

## What to try

1. **Supervisor**: mark attendance, record a few muster weights on the keypad, switch to Offline and sync later, then submit.
2. **Portal → Washing**: turn the submitted muster into a washing lot.
3. **Portal → Processing**: start a batch, complete each stage, and approve it at the quality check.
4. **Portal → Packing**: pack `B-HSE-2026-0002`, which mixes two harvest dates, into bags with QR labels.
5. **Portal → Trace a bag**: look up `HILLAA13` to see a bag holding coffee from two harvest dates.

The whole demo is the single file `index.html`. It needs an internet connection only for fonts and the QR code library.
