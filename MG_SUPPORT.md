# Help & Support — Magic Clean

Last updated: **14 May 2026**

This document describes how users and partners can get help when using **Magic Clean** (the mobile app related to **[https://magiccleanksa.com](https://magiccleanksa.com)**).

> Replace **placeholders** in square brackets `[like this]` with your real phone, email, WhatsApp Business link, or support portal before publishing.

---

## 1. Who this is for

- **Customers (clients)** — bookings, payments, addresses, packages, cancellations, refunds, account access.
- **Technicians** — jobs, schedules, areas, ratings.
- **Business / admin teams** — using the dashboard or APIs as provided by Magic Clean operators.

---

## 2. How to reach us

| Channel | When to use |
|--------|---------------|
| **In-app Contact** | Tap **Contact Us** in the app (drawer/menu) for the primary support path you expose in the UI. |
| **Email** | `[support@magiccleanksa.com]` — account issues, receipts, disputes, privacy requests (see **[PRIVACY_POLICY.md](./PRIVACY_POLICY.md)**). |
| **Phone** | `[+966-xx-xxx-xxxx]` — urgent service-day issues when you operate a phone line. |
| **[Website](https://magiccleanksa.com)** | Announcements, web contact forms, or help pages if available. |

If your product uses **in-app tickets** (`/api/client/tickets`), describe here: **Open Profile / Help → Submit ticket** (adjust to match your actual screens).

---

## 3. Response times

- **Business hours:** `[e.g. Sunday–Thursday, 9:00–18:00 AST]`  
- **Expected first reply:** `[e.g. within 24–48 business hours]` for non-emergency tickets; **same-day** for critical safety or payment failures where feasible.

Actual SLAs depend on your operations—set realistic windows and keep them consistent with Play/App Store listings.

---

## 4. Common topics (FAQ)

### Account & sign-in

- **OTP not received:** Check SMS reception, airplane mode, and correct **`+966` mobile number**. Wait for the countdown, then tap resend once. Avoid VPNs blocking SMS gateways if applicable.
- **Wrong number:** Ensure the digits match the SIM you use for Magic Clean.

### Booking & scheduling

- **Confirm time and address** before submitting the order.
- Service **areas** may be limited; if you see a message about an **unsupported area**, pick a listed area or contact support—availability depends on technician coverage.

### Location & maps

- **Grant location permission** when prompted so we can validate your area and simplify address selection.
- If **maps or search fail**, check Internet access, disable conflicting VPN/proxy briefly, and update the app and **Google Play services** (Android) / OS (iOS).

### Payments

- For **declined payments** or missing confirmation, capture the **approximate time** and **payment method** (never send full card numbers by email unless your processor instructs secure channels).
- Refund rules follow the **cancellation policy** shown in the app; see **[Cancellation policy](#policy-booking)** below.

### Cancellations & refunds

- See in-app sections for **cancellation windows**, **fees**, **no-show** rules, and **refunds**, or API-backed policy content at `https://magiccleanksa.com` when exposed in the client.
- For **exceptions or emergencies**, the app refers users to **customer support**—use the contact methods in **Section 2**.

### Notifications

- Enable **notifications** for order updates if your device build uses push (FCM). In-app notification list is available where the app exposes it.

### Technicians

- Job or **schedule issues:** use your in-app technician flow first, then escalate via your internal dispatcher or `[technician-support@…]`.

---

## 5. Reporting a bug

Please include:

1. **App version** (Settings / About if available, or store version).
2. **Device model** and **OS version** (Android / iOS).
3. **Steps to reproduce** the problem.
4. **Screenshots** (no passwords or payment card data).
5. **Approximate date & time** (important for logs).

Send to `[support@magiccleanksa.com]` or your ticket system.

---

## 6. Security & abuse

To report **security vulnerabilities**, **fraud**, or **account compromise**, email `[security@magiccleanksa.com]` with “**Security**” in the subject (or your organization’s coordinated disclosure inbox).  

Do **not** post exploit details publicly before a fix is coordinated, if possible.

---

## 7. Related documents

- **[PRIVACY_POLICY.md](./PRIVACY_POLICY.md)** — how we handle personal data.
- **Booking / cancellation / privacy screens** inside the app — short summaries; official terms may also live on the website.

---

## 8. Store compliance (short blurb for copy-paste)

**Support contact:** `[email or URL]`  
**Support website:** [https://magiccleanksa.com](https://magiccleanksa.com)

---

*Magic Clean — help file for distribution with the project. Update placeholders and response times before production use.*
