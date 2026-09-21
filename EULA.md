# App Store Connect EULA recommendation

**Recommend for ASC “EULA” field (all three apps):**

https://www.apple.com/legal/internet-services/itunes/dev/stdeula/

## Why

Apple’s Standard Licensed Application End User License Agreement satisfies the App Store Connect EULA field for most auto-renewable subscription apps when you also expose Privacy Policy and Terms of Use links in-app (paywall / settings).

## Custom Terms still required

Continue hosting and linking each app’s custom **Terms of Use** (and Privacy Policy) for app-specific disclaimers:

- LeaseLens — not legal advice / educational only
- PawRx — not veterinary advice; not for emergencies
- FrameMatch — personal progress photos; not professional medical/fitness advice

The Standard EULA covers Apple’s baseline licensed-application terms; it does **not** replace those product-specific disclaimers.

## LeaseLens wiring

`AppConstants.eulaUrl` already points at the Standard EULA URL.
