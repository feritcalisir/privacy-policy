Play Console — Data safety (no ads / no IAP; Play Games cloud save)
Fill the Data safety form with these answers while Magnesia ships free with local diamonds only (see MONETIZATION.md).
Does your app collect or share any of the required user data types?
Yes — through the Google Play Games Services SDK (sign-in + Saved Games cloud save, added 2026-10). No ads, billing or analytics SDKs of our own.
Draft answers below. They follow Google's guide for this SDK (Prepare for Google Play's data disclosure requirements); confirm them there before submitting, since Google says the developer alone is responsible for the form.
Data type	Collected	Shared	Purpose	Why
Personal info → User IDs	Yes	No	App functionality	Play Games player identity used for sign-in
App activity → Other actions (game progress)	Yes	No	App functionality	The progress profile saved to Saved Games
App info and performance → Diagnostics	Yes	No	Analytics	Collected automatically by the Play Games SDK for stability
Collection is required on Android for cloud save to work; the game still runs without Play Games, with local saves only.
Settings (language, music, visuals) are not uploaded.
Data collected (when ads/IAP are added later)
Update this form and PRIVACY.md before shipping a build that includes:
Type	Collection	Sharing	Purpose
Device / advertising IDs	Yes (AdMob / UMP)	Yes (ad partners)	Advertising, fraud prevention
Purchase history	Yes (Play Billing)	With Google	App functionality
App interactions (ad views)	Yes	Ad partners	Advertising
Until then: leave those rows unset / “Not collected”.
Security practices
Data is encrypted in transit: Yes (Play Games Services uses HTTPS).
Users can request deletion: Yes — local saves by uninstalling; cloud save and Play Games data from the Play Games profile or Google account.
Committed to follow Play Families Policy if targeting children: follow store guidance; no personalized ads in a child-directed listing.
Checklist before closed testing
[x] Privacy policy URL: https://feritcalisir.github.io/privacy-policy/ (also in Settings → Privacy)
[ ] Data safety matches this file
[ ] Screenshot set from STORE.md (include Giant, Oracle, Melon Warden)
[ ] Short description ≤80 characters
[ ] No AdMob / Billing permissions in the shipped AAB unless monetization is enabled
