# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: developers and power users on macOS. They run Docker, Tailscale, VPN clients, Telegram, clipboard and screenshot tools, and accumulate ten or more Menu Bar Items until the Items compete for space — and, on notched MacBooks, start disappearing behind the notch. They already run utilities and know what a menu bar extra is, so the page can be precise and skip first-principles explanation.

## Product Purpose

Nooker is a macOS utility that tucks crowded Menu Bar Items into named Groups, each shown in the Menu Bar as a single icon. Clicking a Group reveals its Items in a Strip; once one is used, the Strip tucks itself away. A built-in Hidden Group holds Items the person never wants to see at all. Success is a Menu Bar that stays calm without ongoing fiddling.

## Positioning

Price and simplicity. Nooker is the cheapest credible option in its category — **$1.99 once**, against roughly $16 for Bartender — and it does one thing without a configuration marathon. The combination a neighboring product cannot truthfully copy: a one-time lifetime licence at that price for a single-purpose grouping tool, with no subscription and no upgrade treadmill.

## Operating Context

The product is judged in the Menu Bar itself, at a glance, dozens of times a day. Evaluation is fast and visual: a prospective user compares their own cluttered bar to a tidy one. Purchase is a small, low-deliberation decision; the barrier is trust in a small unknown utility, not budget. Setup happens once — the user drags Items into Groups and then stops thinking about it.

## Capabilities and Constraints

- Requires macOS 26 or later. **Apple Silicon only** (arm64); no Intel or universal build exists today.
- Developer ID signed by Venture Deals, Co., notarized by Apple and stapled. Distributed as a ~2 MB DMG.
- Runs entirely on the user's Mac. No account, no sign-in, no telemetry, no network calls.
- Product vocabulary is fixed and binding: **Menu Bar, Item, Group, Strip, Reveal, Hidden Group**. Avoid "icon" for an Item, and "popover", "tray", or "drawer" for a Strip.
- Licence: $1.99 one-time, lifetime, sold through a Stripe Payment Link.
- **In-app licence enforcement is not built yet** — the download is currently unrestricted. Copy must not claim gating, trial limits, or activation that does not exist.
- The landing page is static HTML/CSS served by GitHub Pages at nooker.org. No build step, no server, no framework.
- Undecided, do not assert: Intel/universal build, in-app purchase flow, automatic updates, App Store availability.

## Brand Commitments

Name: **Nooker**. Publisher: **Venture Deals, Co.** Domain: nooker.org. The existing app icon is the mark. The product vocabulary above is binding in all user-facing copy.

## Evidence on Hand

Real and usable: the shipping app itself, the notarized DMG, the app icon, the actual price and system requirements, and a working Stripe checkout. The strongest available proof is a demonstration of the mechanism — a cluttered Menu Bar becoming a tidy one.

Absent, and must never be fabricated: no users, testimonials, reviews, ratings, star counts, press coverage, download numbers, or team size. The product is **pre-launch**; the page carries zero social proof.

## Product Principles

1. **One job, done completely.** Nooker groups Menu Bar Items. It does not become a launcher, a monitor, or a tweak suite.
2. **Price is the argument.** $1.99 once is the position — state it early and plainly rather than burying it.
3. **Show the mechanism.** The before/after of a real Menu Bar is the only proof available and outperforms any claim.
4. **Claim nothing untrue today.** No invented users, no unbuilt features, no implied enforcement.
5. **Respect the vocabulary.** Groups, Items, Strips and Reveals are the product's language everywhere.
