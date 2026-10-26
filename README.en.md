# MİHENK

**A local workspace for financial research and portfolio tracking.**

[Türkçe](README.md)

MİHENK is an actively developed project that brings historical prices, technical indicators, financial statements, news and personal research records into one workspace. It emphasizes visible data sources, timestamps and missing-data handling.

This repository is a portfolio presentation. Application source code, executable packages, credentials and personal records are not distributed. There is no public application or demo endpoint.

## Implemented capabilities

- Daily historical charts over 30/90/180/365 calendar days for supported symbols, with candlestick/line views, available volume, SMA 20/50 and RSI 14.
- Comparisons aligned to overlapping observation dates.
- Financial statement views with reporting periods and source references for supported US companies and BIST symbols.
- Turkish news headline translation while retaining original headlines, publication times and source links.
- Watchlists, research notes, a portfolio and transaction journal, and backup import/export.
- Current portfolio valuation in TRY/USD/EUR using supported exchange-rate references, with partial totals when inputs are missing.
- A local daily-reference alarm service that checks every 15 minutes while the computer is awake and the server is running, with Windows notifications.

## Engineering approach

The application uses HTML, CSS and JavaScript with a local Python HTTP service. Validation considers symbols, data sources, timestamps, currencies and reporting periods. Missing market data is not replaced with synthetic prices or zero values. Development is AI-assisted and includes automated JavaScript/Python tests and user-assisted interface checks.

## Scope

The project uses daily historical observations and does not claim real-time BIST prices, market depth or a continuous tick feed. Coverage depends on supported symbols and external provider availability. Windows settings may affect notification visibility. The application does not submit trading orders.

## CV summary

> **MİHENK — Financial Research and Portfolio Workspace:** AI-assisted development of historical charts, Turkish news translation, period-aware financial analysis, a transaction journal and local notifications using JavaScript and Python, with data provenance, missing-data checks and automated tests.

This repository documents the project; it does not distribute the application or provide installation instructions.
