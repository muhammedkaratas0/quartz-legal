# Quartz — Privacy Policy

_Effective date: 2026-04-20_

Quartz ("we", "our", "the app") is a watch recognition and collection
management application developed by Ali Karataş. This policy explains what
data we collect, why, and how it is handled.

## 1. Information we collect

### 1.1 Scanned images
When you use the scan feature, the photo you capture or select is sent to our
Supabase Edge Function and processed by a third-party AI vision provider
(Groq) **solely to identify the watch in the image**. Images are **not stored
long term** on our servers; they are used in-memory during identification
and discarded once the response is returned.

### 1.2 Anonymous user identifier
Quartz automatically creates an **anonymous user account** on first launch so
your collection and scan history can persist across sessions on your device.
This user ID is a random UUID and is **not linked to your name, email, phone
number, or any other identifying information** unless you later sign in with
an external provider (not offered in v1).

### 1.3 Watch collection data
Watches you add to your collection (via the scan swipe or manual add) are
stored in our Supabase database, keyed to the anonymous user ID described
above. No personal data is attached.

### 1.4 Purchase data
Subscription purchases are processed by Apple (App Store) and reported to
us via RevenueCat for subscription management. RevenueCat receives your
anonymized Apple device/subscription identifiers but not your name or
contact information.

### 1.5 Analytics & tracking
Quartz does **not** use third-party analytics SDKs. We do **not** track
you across apps or websites. We do **not** share data with advertisers.

## 2. How we use your data

- **Scanned images**: only to identify the watch via AI.
- **Anonymous user ID + collection data**: to persist your collection across
  app launches.
- **Purchase data**: to grant and validate premium access.

## 3. Third-party services

| Provider   | Role                              | Data shared                                    |
|------------|-----------------------------------|------------------------------------------------|
| Supabase   | Backend (database, auth, storage) | Anonymous user ID, collection entries, scans   |
| Groq       | AI watch identification           | Single scanned image at request time (not stored) |
| eBay       | Market price data                 | We fetch public listings — no user data sent   |
| RevenueCat | Subscription management           | Anonymized purchase identifiers                |
| Apple      | App Store / IAP                   | Standard Apple App Store purchase flow         |

## 4. Data retention

- Anonymous user ID and collection: retained until you delete the app /
  request deletion.
- Scanned images: discarded immediately after identification.
- Raw eBay listings (in our database): rolling 30-day window, then purged.

## 5. Your rights

- **Delete your data**: uninstall the app to remove local session data.
  For full server-side deletion (anonymous user ID + collection), email
  us at the address below.
- **Export your data**: available on request.

## 6. Children

Quartz is not directed at children under 13. We do not knowingly collect
information from children.

## 7. Changes to this policy

We may update this policy; the "Effective date" above will be revised.

## 8. Contact

Questions or deletion requests: **hangiislam0@gmail.com**

---

_This policy is provided in both English and Turkish. The English version is
authoritative in case of conflict._
