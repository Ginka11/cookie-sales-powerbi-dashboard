# Cookie Sales Analytics Dashboard | Power BI

A Power BI portfolio practice project built from supplied sample Excel workbooks. The report combines sales, customers, products, inventory, and feedback into desktop and mobile views for business users.

> The workbooks contain clearly synthetic records, including `example.com` customer emails. All values below describe the sample dataset, not a real company.

## Project Scope

- Imported and transformed three Excel workbooks with Power Query.
- Created relationships between orders, customers, products, inventory, and feedback.
- Built three report pages: Cookie Bills Sales Dashboard, Sales Report, and Management Report.
- Added KPI cards, filters, drill-down, cross-filtering, and page navigation.
- Created separate desktop and mobile layouts.

## Verified Report Snapshot

The committed screenshots visibly report:

- **6M** total revenue; the source report does not specify a currency.
- **4.20** average customer rating.
- A plotted daily quantity peak of **120** on September 8 in the sample period.
- Coffee stock count of **4** compared with Pastry stock count of **1**.
- Reorder count of **4** for Bean World and **1** for PastryPro.

## Dashboard Evidence

### Executive sales overview

![Cookie sales executive dashboard](screenshots/ninth.png)

### Sales detail

![Cookie sales detail report](screenshots/eighth.png)

### Management and inventory view

![Cookie sales management report](screenshots/seventh.png)

<details>
<summary>Mobile-layout evidence</summary>

These screenshots document the mobile work completed in Power BI. The layout remains a prototype and would benefit from a further typography and spacing pass.

#### Dashboard

![Cookie sales mobile dashboard top](screenshots/first.png)

![Cookie sales mobile dashboard detail](screenshots/second.png)

#### Sales report

![Cookie sales mobile report top](screenshots/third.png)

![Cookie sales mobile report detail](screenshots/fourth.png)

#### Management report

![Cookie sales mobile management top](screenshots/fifth.png)

![Cookie sales mobile management detail](screenshots/sixth.png)

</details>

## Repository Structure

```text
cookie-sales-powerbi-dashboard/
â”œâ”€â”€ Projecta.pbix
â”œâ”€â”€ Datasets/
â”‚   â”œâ”€â”€ data.xlsx
â”‚   â”œâ”€â”€ practice.xlsx
â”‚   â””â”€â”€ final.xlsx
â”œâ”€â”€ screenshots/
â”‚   â”œâ”€â”€ first.png
â”‚   â”œâ”€â”€ second.png
â”‚   â”œâ”€â”€ third.png
â”‚   â”œâ”€â”€ fourth.png
â”‚   â”œâ”€â”€ fifth.png
â”‚   â”œâ”€â”€ sixth.png
â”‚   â”œâ”€â”€ seventh.png
â”‚   â”œâ”€â”€ eighth.png
â”‚   â””â”€â”€ ninth.png
â””â”€â”€ README.md
```

## Skills Demonstrated

- Power Query data preparation
- Relational data modeling
- KPI and dashboard design
- Interactive filtering and drill-down
- Desktop and mobile report development
- Business reporting with Power BI

## Limitations and Next Improvements

- Document the workbook provenance and usage rights.
- Rename generic source files and the `.pbix` artifact by business purpose.
- Define currency, reporting periods, and KPI formulas explicitly.
- Add a model diagram, key Power Query steps, and representative DAX measures.
- Refine mobile spacing and replace default `Sum of ...` visual titles.

