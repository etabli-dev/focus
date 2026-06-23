# Etabli Focus

> Track focused work blocks by category.

`iOS` `Android` · Apache-2.0 · Part of the [Etabli Suite](https://github.com/etabli-dev)

Etabli Focus is a Pomodoro and focus-session tracker. Track work blocks by category (deep work, review, admin, research, manuscript, data analysis) with configurable focus and break durations and local notifications. Timers survive force-quit and reboot. Entirely offline.

## Availability

- **App Store (iOS):** available.
- **Google Play:** available.
- **F-Droid (main repo):** built from this repo's `/android` source.

## Privacy

No analytics. No third-party SDKs. No accounts. Credentials, where needed, live only in the platform secure store (iOS Keychain / Android EncryptedSharedPreferences). This app is fully offline.

## Repository layout

```
ios/        SwiftUI app
android/    Kotlin + Jetpack Compose app
fastlane/   F-Droid / store listing metadata
```

Both platforms are one product, sharing the Coder Design System tokens.

## Tech

iOS: SwiftUI + SwiftData. Android: Compose, Room, DataStore, AlarmManager

**Status:** Complete on both platforms

## Support development

- 💚 **[Liberapay](https://liberapay.com/rabanheller/)** — recurring, 0% commission, shown on F-Droid.
- ☕ [Buy Me a Coffee](https://buymeacoffee.com/rabanheller) — one-off tip (also the in-app link on iOS/Android).

## License

Apache License 2.0 — see [LICENSE](LICENSE) and [NOTICE](NOTICE).

Copyright 2026 Raban Heller.
