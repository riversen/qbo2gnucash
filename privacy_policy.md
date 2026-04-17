# Privacy Policy — qbo2gnucash

**Last updated: April 17, 2026**

qbo2gnucash is a personal data-migration tool. This privacy policy
describes how it handles information.

## What data the tool accesses

When authorized, the tool reads accounting data from QuickBooks Online
via Intuit's official API, including:

- Chart of accounts, customers, vendors, employees, items
- Transactions (journal entries, invoices, bills, payments, deposits, etc.)
- Attachments and file links
- General ledger reports

## What the tool does with that data

- Writes it to files on the local machine where the tool is run.
- Converts it into a GnuCash SQLite file on the same local machine.
- Does not transmit data to any third party.
- Does not send data to the tool's author or to any remote server.
- Does not use the data for analytics, advertising, or any secondary purpose.

## Data storage

All data stays on the local machine in user-controlled directories.
OAuth tokens are stored in a local `.env` file. The user is responsible
for the security of their own machine and files.

## Data sharing

None. The tool does not share data.

## Data retention

The user controls retention. Delete the output directories and `.env`
file to remove all extracted data.

## Contact

Report issues or questions via the project's issue tracker.
