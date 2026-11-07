# Machine Patch privacy policy

This repository publishes the public privacy policy for the Android game **Machine Patch** by **Navrang Labs**. The policy is a single static page, `index.html`.

The repository is limited to that policy and this scope note. It does not contain game source, binaries, signing files, Play Console material, ad unit IDs, or secrets. It is separate from `numerologynavigator.github.io` and from any other app repository.

## Page

- File: `index.html`
- Canonical URL: https://numerologynavigator.github.io/machine-patch-privacy/
- Pages source: branch `main`, folder `/`
- `.nojekyll` is present so Pages serves the HTML as static files

GitHub Pages is enabled for this repository and publishes `main` from the repository root. Merging to `main` starts a Pages rebuild. A merged commit is not, by itself, evidence that the public URL is serving the new text. After a change, request the canonical URL and confirm HTTP 200 and the updated wording.

The page adds no analytics, advertising, third-party scripts, forms, or cookies. GitHub still hosts the site and may process connection data such as IP address and server logs under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement).

## Builds this policy describes

The page covers two closed-test **release** builds. Their data practices match. It does not claim that a later build collects nothing. Debug builds are outside that release description: a debug build can request Google demo ads, and the releases below do not.

| Fact | versionCode 1 | versionCode 2 |
| --- | --- | --- |
| versionName | 0.1.0 | 0.1.1 |
| Package | `com.machinepatch.game` | `com.machinepatch.game` |
| Distribution | Closed-test release | Closed-test release |
| Puzzles | 50 | 50, with no gameplay or data-practice change |
| Collection and sharing | None off the device | None off the device |
| Progress | Local preferences `machine_patch` only | Same |
| Backup | Off; extraction rules exclude preferences | Same |
| Account, analytics, chat, IAP, location | Absent | Absent |
| Ads SDK | Google Mobile Ads 25.5.0 and UMP 4.0.0 packaged and inactive | Same |
| Release ad gate | `LIVE_ADS` false, `ADS_LIVE_GATE` false, return before consent and `MobileAds.initialize` | Same |
| Manifest ads setup | `DELAY_APP_MEASUREMENT_INIT` true, `MobileAdsInitProvider` removed | Same |
| Advertising permissions | Unused and bundled: `AD_ID`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | All four removed |
| Network permissions | Not separately restated here | Release keeps `INTERNET` and `ACCESS_NETWORK_STATE`; that is not collection or sharing |
| In-app privacy | Not part of this release | Home screen Privacy control shows the canonical policy URL and anandnaidu0999@gmail.com; external browser and mailto; no in-app browser |
| Intended audience | 13 and older, no age gate, no parental safeguards | Same |
| Effective date | 7 November 2026 | Same date; practices are unchanged |
| Contact | anandnaidu0999@gmail.com | anandnaidu0999@gmail.com |

A build after these two that turns advertising on has to update this policy, consent, and Play disclosures first. That later build may collect and share identifiers, IP address, ad interactions, and diagnostics with Google. versionCode 1 and versionCode 2 do not do that.

Store content ratings such as IARC General, Everyone, or PEGI 3 are not the intended-age statement and are not an in-app age gate.

Email to the contact address is user-initiated, including the mailto link on the versionCode 2 Home screen. The sender’s address and message are used to respond. That is separate from automatic collection by the app. The policy states no retention period and describes no backend.

## Out of scope

Do not add the game project, Gradle files, keystores, API keys, or ad unit IDs. Do not change [numerologynavigator/numerologynavigator.github.io](https://github.com/numerologynavigator/numerologynavigator.github.io) from this repository. Do not change the Pages source away from `main` `/`.
