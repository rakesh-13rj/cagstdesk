CA GST Desk — Starter Prototype

Open index.html in a modern browser. This is a local demo; no server or login is configured.
Current functions:
- Import generic CSV reports
- Add an offline sales invoice manually
- View basic sales register and totals
- Export working-data JSON and summary/register CSV
- Basic duplicate invoice/source warning

Important limitations:
- It is NOT production-ready and has no persistent database, user login, encryption, cloud backup, or audit trail.
- CSV column mapping is basic. Platform-specific report formats need real sample files and explicit mapping.
- It does not currently extract data from PDF/photo bills, import XLSX, calculate all GST scenarios, reconcile GSTR-2B, or create verified official GST Portal JSON.
- The JSON export is deliberately labelled DRAFT and must NOT be uploaded to the GST Portal.
- Validate tax treatment, GSTIN, place of supply, credit notes/returns, HSN, e-commerce tables, and totals with the current official GST Offline Tool before filing.

Official GSTR-1 guide:
https://tutorial.gst.gov.in/userguide/returns/GSTR_1.htm
