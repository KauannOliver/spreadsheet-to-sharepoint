# SharePoint List Form Automation

A local desktop workflow that reads rows from Excel and enters mapped values into SharePoint List forms through browser automation.

> Private repository: the current automation targets a company-specific SharePoint environment. Use only authorized accounts and keep workbook data and browser sessions local.

## Configuration

Copy `.env.example` to `.env` and set the authorized `SHAREPOINT_LIST_URL`; keep account data in the local browser session.

## Stack

Python, Tkinter, Pandas, and Selenium.

## Run locally

Requires Python, a graphical desktop session, Chrome, and the dependencies in `requirements.txt`. Run `pip install -r requirements.txt`, then `python main.py`. The user must authenticate in the authorized browser session.

The form fields and SharePoint URL are environment-specific and should be replaced with placeholders before any public release.
