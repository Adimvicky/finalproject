# BUS298 Final Project

## Goals

- Create forms on the frontend that can be POSTed to a spreadsheet somewhere
- Every time a new form is successfully posted, send an email alert
- Optionally, support mutliple forms that can be spawned by user choice

## Services Used

- Bootstrap for frontend form generation
- **[Webtask](https://webtask.io/)** for handling connection between the frontend form and the new row in spreadsheet
- **[Airtable](https://airtable.com/)** for storing data as spreadsheet
- **[IFTTT](https://ifttt.com/airtable)** for automating emails sent when spreadsheet is mutated
