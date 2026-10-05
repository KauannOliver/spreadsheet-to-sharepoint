# SharePoint List Form Automation

A local desktop workflow that reads rows from Excel and enters mapped values into SharePoint List forms through browser automation.

> Public source edition. Configure credentials locally and use empty or synthetic inputs. Company and institution names identify the original integration context; this repository does not claim affiliation or endorsement.

## Configuration

Copy `.env.example` to `.env` and set the authorized `SHAREPOINT_LIST_URL`; keep account data in the local browser session.

## Stack

Python, Tkinter, Pandas, and Selenium.

## Run locally

Requires Python, a graphical desktop session, Chrome, and the dependencies in `requirements.txt`. Run `pip install -r requirements.txt`, then `python main.py`. The user must authenticate in the authorized browser session.

The form fields and SharePoint URL are environment-specific and should be replaced with placeholders before any public release.
