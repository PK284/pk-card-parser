# PK Card Parser

PK Card Parser is a personal, local-only web app that I built for my own use. It reads my own Gmail inbox (read-only) to find bank and credit card transaction emails, extracts the transaction details, and shows them in a spending dashboard that runs on my own computer.

## What it does

- Connects to my own Gmail account using Google OAuth with the read-only `gmail.readonly` scope.
- Finds transaction alert emails and parses the amount, merchant, date and card.
- Stores the parsed data in a local database and shows it in a dashboard at `localhost`.

## Privacy

All processing and storage happens locally on my computer. No data is sent to any third party. See the full [Privacy Policy](PRIVACY.md).

## Who it is for

This app is a personal project used only by its author, Piyush Kumar. It is not a public service.

## Contact

kumarpiyush2841@gmail.com
