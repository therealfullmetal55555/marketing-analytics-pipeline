# Fares Korea — End-to-End Analytics Pipeline

Dashboard that traces revenue back to its source — from AmoCRM leads and ad spend through to actual sales — so spend and outcome sit on one screen instead of three separate exports.

This repo is a self-contained visual walkthrough of the dashboard (`index.html`). The production version reads live from the client's AmoCRM and ad accounts, so it isn't public — this demo shows the same structure and flow without any of that.

## What it does

- Pulls together AmoCRM, ad platforms and sales data that used to live in separate exports
- Traces the funnel from click to lead to revenue, so a spend number and a result number sit next to each other
- Built to answer one question fast: which channel is actually paying for itself

## Why it exists

Built for an e-commerce brand selling on Wildberries and Ozon. Before this, checking whether an ad channel was profitable meant pulling CRM data, ad spend, and sales figures separately and reconciling them by hand.

## Stack

Frontend dashboard in vanilla HTML/CSS/JS. Production version syncs live data from AmoCRM's API; 1C sales data is reconciled monthly.
