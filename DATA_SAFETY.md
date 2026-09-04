# Play Console — Data safety (no ads / no IAP build)

Fill the Data safety form with these answers while Magnesia ships **free with local diamonds only** (see [MONETIZATION.md](MONETIZATION.md)).

## Does your app collect or share any of the required user data types?

**No** — for the current build without AdMob / Play Billing / analytics SDKs.

Rationale: progress is stored only on-device (`user://` profile). No account, no cloud sync, no ads SDK.

## Data collected (when ads/IAP are added later)

Update this form and [PRIVACY.md](PRIVACY.md) before shipping a build that includes:

| Type | Collection | Sharing | Purpose |
|------|------------|---------|---------|
| Device / advertising IDs | Yes (AdMob / UMP) | Yes (ad partners) | Advertising, fraud prevention |
| Purchase history | Yes (Play Billing) | With Google | App functionality |
| App interactions (ad views) | Yes | Ad partners | Advertising |

Until then: leave those rows unset / “Not collected”.

## Security practices

- Data is encrypted in transit: **N/A** (no network user data).
- Users can request deletion: uninstall clears local saves on that device.
- Committed to follow Play Families Policy if targeting children: follow store guidance; no personalized ads in a child-directed listing.

## Checklist before closed testing

- [x] Privacy policy URL: https://feritcalisir.github.io/privacy-policy/ (also in Settings → Privacy)
- [ ] Data safety matches this file
- [ ] Screenshot set from [STORE.md](STORE.md) (include Giant, Oracle, **Warden**)
- [ ] Short description ≤80 characters
- [ ] No AdMob / Billing permissions in the shipped AAB unless monetization is enabled
