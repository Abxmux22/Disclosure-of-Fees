# Disclosure of Fees Calculator

A responsive real estate fee disclosure calculator with live general partner fee totals and a branded PDF report.

## Run locally

Run `python server.py`, then open `http://localhost:8000`.

## Calculations

- Acquisition fee, loan guarantee fee, and loan refinance fee are one-time fees.
- Total annual asset management fee = annual fee amount × years of project.
- Total fee to general partners = all one-time fees + total asset management fee.

Fee amount and project-term cells are editable inputs. The app is self-contained and does not require third-party packages or a database.
