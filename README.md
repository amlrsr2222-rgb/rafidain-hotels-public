# Rafidain Digital Hotels — public marketing site

Static Arabic landing site for a hotel-management SaaS project. This repository **must not** contain the booking database, hotel records, guest information, auth secrets, or the private local server.

## Status / truthful scope
- Public site advertises features verified in the local engine (room inventory, staff-confirmed bookings, overlap checks, report export, hotel isolation).
- The online website does **not** process hotel reservations, provide account login, collect leads, process payments, or link to the private local system.
- The public sales contact channel will be added **only after** a separate authorized business contact is available.
- Render Static Site deployment is for the marketing frontend alone. Backend with protected hotel data will require durable production DB, legal privacy notices and secure hosting.
- There are no fake hotel names, references, testimonials, or actual customers.

Render settings: branch main, build command `echo static-ready`, publish directory `docs`.
