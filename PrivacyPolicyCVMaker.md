# Privacy Policy for CV Maker

**Last updated:** October 13, 2026

## Overview
CV Maker ("we", "us", "our", developed by OSDev) respects your privacy. This Privacy Policy explains what information CV Maker collects, how it's used, and your choices — for both the app and this policy itself.

## Information We Collect
- **Advertising identifiers & technical data**: CV Maker shows ads through Google AdMob (Android and iOS only). To do this, Google AdMob and its partners may collect your device's advertising identifier, device model and OS version, general location derived from your IP address, and ad interaction data (e.g., which ads were shown or tapped). We do not collect this information ourselves — it's collected directly by Google in the course of serving ads. See Third-Party Services below.
- **Consent choices**: If you're in the European Economic Area (EEA), the United Kingdom, or Switzerland, Google's consent form (see "Your consent choices for ads" below) asks you whether ads may use your data. Your answer is recorded by Google's consent software (the User Messaging Platform) and stored on your device so the app can honor it. We don't receive or keep a copy of your individual choice.
- **Usage analytics (Firebase Analytics)**: To learn which parts of the app are used and what needs improving, CV Maker uses Google's Firebase Analytics (Android and iOS). It records anonymous events — for example which screens are opened, which export format you choose ("pdf", "docx"…), which template you pick, whether a QR code is shared or scanned, and whether a notification choice is changed — together with basic device and app information: device model, operating system and app version, language, approximate region derived from your IP address, a random identifier Firebase generates for this installation (the "app instance ID") and, where your device allows it, its advertising identifier. **It never includes anything you type into a CV** — no names, contact details, work history, photos or file contents. We use this data only to understand and improve the app, not to build advertising profiles. Analytics stay **off** until the consent check described under "Your consent choices" has run, and where the law requires your consent (the EEA, the United Kingdom and Switzerland) they run only if your answer allows it. We do not collect crash reports.
- **Update notifications (Firebase Cloud Messaging)**: CV Maker can send you the occasional notification about new templates and features. To deliver them, Google's Firebase Cloud Messaging gives this installation a device registration token, and the app subscribes it to a general "updates" topic. The token and the topic are used only to deliver these messages; we don't link them to your name or to anything in your CVs. Notifications appear only if you allow them in the system's permission prompt (asked once — on the last page of the welcome tour, or when you turn notifications on in Settings). You can stop them at any time in **Settings → Notifications** (which also removes this installation from the topic) or in your device's notification settings.
- **Location**: CV Maker does not itself use or collect precise location data.
- **User content**: CV Maker lets you create and store CV/résumé content — your name, contact details, work history, education, skills, and similar information you choose to enter, plus an optional photo. This content is stored only on your device. It never leaves your device unless you actively choose to export or share it (as a PDF, Word, image, HTML or other file; or as a QR code you save or share), or turn on the optional Google Drive backup described below — we do not otherwise receive, transmit, or have any access to it. Files and images you save or share go wherever you choose to put them (your Files app, a messaging app, an email, and so on), and from that point they're outside our control.
- **QR codes**: QR codes are generated on your device. A contact-card code contains the contact details from your CV. A full-CV code contains your whole CV — every section, its template, color, fonts and page style, and (if you leave **Include photo** on) a small version of your photo — as a short series of codes that the other phone scans in one go. Anyone who receives or scans these codes can read what's inside them, so share them only with people you trust.
- **Camera and scanning QR codes**: CV Maker asks for camera access only so that **Scan QR Code** (Home → the scan icon) can read a QR code, and it uses the camera only while that screen is open. The code is read entirely on your device — on Android by Google's ML Kit barcode scanner (its model is bundled in the app), on iOS by Apple's Vision framework. CV Maker does not record, save, or upload camera images or video. If you choose to scan from a saved picture instead, the app reads only the one picture you select with the system photo picker. What a scan finds stays on your device: a contact card or CV becomes a new CV only if you tap **Create CV**, and a link is opened only if you tap **Open link**; anything else is just shown to you, and nothing is stored unless you copy it yourself. You can deny or later withdraw camera access in your device settings — the rest of the app, including importing from a picture, works the same.
- **Backup files**: **Settings → Import/Export Data** creates a file that contains all your CVs, their photos, and your app settings (theme, language, favorite templates). It is written wherever you choose to put it (or sent through the app you choose to share it with) and from then on it is outside our control — treat it like your CV itself. Importing reads only the file you pick, and lets you either merge it into the CVs already on your device or replace them.
- **Display choices**: Each CV also remembers, on your device only, its template and color, the light or dark page, the fonts, and the order of its sections; your favorite templates are remembered in the app's settings. None of this is sent anywhere.
- **Account information**: CV Maker does not require an account and stores no personal account information.

## How We Use Information
Your CV content is used solely to provide the app's core function: building, previewing, and exporting your CV. We don't use it for anything else, because we never receive it ourselves. Information collected by Google AdMob is used to deliver ads and measure their performance, and — where applicable and consented to — to personalize them. Anonymous analytics are used to see how the app is used and to improve it, and the notification token is used to deliver the update notifications you've allowed.

## Legal Bases (GDPR / UK GDPR)
Where the GDPR or UK GDPR applies, the legal bases we rely on are:
- **Your consent** (Article 6(1)(a)) for storing or accessing information on your device, for using your data to show or personalize ads, for usage analytics, and for showing you notifications (the system permission). You can withdraw it at any time (see below); withdrawing doesn't affect anything done before you withdrew.
- **Providing the app you asked for** (Article 6(1)(b)) for building and exporting your CV, which happens entirely on your device.

For ad serving, Google acts as an independent controller of the data it collects through AdMob; for Firebase Analytics and Cloud Messaging, Google processes the data on our behalf. For everything you create in the app, nobody but you holds the data — we are not a processor or controller of your CV content, since we never receive it.

## Third-Party Services
CV Maker is integrated with:
- **Google AdMob** (advertising, Android/iOS only) — https://policies.google.com/privacy
- **Google Firebase — Analytics and Cloud Messaging** (anonymous usage analytics and update notifications, Android/iOS only — see "Usage analytics" and "Update notifications" above) — https://firebase.google.com/support/privacy
- **Google ML Kit** (reads QR codes on Android, on the device — see "Camera and scanning QR codes" above; as with other Google libraries, it may collect limited technical and diagnostic information, such as the app version and device model) — https://policies.google.com/privacy
- **Apple Vision** (reads QR codes on iOS, on the device; part of the operating system)
- **Google Drive** (optional cloud backup — see below) — https://policies.google.com/privacy
- **Open-source fonts**: the typefaces you can choose for a CV are bundled in the app (SIL Open Font License 1.1). They are never downloaded, and no request is made to a font service when you preview or export.

We don't control how these services handle data beyond what we describe here; their own privacy policies apply to their part of the processing.

### Optional Google Drive backup
Settings → Sync → Google Drive lets you back up your CVs to your own Google Drive and restore them later. As of this version of the app, this feature is not yet enabled — turning it on requires signing in with your Google account, which isn't wired up in this build, so no CV content is sent to Google Drive today. Once it is enabled in a future update: signing in is handled by Google's own sign-in flow (we don't see or store your Google password); your backup file is written to a private, app-only area of your Google Drive ("app data folder") that isn't visible in your regular Drive file list and that no one — including us — can access except CV Maker acting on your behalf; and you can disconnect or delete that file at any time. **iCloud backup is planned but has no implementation yet** — choosing it in the app currently just shows a "coming soon" message and sends no data anywhere.

### Your consent choices (ads and analytics)
CV Maker uses Google's consent management platform (the User Messaging Platform) so that ads and analytics are handled in line with the law where you live.
- **In the EEA, the United Kingdom and Switzerland**, a consent form from Google appears when you open the app, asking whether information may be stored or accessed on your device and whether your data may be used to personalize ads. CV Maker doesn't request any ads, and doesn't switch on analytics, until that choice has been made, and honors it afterwards. If you decline, ads that depend on your consent aren't requested — so you may see limited ads, or none — analytics stay off, and the rest of the app works exactly the same.
- **Changing your mind**: in those regions, **Settings → Privacy options** reopens the form at any time so you can review or withdraw your consent. (The entry only appears where the rules require it.)
- **Elsewhere**, no consent form is shown, and ads follow the device-level controls below.
- **Device-level controls** also apply everywhere: on Android, Settings → Privacy → Ads (reset or delete your advertising ID); on iOS, Settings → Privacy & Security → Tracking, and Settings → Privacy & Security → Apple Advertising.

## Data Sharing & Disclosure
We do not sell your personal information. We share information only with the third-party services listed above (Google AdMob; Google Firebase for analytics and notifications; on Android, Google ML Kit's technical data; and Google Drive if and when you use the optional backup feature), as required by law, or to protect the rights and safety of CV Maker, our users, or the public.

## Data Retention
Your CV content stays on your device for as long as you keep it there. You can delete an individual CV at any time from within the app, or remove everything at once using Settings → Delete All Data. Uninstalling the app also removes everything stored locally. Files, backup files and QR images you've saved or shared are separate copies that stay wherever you put them until you delete them yourself. Analytics events are kept by Google Analytics for a limited period set in our Firebase project (no longer than 14 months) and are not tied to your name; the notification token stays until you uninstall the app, reset the app's data, or switch notifications off in Settings (which removes the topic subscription). If you've used the optional Google Drive backup once it's enabled, your backup file remains in your own Google Drive until you delete it yourself (from the app, or directly in Drive) — uninstalling CV Maker does not delete it, since it lives in your Google account, not ours.

## Your Rights & Choices
Because your CV content lives only on your device, you already hold full access, correction, and deletion rights over it directly in the app — edit any field, delete an entry, or use Delete All Data at any time.

If the GDPR or UK GDPR applies to you, you also have the right to access, correct, erase, restrict, and port the personal data held about you, to object to its processing, and to withdraw your consent at any time (for ads and analytics: Settings → Privacy options, or the device-level controls above; for notifications: Settings → Notifications or your device's notification settings). Most of this data is held by Google rather than by us — Google's own privacy tools (https://myaccount.google.com/data-and-privacy) let you manage it. You also have the right to lodge a complaint with your local data-protection authority; in France, that is the CNIL (https://www.cnil.fr).

For anything else, contact us at omransoliman.osdevapps@gmail.com

## Children's Privacy
CV Maker is not directed at children under 13, and we do not knowingly collect personal information from children under 13. The app may be used by a mixed-age audience; we do not knowingly serve behavioral or interest-based advertising to users who identify as under 13. If we learn we've collected personal information from a child under 13 without verified parental consent, we will delete it promptly. A parent or guardian who believes their child has provided us with personal information can contact us at omransoliman.osdevapps@gmail.com to request its deletion.

## Security
We take reasonable measures to protect your information, but no method of transmission or storage is completely secure, and we can't guarantee absolute security.

## International Data Transfers
CV Maker is developed in France. Your CV content isn't transmitted anywhere by us. Information collected by Google AdMob, Firebase and Google ML Kit (and, once enabled, Google Drive backups you choose to use) may be processed in the countries where Google operates; where data leaves the EEA, UK or Switzerland, Google relies on the transfer safeguards described in its own terms and privacy policy.

## Changes to This Policy
We may update this Privacy Policy from time to time — for example, when the Google Drive backup becomes available, new features need new permissions, or the way ads, analytics, notifications and consent are handled changes. We'll update the "Last updated" date when we do, and encourage you to review this policy periodically.

## Contact Us
Questions about this policy? Contact us at omransoliman.osdevapps@gmail.com
