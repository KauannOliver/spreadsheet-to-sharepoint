# Spreadsheet to SharePoint

A local desktop workflow that reads rows from Excel and enters mapped values into SharePoint List forms through browser automation.


## Configuration

Copy `.env.example` to `.env` and set the authorized `SHAREPOINT_LIST_URL`; keep account data in the local browser session.

## Stack

Python, Tkinter, Pandas, and Selenium.

## Run locally

Requires Python, a graphical desktop session, Chrome, and the dependencies in `requirements.txt`. Run `pip install -r requirements.txt`, then `python main.py`. The user must authenticate in the authorized browser session.

The form fields and SharePoint URL are environment-specific and should be replaced with placeholders before any public release.


## Snapshot review

Setup and capabilities are based on the included code. External services and operating-system-specific integrations were not exercised during this publication review. Use synthetic data in a separate local environment.

Git-triggered Vercel deployment is disabled in the included web configurations. This update publishes source and documentation only.

## License

No new distribution license is granted for this corporate source edition. Public visibility does not grant reuse rights; obtain permission from the relevant rights holder. Existing third-party notices remain applicable.

## Verification record

See [snapshot checks and remaining limitations](docs/VERIFICATION.md).
