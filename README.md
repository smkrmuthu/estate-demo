# CEMMS Estate Demo

A public, clickable demo of CEMMS (Coffee Estate Maintenance and Management System). It shows the daily flow on a coffee estate, from morning attendance and evening plucking muster through washing, the three processing routes and packing, with every packed bag traceable back to its harvest dates and divisions.

**Open the demo:** https://smkrmuthu.github.io/estate-demo/

The two estates are Glazebrooke and Byson Valley; every division, worker and figure in this demo is invented. Anything you enter is kept only in your own browser; use **Reset** to start again.

## What to try

1. **Supervisor**: mark attendance, record a few muster weights on the keypad, switch to Offline and sync later, then submit.
2. **Portal → Washing**: turn the submitted muster into a washing lot.
3. **Portal → Processing**: start a batch, complete each stage, and approve it at the quality check.
4. **Portal → Packing**: pack `B-HSE-2026-0002`, which mixes two harvest dates, into bags with QR labels.
5. **Portal → Trace a bag**: look up `HILLAA13` to see a bag holding coffee from two harvest dates.
6. **Portal → Reports**: copy the day's summary for WhatsApp, compare outturn (kilograms of cherry per kilogram of dried coffee) by route, variety and field, and see kilograms per plucker with a pay preview.

Other things to try: mark a worker Off day or Holiday, reopen an approved day with a reason, record the number of bags and a remark on a weigh-in, enter the weight at washing (a difference over 1% needs a reason), pick drying trays by hand, log turning, covering and rain, put a batch on hold or split it, and weigh each packed bag.

The whole demo is the single file `index.html`. It needs an internet connection only for fonts and the QR code library.
