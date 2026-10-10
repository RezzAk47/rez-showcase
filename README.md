# ReZ POS: showcase

ReZ is a point-of-sale system for table-service restaurants. It runs in a web browser on tablets and a kitchen screen. It is built for small independent restaurants that want seat-by-seat ordering without buying expensive hardware.

**The source code is private.** This repo has screenshots and text only. For a demo, email rzk.karimi@gmail.com.

All screenshots show demo data: an invented Canadian pub menu, made-up dishes and prices, and made-up staff names. No real restaurant, guest or payment is shown. ReZ is a demo build: it does not take real card payments yet.

## Who it is for

Independent restaurants and pubs with a few tablets and one kitchen screen. The first market is Vancouver.

## What it does

- A floor plan you tap. Pub, cafe, banquet and grid layouts, with sections (bar, booths, dining, patio). Managers can drag tables to edit the floor.
- Seat-by-seat ordering. Share a dish between seats and the price divides to the cent.
- Merge tables for big parties and split them apart again.
- Dish changes: leave out ingredients, add extras, write a note. Allergy alerts appear as a red banner on the kitchen ticket. Allergens are set by the restaurant; the kitchen still confirms cross-contact risk.
- Hold and fire dishes. A kitchen screen with Fire, Ready and Bump buttons updates the tablets in about a second.
- Split checks by seat or evenly (2 to 9 ways). Payment sheet with cash, debit and credit, tips, automatic gratuity and 5-cent cash rounding.
- Staff sign-in with 4-digit codes, tablet pairing, manager and server roles checked by the server.
- A menu editor, tip-out rules, a time clock, shift reports and printable receipts.
- Works offline on a tablet and sends orders when the server is back.
- Plans (from the project website): ReZ Free for up to 3 tablets and 1 kitchen screen, and ReZ Premium at $69 per month CAD with everything included. Prices are drafts and may change.

## What it does not do yet

- No real card payments. Stripe is only wired in test mode.
- Not tested on real card readers or receipt printers.
- Not used in a live restaurant.
- An AI order assistant is not built.

## Screenshots

| | |
|---|---|
| ![Floor plan](media/floor-plan.png) | ![Table with a whole order](media/table-whole-order.png) |
| Floor plan with table status colours | One table in focus with its whole order |
| ![Split checks](media/split-checks.png) | ![Dish changes and allergies](media/modify-dish-allergies.png) |
| One check per seat | Remove, add, allergy and kitchen note |
| ![Kitchen screen](media/kitchen-screen.png) | ![Payment sheet](media/payment-sheet.png) |
| Kitchen screen with an allergy alert | Payment sheet (demo, no card is charged) |
| ![Pub floor](media/pub-floor-sections.png) | ![Floor layouts](media/floor-layouts.png) |
| Pub floor with sections | Choosing a floor layout in edit mode |
| ![Menu editor](media/menu-editor.png) | ![Shift report](media/shift-report.png) |
| Menu editor | Shift report with a daily briefing |

Short video clips are planned: see [media/VIDEO-PLAN.md](media/VIDEO-PLAN.md).

## Contact

Razi Karimi, Vancouver. rzk.karimi@gmail.com

## Licence

Text and images here are all rights reserved. See [LICENSE](LICENSE). The ReZ source code is not part of this repo.
