# Quartz — Privacy Policy

_Effective date: 2026-05-06_

Quartz ("we", "our", "the app") is a watch recognition and collection
management application. This policy explains what data we collect, why, and
how it is handled. The canonical App Store Privacy Policy URL is:
https://muhammedkaratas0.github.io/quartz-legal/privacy.html

## 1. Information we collect

### Account information
Quartz can create an anonymous Supabase account so your scan history and
collection persist. If you sign in with email or Sign in with Apple, we collect
the email address or Apple identifier needed to operate that account.

### Scanned images
When you use the scan feature, the photo you capture or select is sent to
Quartz and trusted AI / vision providers such as Groq and Google Cloud Vision
solely to identify the watch and return results. Images are not used by Quartz
to train AI models and are deleted from our servers after identification except
for short-lived diagnostic records.

### Collection and scan data
Watches you save, archive, or add to a wishlist, plus scan history, candidate
matches, watch references, and timestamps, are stored in Supabase and linked to
your Quartz user ID.

### Purchases
Subscription purchases are processed by Apple and managed through RevenueCat.
Quartz receives subscription state and receipt validation metadata, not your
payment card details.

### Product analytics and diagnostics
Quartz uses Amplitude and Supabase analytics events to understand app opens,
scan starts, successful scans, failed scans, paywall views, purchases, device
type, app version, coarse location derived from network data, and performance
or crash diagnostics. We do not sell this data and we do not use it to track you
across other apps or websites.

## 2. How we use data

- Identify watches you photograph and return scan results.
- Save and display your collection across devices.
- Provide subscription access and restore purchases.
- Improve scan quality, reliability, and product experience.
- Respond to support requests and prevent fraud or abuse.

## 3. Third-party services

| Provider | Role | Data shared |
| --- | --- | --- |
| Supabase | Auth, database, storage, Edge Functions | User ID, account data, collection entries, scans, diagnostics |
| Apple | Sign in with Apple, App Store payments | Standard Apple account and purchase flow |
| RevenueCat | Subscription management | App user ID, receipt/subscription metadata |
| Amplitude | Product analytics | App interaction events, user ID, device/app metadata, coarse location |
| Groq | AI watch identification | Scanned image and watch-identification prompt at request time |
| Google Cloud Vision | Visual/image understanding | Scanned image at request time |
| Firecrawl | Public web retrieval | Watch reference/search queries, not personal account data |
| eBay Browse API | Market price data | Watch reference/search queries, not personal account data |
| Wikimedia Commons and public sources | Editorial/reference content | Public attribution/source metadata |

## 4. Retention and deletion

Account, collection, and scan records are retained while your account exists.
Submitted scan images are retained only for the identification request and then
deleted. Diagnostic records tied to your account are deleted when you delete
your account; aggregated or de-identified operational metrics may be retained
for analytics and abuse prevention.

You can delete your account directly in the app at
**Profile → Settings → Delete Account**. Deletion removes your account,
collection, scan history, pending scan candidates, user-linked scan diagnostics,
and other Quartz data tied to your user ID. Deleting your Quartz account does
not cancel an active App Store subscription; manage subscriptions in your Apple
ID settings. If you used Sign in with Apple, you can also revoke Quartz from
**Apple ID Settings → Sign-In & Security → Sign in with Apple**.

## 5. Your rights

Depending on where you live, you may have rights to access, correct, export, or
delete your personal information. Contact us at hello@quartzapps.com for help.

## 6. Children

Quartz is not directed at children under 13 or the age of digital consent in
your jurisdiction. We do not knowingly collect information from children.

## 7. Contact

Questions or deletion requests: **hello@quartzapps.com**
