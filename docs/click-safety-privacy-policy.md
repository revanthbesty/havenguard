# Click Safety — Privacy Policy

**Last updated:** 9 November 2026  
**Applies to:** Click Safety browser extension, version 0.11.2.

## Overview

Click Safety provides locally processed, rule-based warnings about suspicious links, messages that users choose to check, and some unexpected tabs appearing after a video Play interaction. Detection is heuristic. Click Safety is not antivirus software and does not include an active live malware-reputation database.

## Information processed during browsing

To provide its functions, Click Safety may inspect website URLs, link destinations, relevant webpage elements and Play-related navigation events on HTTP and HTTPS websites. When a user chooses to check a URL or pasted message, that text is evaluated locally by the extension. Navigation observations used to assess a possible unwanted tab are temporary.

## Information stored on the user's device

The extension uses browser extension-local storage to retain protection preferences, automatic tab-closing consent, selected theme, onboarding state, user-configured trusted and blocked domains, temporary website pauses and their expiry times, and aggregate activity counters. Domain exceptions may reveal which websites a user configured. Click Safety does not intentionally save the content of pasted scam-check messages or maintain a complete record of visited pages.

## Sharing and external services

The reviewed Click Safety v0.11.2 source does not include developer-operated analytics, advertising trackers, an account/login service, or an enabled remote threat-analysis service. The extension's local checking logic does not intentionally transmit browsing URLs or pasted messages to a Click Safety server. The browser and websites visited may independently make normal network requests. If an unwanted tab opens, its destination may begin loading before the optional tab-close action occurs.

## Browser permissions and purpose

- **Website access (HTTP/HTTPS):** Enables supported playback detection and on-page warning checks.
- **activeTab:** Enables user-initiated checks and website controls for the current page.
- **webNavigation:** Observes navigations potentially associated with unexpected new tabs.
- **declarativeNetRequest:** Applies locally configured blocking rules for domains users choose to block.
- **storage:** Saves local preferences, exceptions, pauses and activity summaries.
- **alarms:** Resumes checks after a temporary website pause expires.

## Controls and data retention

Automatic tab closing is **off by default** and requires the user's choice to enable it. Users can change warning settings, manage trusted and blocked domains, temporarily pause protection for a site, resume early and clear aggregate activity counts. Browser-local settings normally remain until changed or cleared by the user, or the extension is removed, subject to browser behavior.

## Limitations

A result with no detected warning signs does **not** prove a link or page is safe. Warnings can produce false positives, and optional tab closing may interfere with legitimate windows. Keep Chrome Safe Browsing enabled as an additional layer of protection. The reviewed v0.11.2 build contains no active live malicious-site database.

## Privacy questions and contact

For support and privacy questions, contact the publisher through the **Support** contact shown on the Click Safety Chrome Web Store listing. You can also find the publisher's public GitHub profile at [github.com/revanthbesty](https://github.com/revanthbesty). Do not submit passwords or sensitive personal information through public GitHub issues.

## Changes to this policy

If material processing, data storage or sharing practices change, this document and relevant store disclosures will be updated. This policy covers the identified v0.11.2 build, not unrelated browser extensions.

---

**Publication:** Public privacy policy for Click Safety. The policy describes the reviewed extension behavior; it is not a guarantee that every suspicious website will be detected.
