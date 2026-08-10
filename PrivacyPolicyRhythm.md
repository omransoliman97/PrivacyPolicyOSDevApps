# Privacy Policy for Rhythm

**Last updated:** [August 7, 2026]

This policy explains what data Rhythm collects, how it's used, and what
choices you have. Rhythm is built to keep your data on your own device
by default — the sections below explain exactly where the exceptions to
that are.

> Fill in the bracketed placeholders below (contact email, developer
> name, effective date) before publishing this policy.

## 1. Who this policy covers

Rhythm is developed by **[Developer name / "osdev"]**. This policy
applies to the Rhythm app on Android and iOS, and to the local web
dashboard the app can optionally host (see Section 4).

## 2. Data stored on your device

When you use Rhythm to create activities, run timers, and review your
history, the following is stored **locally on your device only**:

- The activities you create (names, icons, colors)
- Your session/timer history (start and end times, durations, notes you
  add)
- App settings and preferences (theme, accent color, activity labels,
  quick-start choices, Timer View style, local server settings)

This data is not collected by us, is not sent to our servers (we don't
operate any), and is not shared with third parties, except as described
in Section 5 (advertising) and Section 4 (the optional local dashboard).
There is no user account, sign-up, or login — Rhythm doesn't know who
you are.

Uninstalling the app removes this data from your device (subject to
your device's normal backup behavior — see Section 6).

## 3. Data we do not collect

We do not collect your name, email address, location, contacts, photos,
or any other personal information, and Rhythm does not require an
internet connection to track your time.

## 4. The optional local (LAN) dashboard

Rhythm includes an optional feature that runs a small web server on
your device, reachable only from other devices on the **same local
Wi-Fi network** (for example, a laptop or tablet at home) — it is never
reachable over the public internet. This feature is off by default and
only starts when you turn it on.

While it's running:

- Anyone on the same local network who has the address (an IP address
  or a `<name>.local` hostname you can customize) can view your
  activities, sessions, and settings, and start, pause, resume, or stop
  timers, using a browser — no separate account or app install is
  needed on that device.
- This traffic stays on your local network; it is not relayed through
  any server we operate.
- Multiple devices with Rhythm installed can each host and use this
  feature independently. Data is not automatically merged or shared
  between separate installations of the app on different devices.

We recommend only enabling this on networks you trust (e.g. not a
public/shared Wi-Fi network), since anyone else on that same network
with the address could reach the dashboard while it's running.

## 5. Advertising

Rhythm shows banner ads served by **Google AdMob**, on both Android and
iOS. This is how the app is able to remain free.

To serve ads, Google's Mobile Ads SDK may collect and process
information such as your device's advertising identifier, general
device information, and app usage/interaction data, in accordance with
[Google's Privacy Policy](https://policies.google.com/privacy) and
[How Google uses information from sites or apps that use our
services](https://policies.google.com/technologies/partner-sites).
Depending on your region and settings, this may include
personalized/interest-based advertising; you can generally control ad
personalization through your device's ad settings (e.g. "Opt out of Ads
Personalization" on Android, or "Limit Ad Tracking"/App Tracking
Transparency permissions on iOS).

Rhythm's own activity, session, and note data (Section 2) is never
shared with or used by the advertising SDK for ad targeting.

## 6. Third-party services

- **Google AdMob** — see Section 5.
- **Device backups** — if your device's operating system (e.g. Android
  auto-backup, iOS/iCloud backup) is configured to back up app data,
  Rhythm's local data may be included in that backup under your
  platform's own backup and account settings, outside of our control.

Rhythm does not use any analytics, crash-reporting, or user-tracking
SDKs beyond what's described above.

## 7. Permissions Rhythm requests

**Android:**
- **Internet / network state / Wi-Fi state** — to load ads and to run
  the optional local dashboard (Section 4).
- **Wi-Fi multicast** — used only while the local dashboard is running,
  so other devices on your network can find it by name (`<name>.local`)
  instead of typing an IP address.
- **Foreground service** — used only while the local dashboard is
  running, so it can keep working reliably while you're using other
  apps.
- **Notifications** — used to show the status of the local dashboard
  while it's running (e.g. that it's active), not for marketing or
  promotional messages.

**iOS:**
- **Local Network** — used only while the local dashboard is running, so
  it can be reached by other devices on the same Wi-Fi network.

Rhythm does not request access to your contacts, photos, camera,
microphone, or precise location on either platform.

## 8. Data retention and deletion

Since your activity/session data lives only on your device, you're
always in control of it:

- Delete individual sessions or activities from within the app at any
  time.
- Uninstalling the app removes its local data from your device (subject
  to Section 6).

Because there's no account or server-side copy of your data, there's
nothing for us to delete on request — the data simply isn't anywhere
but your device (and any device backups you've configured, per Section
6).

## 9. Children's privacy

Rhythm is not directed at children under 13 (or the relevant minimum age
in your region), and we do not knowingly collect personal information
from children. Advertising shown via Google AdMob is subject to
Google's own policies regarding child-directed treatment where
applicable.

## 10. Changes to this policy

We may update this policy from time to time (for example, as app
features change). Material changes will be reflected by updating the
"Last updated" date above.

## 11. Contact

Questions about this policy or Rhythm's data practices can be sent to:
**[omransoliman.osdevapps@gmail.com]**
