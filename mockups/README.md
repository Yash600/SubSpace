# Subspace.money — Product Teardown
### Product Intern Assignment · Yash Vardhan Malik · May 2026

---

## Overview

A hands-on product teardown of [Subspace.money](https://subspace.money) — India's subscription sharing & savings marketplace. This submission includes a full written report and **5 interactive UI mockups** showing proposed fixes.

---

## 📄 Report

The full teardown PDF covers 5 product pillars across GTM, UX, Features, Competitor Analysis, and Potential Collaborations — each with a specific Observed → Problem → Ship Instead structure using 7Ps, SWOT, and Porter's Five Forces frameworks.

---

## 🖥 UI Mockups — Proposed Fixes

Each mockup is a self-contained HTML file showing the current state vs. the proposed redesign.

| # | Mockup | Pillar | Fix |
|---|--------|--------|-----|
| 01 | [First-Run Onboarding Flow](mockups/01-onboarding.html) | UX | 3-step role-based onboarding overlay for new users |
| 02 | [Dashboard Redesign](mockups/02-dashboard.html) | UX | Renames 'Home' → 'Dashboard', surfaces Money Saved as hero widget |
| 03 | [Checkout Redesign](mockups/03-checkout.html) | UX | Fixes date bug, adds group fill visualisation & Subspace Guarantee |
| 04 | [Gift Card Page](mockups/04-gift-card.html) | UX + Features | Removes text wall, structures purchase info in single viewport |
| 05 | [Subscription Catalog](mockups/05-subscription-catalog.html) | Features | Expands from 8 to 50+ services with category filters + custom add |

---

## 5 Pillars Summary

### 01 · UX — 7Ps (Product & Process)
**Problem:** Trust breaks at first visit (no onboarding), at checkout (2028 date bug, empty groups), at vendor management ('Active but NOT LIVE'), and in the wallet ('Locked Amount' unexplained).  
**Fix:** Role-based first-run flow, correct date copy, group fill progress bar, Money Saved as dashboard hero.

### 02 · Features/Services — SWOT (Weaknesses)
**Problem:** Only 8 trackable subscriptions on a platform promising to manage all of them. Negotiate API marketed but absent from product. Bill Payments empty in primary nav.  
**Fix:** 50+ service catalog, activate/remove Negotiate API, hide Bill Payments behind 'Coming Soon'.

### 03 · GTM & ICPs — 7Ps (People & Promotion)
**Problem:** 3 user types (buyers, group owners, vendors) with identical navigation and zero role-based onboarding. Privacy policy copied from Amazon's template.  
**Fix:** Role-based first sessions, ICP-specific landing pages, DPDP-compliant privacy policy.

### 04 · Competitor Analysis — Porter's Five Forces
**Problem:** Real competitor is WhatsApp+UPI (free, trusted, zero friction) — not Spliiit or GoSplit. No trust layer (credential security, refund protection, dispute resolution) to beat informal sharing.  
**Fix:** Subspace Guarantee (group breaks → next month free), aligned T&C, India-first moat investment.

### 05 · Potential Collaborations — SWOT (Opportunities)
**Problem:** Subspace has a Refer & Earn program but no structured acquisition channels — no campus partnerships, no corporate benefits integration, no UPI refund partner.  
**Fix:** Campus ambassador program, B2B corporate benefits dashboard, PhonePe/GPay refund integration.

---

## Prioritisation

| Priority | Fix | Why |
|----------|-----|-----|
| 1 | Surface Money Saved + onboarding + fix date bug | Pure product, no new infra, immediate user impact |
| 2 | Expand subscription catalog to 50+ | Delivers on core promise |
| 3 | Campus ambassador program | Near-zero CAC, highest ICP fit |
| 4 | Rewrite privacy policy | DPDP 2023 compliance, non-negotiable |
| 5 | Subspace Guarantee + UPI refund partner | Beats WhatsApp+UPI on accountability |

---

*Built with genuine product thinking — every observation comes from actually using the app.*
