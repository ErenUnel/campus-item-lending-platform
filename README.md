# Campus Item Lending Platform

BBF 302E Database Systems – Term Project (Fall 2026) · Team **AstonVilla**

A Flask web application where university students lend and borrow items (calculators, textbooks, lab equipment, sports gear) free of charge. Owners list items with availability dates, borrowers send requests, and accepted requests become loans whose pickup and return are tracked. Users can review each other after a loan and receive in-app notifications; admins manage categories, accounts and overdue loans.

## Tech stack
- Python / Flask with Jinja templates
- PostgreSQL (raw, parameterized SQL — no ORM)
- psycopg driver

## Team
| Member | Student ID | Responsibilities | Tables |
|---|---|---|---|
| Cemşah Aksünger (Team Leader) | 150230067 | Loans, returns, consistency | loan, loan_event |
| Eren Ünel | 150230083 | Accounts, authentication | account, contact_preference |
| Mert Alma | 150230041 | Catalog, categories | category, item |
| İsmail Köylü | 150230306 | Availability, requests | availability_period, borrow_request |
| Muhammed Ahmet Sadi Kerimi | 150230319 | Reviews, notifications | review, notification |

## Project status
- [x] Milestone 1 – Project proposal
- [x] Milestone 2 – ER diagram and data model design
- [ ] Milestone 3 – Database implementation and Flask app
- [ ] Milestone 4 – Final demo and documentation

Setup and run instructions will be added in Milestone 3.
