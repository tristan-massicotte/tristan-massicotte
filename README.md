<div align="center">
  <img src="assets/banner.svg" alt="Tristan Massicotte, Industrial Engineering, University of Toronto" width="100%">
</div>

<p align="center">
  <a href="https://linkedin.com/in/tristan-massicotte"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:tristanmassicotte@me.com"><img src="https://img.shields.io/badge/Email-C71610?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"></a>
  <a href="https://tristan-massicotte.github.io/engineering-internship-highlights"><img src="https://img.shields.io/badge/Internship_highlights-1F5FBF?style=for-the-badge&logo=githubpages&logoColor=white" alt="Internship highlights"></a>
  <img src="https://img.shields.io/badge/Toronto_&_Québec-1F2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Toronto and Québec">
</p>

---

## About me in a nutshell

**Optimize, optimize, optimize.** Whether it's the way I cook my meals or the way a factory runs, I'm addicted to optimizing.

- **Industrial Engineering at the University of Toronto** (class of 2029), French and English.
- **Manufacturing Software Developer at Technimount System,** a manufacturer in Québec, after a summer there as Continuous Improvement Intern. The MRP system I built cut order processing **from 5 days to half a day**.

<br>

# &nbsp;🏭&nbsp; Built at Technimount System

I design the logic and rules; I build the apps with AI coding tools. The code belongs to Technimount, so three of these tools stay internal. Two have public demos rebuilt on fictional data.

### MRP system &nbsp;<sub>purchasing and requirements planning · internal</sub>

<img src="https://img.shields.io/badge/MRP-374151?style=flat-square"> <img src="https://img.shields.io/badge/Zoho_Inventory-E42527?style=flat-square&logo=zoho&logoColor=white">

- **What it is.** The buyers' daily answer to *"what must I order today so it arrives in time?"* Open sales orders are netted against stock, exploded through the bills of materials and filtered by each part's lead time. A second track reorders assemblies that fall below their reorder point.
- **What changed.** Order processing went **from 5 days to half a day (−90%)**, from quote to purchase order. In fall 2026 I rebuilt it as a web app, and the report went **from about 8.5 minutes to under a second**.
- **Skills shown.** MRP logic (BOM explosion, lead-time netting, reorder points), turning a purchasing process into a tool buyers trust.

<br>

### [Sales dashboard](https://tristan-massicotte.github.io/sales-dashboard/) &nbsp;<sub>3 companies, 2 currencies</sub> &nbsp;[![demo](https://img.shields.io/badge/try_the_demo-2EA44F?style=flat-square&logo=githubpages&logoColor=white)](https://tristan-massicotte.github.io/sales-dashboard/)

 <img src="https://img.shields.io/badge/Zoho-E42527?style=flat-square&logo=zoho&logoColor=white"> <img src="https://img.shields.io/badge/Excel_&_PowerPoint_export-217346?style=flat-square">

- **What it is.** Sales by salesperson for three companies billing in CAD and USD, with drill-down to every invoice, a map of sales by region, a KPI page (credit notes, unpaid invoices by age), and one-click Excel and PowerPoint exports for the leadership meeting.
- **What changed.** About 1,800 invoices, **matched to Zoho to the cent**. In daily use.
- **Skills shown.** Writing down the calculation rules (credit notes, taxes, CAD and USD kept apart) and checking them against the books.

<div align="center">
  <a href="https://tristan-massicotte.github.io/sales-dashboard/"><img src="assets/sales-dashboard.png" alt="Sales dashboard demo: map of sales by region" width="760"></a>
  <br><sub>Sales dashboard demo, map page (fictional data).</sub>
</div>

<br>

### [Manufacturing dashboard](https://tristan-massicotte.github.io/manufacturing-dashboard/) &nbsp;<sub>for the production director and CEO</sub> &nbsp;[![demo](https://img.shields.io/badge/try_the_demo-2EA44F?style=flat-square&logo=githubpages&logoColor=white)](https://tristan-massicotte.github.io/manufacturing-dashboard/)

<img src="https://img.shields.io/badge/Inventory_planning-374151?style=flat-square"> <img src="https://img.shields.io/badge/Zoho_Inventory-E42527?style=flat-square&logo=zoho&logoColor=white">

- **What it is.** One screen for the plant: inventory value and age at FIFO cost, open sales and purchase orders, purchases by supplier, stock cover for the best sellers, and on-time shipping against an 80% target.
- **The rules that mattered.** Parts used in assemblies are traced through FIFO lots back to the supplier they actually came from. On-time is judged per order line, so an order with 3 of 4 lines on time counts as 0.75.
- **Skills shown.** Inventory metrics (age, dormant stock, turns, days on hand), on-time delivery, supplier analysis.

<div align="center">
  <a href="https://tristan-massicotte.github.io/manufacturing-dashboard/"><img src="assets/manufacturing-dashboard.png" alt="Manufacturing dashboard demo: inventory value and supplier breakdown" width="760"></a>
  <br><sub>Manufacturing dashboard demo (fictional data).</sub>
</div>

<br>

### Quote tool &nbsp;<sub>supplier quotes for manufactured parts · internal</sub>

<img src="https://img.shields.io/badge/Purchasing-374151?style=flat-square"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">

- **What it is.** One project is one request-for-quote cycle. The tool builds a **ZIP of every part's drawings automatically** and **emails it to each supplier** with the quote form, no manual packaging.
- **The part I'm proudest of.** When a supplier sends back their Excel quote, I reverse-engineer their pricing into a **price curve by quantity**, so we can price an assembly near-exactly for any order quantity, not just the 5 tiers they quoted, and compare it against our target cost.
- **Where it is.** Deployed and in use. It replaced an Excel workbook.
- **Skills shown.** Sourcing and cost modelling, automating the repetitive half of purchasing.

<br>

### Clear-to-build dashboard &nbsp;<sub>every open order, 4 companies · internal</sub>

<img src="https://img.shields.io/badge/Clear--to--build-374151?style=flat-square"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/Zoho_Inventory-E42527?style=flat-square&logo=zoho&logoColor=white">

- **What it is.** Each open customer order is sorted into *ready to ship*, *to assemble* (parts in stock, multi-level BOMs), *waiting on a PO* (with the PO), or *to order* (which part is missing, and how many). The oldest orders get stock and incoming POs first.
- **What changed.** **6 hours a week saved** (3 hours each for 2 people).
- **Skills shown.** Clear-to-build analysis, finding the bottleneck part, allocating scarce stock by priority.

<br>

# &nbsp;🛍️&nbsp; Soma

### [Soma](https://apps.shopify.com/soma) &nbsp;<sub>founder and developer · launched May 2026</sub> &nbsp;[![website](https://img.shields.io/badge/website-1F2937?style=flat-square&logo=shopify&logoColor=white)](https://somastudios.fashion)

<img src="https://img.shields.io/badge/Shopify_app-7AB55C?style=flat-square&logo=shopify&logoColor=white"> <img src="https://img.shields.io/badge/AI_virtual_try--on-8A2BE2?style=flat-square">

- **What it is.** A Shopify app that adds AI virtual try-on to a store's product pages. The merchant drops a "Try it now" button onto the product page from the theme editor, and shoppers see the clothes on themselves without leaving the site.
- **The piece I'm proudest of.** A Web Pixel that attributes purchases back to a try-on, which let me price the product as a share of attributed revenue rather than a subscription.
- **Where it is.** Used by La Boutique du Lac. I was interviewed on FM93 about it.

<br>

<sub>Technimount code stays with Technimount. The demos are separate rebuilds on fictional data, published with permission.</sub>
