# Branch Control — Chemical Distribution Management

A Next.js 14 + React + TypeScript starter admin portal for a small chemical distributor branch.

## Included modules
- Branch overview dashboard
- Sales register
- Customer master
- Enquiry and order pipeline
- Inventory and reorder alerts
- Collections register
- Dispatch status tracker
- Team tasks for Branch Manager + two employees
- Basic MIS snapshot and CSV exports

## Run locally
1. Install Node.js 18.17+ (Node 20 LTS recommended).
2. Extract this project.
3. Open a terminal in the project folder.
4. Run:

   ```bash
   npm install
   npm run dev
   ```

5. Open http://localhost:3000

## Important setup notes
- The sample data is illustrative only. Replace it with actual distributor data.
- Data is stored in the current browser using localStorage. It is not shared between users or computers.
- This starter has no login, server database, role-based permissions, cloud backup, audit log, GST/accounting integration, ERP integration or multi-user sync.
- Do not enter confidential customer, pricing, financial or chemical safety data into this demo until authentication, access controls, backups and hosting security are implemented.
- Product names, prices, stock levels, customers and dates are placeholders, not Growel's official product catalogue or records.
- Verify all chemical handling, SDS, batch, expiry/retest, transport and regulatory requirements against the actual product documentation and company procedures.

## Recommended production architecture
- Next.js App Router + TypeScript frontend
- PostgreSQL database (e.g. managed Postgres)
- Auth.js / enterprise identity with role-based access
- Server-side validation and audit logs
- Daily automated database backups
- Secure document storage for invoices, SDS and delivery proofs
- Approval workflow for discounts, credit limits, stock adjustments and write-offs
- Separate roles: Branch Manager, Sales, Operations/Accounts, Owner/Admin

## Suggested next development phase
1. Confirm exact business workflow and approval hierarchy.
2. Add secure login and user roles.
3. Connect PostgreSQL and migrate all records.
4. Add customer ledger, receivables ageing, credit-limit checks and gross-margin reports.
5. Add purchase/inward stock, batch/lot tracking, SDS attachments and stock reconciliation.
6. Add PDF invoice/dispatch documents and scheduled MIS reports.
