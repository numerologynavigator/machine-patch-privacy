# Machine Patch privacy policy

This repository publishes the public privacy policy for the Android game **Machine Patch** by **Navrang Labs**. The policy is a single static page, `index.html`.

The repository is limited to that policy and this scope note. It does not contain game source, binaries, signing files, Play Console material, ad unit IDs, or secrets. It is separate from `numerologynavigator.github.io` and from any other app repository.

## Page

- File: `index.html`
- Public address, once GitHub Pages is serving this repository: https://numerologynavigator.github.io/machine-patch-privacy/
- Pages source intended for this site: branch `main`, folder `/`
- `.nojekyll` is present so Pages serves the HTML as static files

The page adds no analytics, advertising, third-party scripts, forms, or cookies. GitHub still hosts the site and may process connection data such as IP address and server logs under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement).

## Build this policy describes

The page is specific to the current closed-test build. It does not claim that later builds collect nothing.

| Fact | Value |
| --- | --- |
| App | Machine Patch |
| Developer | Navrang Labs |
| Package | `com.machinepatch.game` |
| Channel | Closed test (audit label in the publication request: 50bay) |
| versionCode | 1 |
| versionName | 0.1.0 |
| Intended audience | 13 and older, with no age gate and no parental safeguards |
| Effective date | 7 November 2026 |
| Privacy and support contact | anandnaidu0999@gmail.com |

Practices stated for this build:

- No account, no analytics SDK, no chat, no in-app purchases, and no location sharing.
- No off-device collection or sharing of personal information by the app.
- Game progress is stored only in local preferences named `machine_patch`.
- Android backup is off, and data-extraction rules exclude preferences.
- Clearing app storage or uninstalling the app removes that local progress. The policy states no retention period and describes no backend copy.
- Google Mobile Ads SDK 25.5.0 and User Messaging Platform SDK 4.0.0 are packaged and inactive: `LIVE_ADS` is false, release `ADS_LIVE_GATE` is false, ads startup returns before consent update and `MobileAds.initialize`, `DELAY_APP_MEASUREMENT_INIT` is true, and `MobileAdsInitProvider` is removed.
- `AD_ID` and `ACCESS_ADSERVICES_AD_ID` are bundled with the SDK and unused. This version does not read an advertising ID or transmit progress.
- A later ads-enabled build has to update this policy, consent, and Play disclosures first. That later build may collect and share identifiers, IP address, ad interactions, and diagnostics with Google. The page does not describe that as current collection.
- Email to the contact address is user-initiated. The sender’s address and message are used to respond. That is separate from automatic collection by the app.

Store content ratings such as IARC General, Everyone, or PEGI 3 are not the intended-age statement and are not an in-app age gate.

## Out of scope

Do not add the game project, Gradle files, keystores, API keys, or ad unit IDs. Do not change [numerologynavigator/numerologynavigator.github.io](https://github.com/numerologynavigator/numerologynavigator.github.io) from this repository.
