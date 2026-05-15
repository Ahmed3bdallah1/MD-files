# Privacy Policy — Magic Clean

**Effective date:** 14 May 2026  

This Privacy Policy describes how **Magic Clean** (“we”, “us”, “our”), in connection with the Magic Clean mobile application and related services operated through **https://magiccleanksa.com**, collects, uses, stores, and shares information when you use the app.

By using Magic Clean, you agree to this Privacy Policy. If you do not agree, please do not use the app.

> **Important:** This document is written to reflect the **functionalities present in the Magic Clean codebase** (authentication, bookings, maps, profiles, payments, notifications, admin/technical tools, and third-party SDKs). It is **not legal advice**. You should have a qualified lawyer review and adapt it for your entity name, Saudi **Personal Data Protection Law (PDPL)** requirements, and any payment processor or hosting agreements you use.

---

## 1. Who we are

The **data controller** is the organization that operates Magic Clean and the backend at `magiccleanksa.com`. For privacy requests (access, correction, deletion, complaints), use the official contact channels published in the app or on the website (you should insert the correct email or form here when publishing).

---

## 2. Scope

This policy applies to:

- **Clients (customers):** browsing services, creating accounts, booking cleaning and related services, managing addresses and orders, paying, rating, support tickets, packages, favorites, and notifications.
- **Technicians:** viewing assigned or available work in their areas, managing availability/time plans, and interacting with job-related data.
- **Administrators:** managing users, services, service types, areas, tags, extra options, promo codes, tickets, statistics, and related operational content (including images uploaded for services or user profiles where applicable).

---

## 3. Information we collect

We collect information **you provide**, **generated when you use the app**, and **from your device** where needed to run features.

### 3.1 Account and identity

- **Phone number** (used for OTP verification and account identification; numbers may be normalized to international format, e.g. Saudi `+966`).
- **Name** and **password** (where registration with password is used).
- **Authentication tokens** stored on the device (e.g. session/access token, role) to keep you signed in.
- **Profile image** if you choose to upload one during registration or when an admin creates or updates a user profile with a photo.

### 3.2 Service delivery and bookings

- **Service selections**, cart contents, **time slots**, **technician availability** choices, and **service requests/orders**.
- **Addresses** you save or enter for service visits (including location-related fields needed to perform the service).
- **Ratings and feedback** you submit for completed services or technicians.
- **Promo codes** you apply at checkout.
- **Packages** you view, subscribe to, or that are linked to your account.
- **Favorites** (services or items you mark as favorites, including any identifiers stored locally or synced with the server per your implementation).

### 3.3 Payments

- Information required to **process payments** through the methods supported by our backend (e.g. selected payment method, transaction references).  
  **We do not describe your full payment stack here** — your payment gateway (e.g. bank, wallet, card network) will have its own privacy policy; we only receive what is necessary to confirm and record the transaction.

### 3.4 Support and communications

- **Support tickets** and messages you send through the app.
- **In-app notifications** (content delivered via our API; read/unread status may be stored server-side).

### 3.5 Location

- **Approximate or precise device location** when you grant permission, used for maps, address search, connecting you with services or areas, and improving the booking experience.  
- On **Android**, the app may request **foreground** and **background** location permissions where declared in the manifest; background use should match what you actually implement and disclose in the store listing.

### 3.6 Device and technical data

- **Device and app identifiers**, **IP address**, **language/locale**, **diagnostic** and **security-related** logs typical of mobile apps and APIs (e.g. fraud prevention, stability).
- **Firebase** initialization is used in the app; depending on configuration, Google/Firebase may process limited technical or analytics-related data according to [Google’s privacy documentation](https://firebase.google.com/support/privacy).
- **Push notification token (FCM):** the backend exposes an endpoint to store an **FCM token** for push messaging. If enabled in your build, the token may be sent to our servers to deliver notifications.

### 3.7 Media (photos)

- **Images** you or authorized staff select from the gallery or camera for **profile photos** or **admin-managed service/marketing images** are transmitted to our servers as part of forms or uploads.

### 3.8 Maps and places

- When you use map or address search features, **Google Maps**, **Google Places**, and **geocoding** services may process queries and coordinates under [Google’s policies](https://policies.google.com/privacy).

### 3.9 Local storage on your phone

- The app uses **local storage** (e.g. `SharedPreferences`) for items such as **auth token**, **user role**, **onboarding completion**, **theme or language preferences**, and other small app settings. Some favorites-related data may also be stored locally depending on feature wiring.

### 3.10 Optional profile-related data

- Where the app supports **vehicles or car sizes** (e.g. for services that depend on vehicle type), related details you enter may be stored and sent to the API.

---

## 4. How we use your information

We use the data above to:

1. **Create and secure your account** (OTP, passwords where used, sessions).  
2. **Provide, schedule, and fulfill** cleaning and related services.  
3. **Show availability**, technicians, areas, pricing, banners, and packages.  
4. **Process payments** and apply discounts (promo codes).  
5. **Communicate** with you about orders, policies (booking/cancellation), and notifications.  
6. **Improve** reliability, safety, and user experience.  
7. **Operate** admin and technician tools (assigning work, managing catalog, support, statistics).  
8. **Comply with law** and respond to lawful requests.

---

## 5. Legal bases (summary)

Depending on applicable law (including **Saudi PDPL** where relevant), we rely on bases such as:

- **Performance of a contract** (providing the service you requested).  
- **Consent** (e.g. location, notifications, optional profile photo).  
- **Legitimate interests** (security, fraud prevention, product improvement), balanced against your rights.  
- **Legal obligation** (tax, accounting, or regulatory retention).

---

## 6. Sharing of information

We may share data with:

- **Service providers** that host our API, databases, email/SMS/OTP providers, and **payment processors**.  
- **Google** (Maps, Places, Geocoding, Firebase, and fonts loaded via `google_fonts` where applicable).  
- **Technicians** (limited data needed to perform your booking: e.g. address, time, service details).  
- **Authorities** when required by law or to protect rights and safety.

We do **not** sell your personal information as a commodity; any “sale” definitions under foreign laws should be reviewed with counsel if you operate globally.

---

## 7. International transfers

Data may be processed on servers or by subprocessors **inside or outside Saudi Arabia**. Where required, we implement appropriate safeguards (e.g. contracts, assessments) in line with PDPL and other applicable rules.

---

## 8. Retention

We keep information **as long as your account is active**, **as needed to provide services**, and **as required by law** (e.g. financial records). When data is no longer needed, we delete or anonymize it according to internal policies (to be defined by your legal/ops team).

---

## 9. Security

We use industry-reasonable technical and organizational measures (encryption in transit where TLS is used, access controls on servers, secure handling of tokens). No method of transmission or storage is 100% secure.

---

## 10. Your rights

Subject to local law, you may have the right to:

- **Access** your personal data.  
- **Correct** inaccurate data.  
- **Delete** certain data or your account (where not prohibited by law).  
- **Object** or **restrict** certain processing.  
- **Withdraw consent** for optional processing (e.g. location, marketing push).  
- **Lodge a complaint** with the Saudi **SDAIA** data protection authority where applicable.

To exercise rights, contact us through the channels you publish for Magic Clean.

---

## 11. Children

Magic Clean is **not intended for children** without parental involvement. We do not knowingly collect data from children below the minimum age defined by applicable law. If you believe we have, contact us and we will delete it.

---

## 12. Third-party links

The app or banners may link to third-party sites. Their privacy practices are governed by **their** policies, not this one.

---

## 13. Changes to this policy

We may update this Privacy Policy from time to time. We will post the new version in the app or on the website and update the **Effective date**. Continued use after changes may constitute acceptance, where permitted by law.

---

## 14. Contact

**Operator:** Magic Clean — **https://magiccleanksa.com**  

Insert: **privacy contact email**, **phone**, and **mailing address** before distribution.

---

## Appendix — Feature checklist (for store disclosures)

Use this checklist for **App Store / Google Play** privacy forms and permission justifications:

| Area | Data / permission | Typical purpose |
|------|-------------------|-----------------|
| Account | Phone, name, password, profile image | Sign-up, login, profile |
| OTP | Phone, SMS gateway metadata | Verification |
| Bookings | Addresses, times, services, notes | Fulfillment |
| Payments | Payment method selection, transaction refs | Checkout |
| Location | Fine/coarse/background (as actually used) | Maps, nearby services |
| Maps/Places | Queries, coordinates | Address picker |
| Notifications | In-app list; optional FCM token | Updates on orders |
| Media | Camera / photo library | Profile or admin images |
| Firebase | App configuration / messaging infra | Core mobile services |
| Local device | Tokens, preferences | Session, UX |

---

*End of Privacy Policy*
