# Job Radar

A twice-daily feed of new product design roles (remote roles open to India, and Delhi NCR), ranked by fit.

Live page: https://subhranilmaity06.github.io/job-radar/

`data/` is rewritten by the scanner after each scan (07:30 and 19:30 IST): `data/index.json` lists recent scans and `data/scans/<run>.json` holds each scan's roles. `index.html` is a static page that reads them; Save, Applied and Hide marks stay in the visitor's own browser.
