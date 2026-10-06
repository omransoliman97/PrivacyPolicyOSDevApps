# Smart Tally — Privacy Policy

**Last updated:** October 6, 2026

This Privacy Policy explains what data Smart Tally ("the app") collects, how it's used, and the choices you have. Smart Tally is published by **OSDev** ("OSDev," "we," "us"). It is built to be **local-first**: your counters, groups, and history are yours, stored on your own device, with no account required to use the app.

---

## 1. Data You Create, and Where It Lives

When you create counters, groups, adjust values, rename things, or set preferences, that information is stored **only on your device**, in a local database. We do not operate a server that receives or stores this data, and it is never uploaded automatically.

This includes:
- Counters, groups, and their names, colors, and values
- Counting history (each increment/decrement, and when it happened)
- Settings (theme, default view, sound/haptics preferences, etc.)

**You control this data entirely.** You can export it (Backup), share it, delete individual counters or their history, wipe everything at once with **Settings → Delete All Data**, or remove it all by uninstalling the app.

## 2. Home Screen Widget (Android)

If you add a Smart Tally widget to your home screen, the counter data it displays is shared with the widget through your device's own local storage (not the internet) so the widget can show the same values as the app.

Taps you make on the widget are saved in the app's private storage on your device until the app has recorded them in its database, so changes made on the widget and changes made in the app are always kept in step and none are lost — even if the app is closed when you tap. None of this leaves your device.

## 3. Advertising (Google AdMob)

Smart Tally shows ads (banner, interstitial, and rewarded) through **Google AdMob** to support free use of the app. This is the one part of Smart Tally that does involve a third party.

To serve and measure ads, Google's Mobile Ads SDK may collect and process, as described in Google's own disclosure:
- Device and advertising identifiers (e.g. Android advertising ID and app set ID; Apple's IDFA on iOS — subject to your device's tracking permission)
- IP address, which can be used to estimate your approximate location
- Interaction data (e.g. app launches, taps, video views, ad impressions and clicks)
- Diagnostic and performance information about the app and the SDK (e.g. launch time, hang rate, energy usage)

Google states that this data is encrypted in transit. Depending on your settings and region, it may be used to personalize the ads you see. You can control ad personalization at any time:
- **Android:** Settings → Privacy → Ads → *Delete advertising ID* or *Opt out of Ads Personalization*
- **iOS:** Settings → Privacy & Security → Tracking, or Settings → \[App name\] → Allow Tracking

Google's own privacy practices for this data are described at:
- https://policies.google.com/privacy
- https://policies.google.com/technologies/ads

**Ad consent (EEA/UK):** for users in the European Economic Area or the UK, Google requires an ads consent mechanism (Google's User Messaging Platform / a Consent Management Platform) to legally gather consent before showing personalized ads there. Smart Tally **implements this**: on launch, the app requests a consent information update and, where Google determines a consent form is required (EEA/UK users), shows Google's own consent form before any ad loads. You can review or change this choice at any time from **Settings → Ad Privacy Options** inside the app (shown wherever your region requires it). This is in addition to — not a replacement for — completing Google AdMob's own EU consent settings in your AdMob account.

## 4. Rewarded Ads & Widget Access

On Android, the home screen widget works for a limited window of days: **2 days** are included when you first open the app, and you can add more by choosing to watch a **rewarded ad**. Watching is always optional, and always happens only after you confirm in a dialog. When an ad finishes, Google AdMob tells the app how many days it is worth, and the app adds them.

To make this work, the app stores **one date and time** on your device — when your widget access ends — in its private local storage, and shares it with the widget (also locally, on your device) so the widget can lock and unlock itself. There is no account, and we don't run a server that tracks rewards or ad views, so we never receive this information. The ad itself is served and measured by Google as described in §3.

Uninstalling the app, or clearing its data, removes this date. **Delete All Data** (see §9) deliberately leaves it in place: it's an entitlement — days you've earned — not content you created.

## 5. Notifications

Smart Tally asks for notification permission once, during first-launch setup, explaining why (limit-reached alerts) before the system prompt appears. If you enable limit-reached alerts, Smart Tally schedules local notifications directly on your device. No notification content is sent to us or to any third party. You can change this permission at any time in your device's system settings for the app.

## 6. Text-to-Speech

If you enable spoken feedback, counter values are read aloud using your device's own built-in text-to-speech engine. Nothing is sent off your device for this feature.

## 7. Sharing & Export

Features like Backup, CSV export, and Share only send your data where **you** explicitly direct them — e.g. the share sheet you choose (Files, Mail, another app). Smart Tally does not transmit this data anywhere on its own.

## 8. Children's Privacy

Smart Tally is a general-purpose counting utility, not directed at children under 13, and we do not knowingly collect personal information from children. If you believe a child has provided us information, contact us using the details below and we'll address it.

## 9. Data Retention & Deletion

Because your data lives on your device, you're in control of it at all times:
- Delete a single counter, its history, or a whole group from within the app
- Clear a counter's history without deleting the counter
- **Settings → Delete All Data** permanently deletes every counter, group, history entry, and setting; the widget's copy of your counters and any widget taps not yet recorded; notifications the app has already shown; and the CSV/backup files the app created in its temporary storage in order to share them. It returns the app to how it was on first install. It asks you to confirm first, and it can't be undone. (Backups or exports you have already saved or sent elsewhere are yours and aren't touched, and your widget access days are kept, as explained in §4.)
- Uninstalling the app permanently removes all locally stored data

## 10. Your Rights

Depending on where you live, you may have rights to access, correct, or delete your personal data. Since Smart Tally's own data is stored locally and never leaves your device (aside from the ad data described in §3), the primary way to exercise these rights for app data is directly within the app (for example with Delete All Data) or by uninstalling it. For data processed by Google as described in §3, see Google's privacy resources linked above, or contact Google directly.

## 11. Security

Your data is protected by your device's own operating-system-level app sandboxing. As with any app, keeping your device's OS up to date and using a device passcode helps keep locally stored data secure.

## 12. Changes to This Policy

We may update this policy from time to time, for example if we add a feature that changes what data is collected. We'll update the "Last updated" date above when we do. Continued use of the app after a change means you accept the updated policy.

## 13. Contact Us

Questions about this policy or your data? Contact OSDev at:

omransoliman.osdevapps@gmail.com
