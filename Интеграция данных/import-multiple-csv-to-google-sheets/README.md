

This workflow automates the process of importing and organizing subscriber data from multiple CSV files into a Google Sheets spreadsheet, ensuring data integrity and providing a centralized view of the subscriber base.

Example: A marketing team managing a newsletter subscription list can use this workflow to automatically import and consolidate subscriber data from various sources (e.g., website signups, event registrations) into a single Google Sheets spreadsheet. This allows them to easily track and analyze their subscriber base, identify active subscribers, and keep the data up-to-date.

## What You Can Do
- Reads multiple CSV files from a designated directory and processes them in batches
- Removes duplicate subscriber records based on the "user_name" field
- Filters the data to include only active subscribers (those with "subscribed" set to "TRUE")
- Sorts the subscriber data by the "date_subscribed" field
- Appends or updates the subscriber data in a Google Sheets spreadsheet

