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

Sign in first. Every sample password is `welcome`: use `owner` for Admin, or one of the supervisor usernames shown on the sign-in screen. A Supervisor sees only the dashboard, attendance, plucking and the daily log; Admin sees everything, including Users. In the daily log, add readings for either estate (temperature in °C, rain in mm, fermentation room temperature) with the time you took each one.

Other things to try: start a Route B batch with a mix of fermentation flavours (the shares must add up to 100%), set a different target time for one batch, change the flavours and their times in Process settings, choose a rest in place of about 2 days after pulping and watch its timer, mark a worker Off day or Holiday, reopen an approved day with a reason, record the number of bags and a remark on a weigh-in, enter the weight at washing (a difference over 1% needs a reason), pick drying trays by hand, log turning, covering and rain, put a batch on hold or split it, and weigh each packed bag.

The whole demo is the single file `index.html`. It needs an internet connection only for fonts and the QR code library.
