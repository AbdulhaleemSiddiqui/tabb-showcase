# Tabb: QR Table Ordering for Restaurants

**Live:** [tabb-web.vercel.app](https://tabb-web.vercel.app/)

Tabb is a restaurant ordering platform (SaaS). Guests scan a QR code on their table and order from their phone's browser, with no app to download and no account to create. Orders go straight to the kitchen, and staff and owners manage the whole operation from one system.

> The source code is private. This repository is a product showcase with an overview, features and architecture notes.

<!-- Add screenshots here once saved in a /screenshots folder:
![Guest ordering](screenshots/guest-ordering.png)
![Kitchen display](screenshots/kitchen-display.png)
![Admin dashboard](screenshots/admin-dashboard.png)
-->

## The problem

Restaurants lose time and orders to paper menus, waiting for a waiter and manual hand-offs between the floor and the kitchen. Tabb moves ordering to the guest's phone and keeps the guest, the kitchen and the staff in sync in real time.

## How it works

```text
Guest scans the table QR code
        ↓
Chooses dine-in or takeaway, browses the menu, adds notes, places the order
        ↓
Kitchen Display System receives the ticket instantly
        ↓
Kitchen moves it through preparation stages; the guest tracks status live
        ↓
Waiter is alerted when it is ready to serve
        ↓
Guest pays at the counter as usual
```

## Features

**For guests**
- Order from a table QR code with no app and no account
- Dine-in or takeaway, cooking notes, live order status
- Digital menu with photos, descriptions, deals and combo meals, in multiple languages

**For the kitchen**
- Kitchen Display System (KDS) with tickets that move through preparation stages

**For waiters**
- Table map with live status
- Ready-to-serve alerts
- Per-guest ordering and bill splitting

**For owners and managers**
- Admin dashboard: revenue, order counts, busy-hour analysis and top-selling dishes
- Role-based access for managers and staff
- Menu management with item availability toggles
- Printable branded table QR posters and standees

## Plans

Basic, Medium and Custom plans for single-location cafes, growing restaurant groups and multi-kitchen venues such as food courts. See the live site for current details.

## Tech stack

| Area | Technology |
| --- | --- |
| Front end | React.js |
| Database | PostgreSQL |
| Hosting | Vercel |
| Real-time | Live order sync between guests, kitchen and staff |

## What I built

I designed and built Tabb end to end: the guest ordering experience, the kitchen display, waiter tools, the admin dashboard, role-based access and the data model behind them.

## Contact

Built by **Abdul Haleem Siddiqui**, Senior Software Engineer.
[LinkedIn](https://www.linkedin.com/in/abdulhaleem-dev/) · [GitHub](https://github.com/AbdulhaleemSiddiqui)
