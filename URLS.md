# Legal URL wiring map

> **Draft note:** These documents are drafts for App Store compliance and should be reviewed by a licensed attorney before relying on them as formal legal advice to the operator.

Intended GitHub Pages base: `https://nighthawk455.github.io/app-legal/`

After publish, update the constants below (currently `example.com` placeholders).

| App | Document | Hosted URL | Constant to update | File |
|-----|----------|------------|--------------------|------|
| FrameMatch | Privacy Policy | https://nighthawk455.github.io/app-legal/framematch/privacy.html | `AppConstants.privacyPolicyUrl` | `apps/FrameMatch/lib/core/constants/app_constants.dart` |
| FrameMatch | Terms of Use | https://nighthawk455.github.io/app-legal/framematch/terms.html | `AppConstants.termsOfUseUrl` | `apps/FrameMatch/lib/core/constants/app_constants.dart` |
| LeaseLens | Privacy Policy | https://nighthawk455.github.io/app-legal/leaselens/privacy.html | `AppConstants.privacyPolicyUrl` | `apps/LeaseLens/lib/core/constants/app_constants.dart` |
| LeaseLens | Terms of Use | https://nighthawk455.github.io/app-legal/leaselens/terms.html | `AppConstants.termsOfUseUrl` | `apps/LeaseLens/lib/core/constants/app_constants.dart` |
| LeaseLens | Apple Standard EULA | https://www.apple.com/legal/internet-services/itunes/dev/stdeula/ | `AppConstants.eulaUrl` | `apps/LeaseLens/lib/core/constants/app_constants.dart` |
| PawRx | Privacy Policy | https://nighthawk455.github.io/app-legal/pawrx/privacy.html | `BillingConstants.privacyPolicyUrl` | `apps/PawRx/lib/billing/billing_constants.dart` |
| PawRx | Terms of Use | https://nighthawk455.github.io/app-legal/pawrx/terms.html | `BillingConstants.termsOfUseUrl` | `apps/PawRx/lib/billing/billing_constants.dart` |

## Index

- https://nighthawk455.github.io/app-legal/index.html

## Notes

- FrameMatch and PawRx do not currently define an `eulaUrl` constant; LeaseLens already links Apple’s Standard EULA on paywall/settings.
- Contact email used in HTML: `kmeckhoff81@gmail.com` — **Contact email confirmed: kmeckhoff81@gmail.com
- Governing law in Terms: State of Illinois — **GOVERNING_LAW_TO_CONFIRM**.
