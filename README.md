# Orchestra Agency Assessment - FoodMart Implementation

This repository contains the technical tracking architecture developed for the FoodMart e-commerce project.

## 🚀 Core Features

* **Privacy-First Tracking:** Implemented client-side SHA-256 hashing for all user identifiers (Email/User ID) to ensure 100% PII compliance and GDPR/CCPA alignment.
* **Data Integrity & Bot Defense:** Custom "Honeypot" logic deployed via GTM to identify and block non-human event inflation at the source.
* **Performance-Optimized Funnel:** Utilized **Intersection Observers** for `view_item_list` events to ensure accurate impressions and reduce browser main-thread bloat.
* **Agile Event Strategy:** Balanced implementation using both a robust Data Layer for e-commerce and DOM-scraping for search tracking to demonstrate technical versatility.
