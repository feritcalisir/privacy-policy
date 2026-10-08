# Play Console — Data Safety (Magnesia: Co-Op Survival)

Fill the **Data safety** form with these answers while *Magnesia* ships free with local diamonds only (see `MONETIZATION.md`).

---

## General Questions

* **Does your app collect or share any of the required user data types?** 
  * **Yes** — through the Google Play Games Services SDK (sign-in + Saved Games cloud save, added 2026-10). No ads, billing, or analytics SDKs of our own.

> **Note:** Draft answers below follow Google's guide for this SDK (*Prepare for Google Play's data disclosure requirements*). Confirm them in Play Console before submitting, since Google states the developer alone is responsible for the form.

---

## Data Collection & Sharing Summary

| Data Type | Collected | Shared | Purpose | Why / Description |
| :--- | :---: | :---: | :--- | :--- |
| **Personal info → User IDs** | Yes | No | App functionality | Play Games player identity used for sign-in. |
| **App activity → Other actions** | Yes | No | App functionality | The progress profile saved to Saved Games (cloud save). |
| **App info and performance → Diagnostics** | Yes | No | Analytics | Collected automatically by the Play Games SDK for stability. |

* **Mandatory Collection:** Collection is required on Android for cloud save to work; the game still runs without Play Games, with local saves only.
* **Settings:** User settings (language, music, visuals) are not uploaded.

---

## Future Data Types (When Ads/IAP are Added)

Update this form and `PRIVACY.md` before shipping a build that includes monetization:

| Type | Collection | Sharing | Purpose |
| :--- | :---: | :---: | :--- |
| **Device / advertising IDs** | Yes | Yes | Advertising, fraud prevention (AdMob / UMP & ad partners) |
| **Purchase history** | Yes | No | App functionality (Play Billing) |
| **App interactions (ad views)** | Yes | Yes | Advertising |

*Until then, leave those rows unset or marked as "Not collected".*

---

## Security Practices

* **Data is encrypted in transit:** Yes (Play Games Services uses HTTPS).
* **Users can request deletion:** Yes — local saves by uninstalling; cloud save and Play Games data from the Play Games profile or Google Account.
* **Committed to follow Play Families Policy if targeting children:** Follow store guidance; no personalized ads in a child-directed listing.

---

## Checklist Before Closed Testing

- [x] **Privacy policy URL:** [https://feritcalisir.github.io/privacy-policy/](https://feritcalisir.github.io/privacy-policy/) *(also in Settings → Privacy)*
- [ ] Data safety matches this file
- [ ] Screenshot set from `STORE.md` (include Giant, Oracle, Melon Warden)
- [ ] Short description $\le$ 80 characters
- [ ] No AdMob / Billing permissions in the shipped AAB unless monetization is enabled
