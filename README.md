# FinTech Accounting Management Application

FinTrack is a comprehensive accounting management app designed to simplify personal or small business finances by offering an intuitive interface and powerful analytical tools. Users can track income, expenses, and manage financial accounts efficiently, helping them make informed financial decisions.

[LINK PRODUCT](https://fintech-saas.vercel.app/)

![Demo](https://github.com/tuanna-kite/finance-saas/blob/main/demo/1.png?raw=true)

## Key Features

- **User Registration and Authentication:** Secure sign-up, login, and Google authentication for quick and safe access.
- **Dashboard Analytics:**
  - **Overview:** View summaries of Income, Expenses, and Remaining Balance for a selected period, with the default view set to the most recent month.
  - **Visual Analytics:**
    - Area Chart: Displays daily income and expenses over the selected date range. Users can toggle between Area, Line, or Bar Chart for preferred visualization.
    - Pie Chart: Offers a breakdown of categories by percentage, with options to switch to Radar or Radial Chart for detailed insights.
    - Interactive Charts: Hover over any chart for real-time data insights on specific values.
- **Account and Category Management:**
  - Full control over financial accounts and transaction categories, allowing users to add, edit, or delete entries as needed.
- **Transaction Management and Filtering:**
  - Easily manage and view transactions, with filters available by date range, account, or transaction type for targeted insights.
  - Payee Search: Quickly locate transactions associated with a specific payee for detailed analysis.
  - CSV Import: Import CSV files and map columns to relevant fields within the system, enabling bulk transaction uploads and seamless data integration.

## Technology Stack

- Next.js with Hono.js and Shadcn UI:
  - Next.js, paired with Hono.js, serves as the foundation for a fast, serverless backend that efficiently handles requests and responses. Shadcn UI enhances the front-end with accessible, responsive components for a polished user experience.
- PostgreSQL:
  - This relational database system ensures secure and structured data storage, enabling complex queries for transaction data, income, expenses, and account information.
- Drizzle ORM:
  - Simplifies database interactions with type-safe querying and helps efficiently map database tables to application objects, streamlining CRUD operations on transactions, accounts, and categories.
- Vercel:
  - Provides reliable, scalable deployment for Next.js applications, ensuring optimal performance and fast load times across various devices.
