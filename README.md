# Motive — Legal

Public-hosted legal pages for the Motive iOS app:

- [Terms of Use](./terms.html)
- [Privacy Policy](./privacy.html)

These URLs are referenced from the App Store Connect metadata and
linked from inside the app (settings + paywall). The body text is
mirrored in the main app source at `lib/i18n/en.ts` and `ar.ts` under
the `terms.*` and `privacyPolicy.*` keys, plus the in-app screens
`app/terms.tsx` and `app/privacy.tsx`.

When the text changes, edit BOTH this repo and the in-app i18n so the
in-app screens and the public URLs stay in sync.
