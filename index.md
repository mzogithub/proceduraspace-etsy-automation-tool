# ProceduraSpace Etsy Automation Tool (Private Seller App)

This is a personal, private automation tool I’m building to manage my own Etsy shop:
https://www.etsy.com/shop/proceduraspace

Last updated: 2026-01-28  
Contact: beyondmzo+proceduraspace@gmail.com

## What it does
ProceduraSpace Studio Tools automates parts of my daily listing and reporting workflow for my single Etsy shop. It is designed to:

- Gather public “trend/context” inputs (e.g., headlines/topics from public data sources)
- Generate creative concepts and prompts for daily artwork
- Produce finished digital artwork files (digital downloads)
- Create Etsy listings as **drafts first**, then publish after review
- Upload listing images and the digital download file
- Poll my shop’s order/sales data on a schedule to update internal reports/spreadsheets

## Scope and users
- **Private use only**: this tool is for **my own shop only**
- No public SaaS, no customer logins, and no access to other sellers’ shops
- I do not provide Etsy API credentials to any third-party software service

## Etsy API usage (high level)
- Uses Etsy Open API v3 for shop/listing management and sales/order reporting
- Uses OAuth 2.0 authorization and only requests the minimum scopes needed
- Intended listing workflow:
  1) Create draft listing
  2) Upload listing images / digital files
  3) Activate listing
- Reporting workflow:
  - Scheduled polling of my shop’s orders/receipts to update internal analytics (e.g., spreadsheets)

## Compliance notes
- All items published are digital downloads created from my own creative direction.
- Where required, listings include appropriate disclosure if AI tools were used in the creation process (per Etsy’s policies).
- This project is **not** for scraping Etsy, cloning Etsy, or mass-listing spam.
- This tool does not email customers or export customer data for marketing.

## Status
Work in progress / under development. This repository exists as a public “app info” page for Etsy’s API application review.

## Security
This repo intentionally contains **no secrets** (no API keys, tokens, or private workflow exports).
