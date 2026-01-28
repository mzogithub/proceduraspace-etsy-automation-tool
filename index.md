# ProceduraSpace Etsy Automation Tool (Private Seller App)

This is a personal, private automation tool I’m building to manage my own Etsy shop:
https://www.etsy.com/shop/proceduraspace

Contact: beyondmzo+proceduraspace@gmail.com

## What it does
ProceduraSpace Studio Tools automates parts of my daily listing workflow for my single Etsy shop. It is designed to:

- Gather public “trend/context” inputs (e.g., headlines/topics from public data sources)
- Generate creative concepts and prompts for daily artwork
- Produce a finished digital artwork file (single-image digital download)
- Create an Etsy listing as a **draft first**, then publish after review
- Upload the listing image and the digital download file

## Scope and users
- **Private use only**: this tool is for **my own shop only**
- No public SaaS, no “customer logins,” and no access to other sellers’ shops
- I do not provide my Etsy API credentials to any third-party software service

## Etsy API usage (high level)
- Uses Etsy Open API v3 for shop/listing management
- Uses OAuth 2.0 authorization and only requests the minimum scopes needed
- Intended workflow:
  1) Create draft listing
  2) Upload listing images / digital files
  3) Activate listing

## Compliance notes
- All items published are digital downloads created from my own creative direction.
- Where required, listings will include appropriate disclosure if AI tools were used in the creation process (per Etsy’s policies).
- This project is **not** for scraping Etsy, cloning Etsy, or mass-listing spam.

## Status
Work in progress / under development. This repository exists as a public “app info” page for Etsy’s API application review.

## Security
This repo intentionally contains **no secrets** (no API keys, tokens, or private workflow exports).
