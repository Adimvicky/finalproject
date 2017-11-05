# BUS298 Final Project

## Goals

- [Create forms on the frontend that can be POSTed to a spreadsheet somewhere](https://github.com/AndrewCarlile/finalproject/issues/1)
- [When form is posted, add to spreadsheet](https://github.com/AndrewCarlile/finalproject/issues/2)
- [Every time a new form is successfully posted, send an email alert](https://github.com/AndrewCarlile/finalproject/issues/3)
- [Optionally, support mutliple forms that can be spawned by user choice](https://github.com/AndrewCarlile/finalproject/issues/4)

## Services Used

- Bootstrap for frontend form generation
- **[Webtask](https://webtask.io/)** for handling connection between the frontend form and the new row in spreadsheet
- **[Airtable](https://airtable.com/)** for storing data as spreadsheet
- **[IFTTT](https://ifttt.com/airtable)** for automating emails sent when spreadsheet is mutated
