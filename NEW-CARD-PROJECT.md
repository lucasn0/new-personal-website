  For the CRM/ERP card:

  Title

  > MARITIME CRM/ERP

  Status

  > client work · pre-production

  Ownership line

  > three-person team · architecture, full-stack & AWS

  Description

  > A custom operational platform for a South American maritime inspection company, replacing fragmented Zoho CRM, spreadsheet, legacy-software, and WhatsApp workflows. Being prepared for
  > 50–100 internal users supporting 24/7 operations across Argentina, Brazil, Chile, and Uruguay.

  Highlights

  - Operational workflows for client orders, cargo inspections, vessels, inventory, invoicing, reporting, statistics, and internal alerts.
  - Next.js frontend, FastAPI backend, and PostgreSQL database.
  - Self-managed Linux deployment on AWS EC2 with RDS and S3.
  - Health-checked deployment workflow that validates releases before switching application processes.

  Stack chips

  > Next.js / FastAPI / PostgreSQL / AWS EC2 / RDS + S3 / Linux

  Don’t add a fake product screenshot. Use a restrained architecture diagram or abstract module map labeled something like:

  OPERATIONS
  ├── inspections
  ├── vessels & cargo
  ├── orders & invoicing
  ├── inventory
  ├── reports
  └── internal alerts

  Next.js → FastAPI → PostgreSQL
                   ↘ S3

  Instead of a button, use a non-interactive badge:

  > confidential client work


For Pact.ar:

  Status

  > independent product · publicly deployed

  Ownership line

  > solo project · product design, full-stack & cloud infrastructure

  Description

  > A digital-contract SaaS for Argentine freelancers and small businesses. I designed and shipped the complete product, including legally valid electronic signatures under Law 25.506,
  > email-based verification, Mercado Pago subscriptions, and self-managed Oracle Cloud infrastructure.

  Highlights

  - Designed and built the product end-to-end.
  - Implemented the electronic-signature and email-verification workflow.
  - Integrated Mercado Pago subscription billing and payment-state handling.
  - Provisioned, secured, and operated its Oracle Cloud deployment.

  Stack chips

  > Next.js / React / Node.js / Express / PostgreSQL / Oracle Cloud / GitHub Actions

  Keep the existing visit pact.ar ↗ button.

  Prompt for Claude

  Update the homepage hero and Projects view without redesigning the visual system.

  Keep the hero’s existing max-width of 560px, font size of 16px, and line-height of 1.7. Replace its text with:

  “software engineer across full-stack development, cloud infrastructure, and systems. computer science @ uba. currently building a custom crm/erp for 24/7 maritime inspection operations;
  creator of pact.ar. from argentina, usually with a terminal open and a record spinning.”

  Highlight only “crm/erp” and “pact.ar” using the existing accent color. Make “crm/erp” navigate to the Projects view and “pact.ar” open https://pact.ar/ externally.

  Change the Projects introduction to:

  “commercial systems and products I’ve designed, built, and shipped end-to-end.”

  Show two project cards using the existing visual language. Put MARITIME CRM/ERP first and PACT.AR second.

  For MARITIME CRM/ERP:
  Status: “client work · pre-production”
  Ownership: “three-person team · architecture, full-stack & AWS”
  Description: “A custom operational platform for a South American maritime inspection company, replacing fragmented Zoho CRM, spreadsheet, legacy-software, and WhatsApp workflows. Being
  prepared for 50–100 internal users supporting 24/7 operations across Argentina, Brazil, Chile, and Uruguay.”
  Highlights:
  - Operational workflows for client orders, cargo inspections, vessels, inventory, invoicing, reporting, statistics, and internal alerts.
  - Next.js frontend, FastAPI backend, and PostgreSQL database.
  - Self-managed Linux deployment on AWS EC2 with RDS and S3.
  - Health-checked deployment workflow that validates releases before switching application processes.
  Stack: Next.js, FastAPI, PostgreSQL, AWS EC2, RDS + S3, Linux.
  Do not fabricate a product screenshot. Create a restrained system/module diagram using the site’s existing typography and colors. Replace the external-action button with a non-interactive
  “confidential client work” badge.

  For PACT.AR:
  Status: “independent product · publicly deployed”
  Ownership: “solo project · product design, full-stack & cloud infrastructure”
  Description: “A digital-contract SaaS for Argentine freelancers and small businesses. I designed and shipped the complete product, including legally valid electronic signatures under Law
  25.506, email-based verification, Mercado Pago subscriptions, and self-managed Oracle Cloud infrastructure.”
  Keep its screenshot and visit button. Preserve the current responsive behavior and avoid adding new animations or decorative effects.

