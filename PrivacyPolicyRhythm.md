# Privacy Policy for Rhythm

**Last updated:** August 31, 2026

This policy explains what data Rhythm collects, how it's used, and what
choices you have. Rhythm is built to keep your data on your own devices
by default — the sections below explain exactly where the exceptions to
that are.


## 1. Who this policy covers

Rhythm is developed by **OSDev**. This policy applies to the Rhythm app
everywhere it's offered — Android, iOS, macOS, Windows, and Linux.

## 2. Data stored on your device

When you use Rhythm to create activities, run timers, and review your
history, the following is stored **locally on your device only**:

- The activities you create (names, icons, colors)
- Your session/timer history (start and end times, durations, notes you
  add)
- App settings and preferences (theme, accent color, activity labels,
  quick-start choices, Timer View style)
- If you use the pairing feature (Section 4): the encryption keys and
  names of the specific devices you've approved, so Rhythm can
  recognize them again

This data is not collected by us, is not sent to our servers (we don't
operate any), and is not shared with third parties, except as described
in Section 5 (advertising) and Section 4 (device pairing/sync). There is
no user account, sign-up, or login — Rhythm doesn't know who you are.

Uninstalling the app removes this data from your device (subject to
your device's normal backup behavior — see Section 6).

## 3. Data we do not collect

We do not collect your name, email address, location, contacts, or
photos. Rhythm does not require an internet connection to track your
time. The one exception is camera access: if you use device pairing
(Section 4), the camera is used live, on-device, to read a QR code —
no photo or video is captured, stored, or transmitted, by Rhythm or
anyone else.

## 4. Device pairing and cross-device sync

Rhythm lets you connect two or more of your own devices — for example
a phone and a desktop — so your activities, sessions, and settings stay
the same across them. This is optional and off until you set it up.

**How pairing works:** the desktop app shows a QR code; a phone scans
it with the camera (Section 3), over your local Wi-Fi network. This
exchanges a unique encryption key directly between the two devices — it
does not pass through, or get seen by, any server we operate. Once
paired, each device stores the other's key and name so it can recognize
that specific device again. A phone never shows a code of its own and
is never independently reachable on the network — it only connects out
to a paired desktop, the same direction any sync or unlock action from
it takes.

**How sync works:** while two paired devices are reachable on the same
local network, changes to activities, sessions, and settings are
exchanged directly between them and encrypted in transit, so a change
made on one shows up on the other. This same connection is also how a
paired phone can lock or unlock a paired desktop, or extend a
desktop's unlock period by watching a rewarded ad instead — see
Section 5 for what that involves.

**Your control:** you choose which devices to pair by scanning a code
yourself, and you can remove a paired device at any time from within
the app, which stops it from syncing or unlocking further. Pairing and
sync only work over your local network — they don't work over the
internet or across networks.

## 5. Advertising

Rhythm shows ads served by **Google AdMob** on Android and iOS: banner
ads shown while using the app, and an optional rewarded ad a paired
phone can choose to watch to extend a paired desktop's unlock period by
a number of days (Section 4). Watching a rewarded ad is always a choice
— a desktop still unlocks the ordinary way, a paired phone tapping
Unlock, with no ad involved, and nothing in the app requires watching
one.

To serve either kind of ad, Google's Mobile Ads SDK may collect and
process information such as your device's advertising identifier,
general device information, and app usage/interaction data, in
accordance with [Google's Privacy Policy](https://policies.google.com/privacy) and
[How Google uses information from sites or apps that use our
services](https://policies.google.com/technologies/partner-sites).
Depending on your region and settings, this may include
personalized/interest-based advertising; you can generally control ad
personalization through your device's ad settings (e.g. "Opt out of Ads
Personalization" on Android, or "Limit Ad Tracking"/App Tracking
Transparency permissions on iOS).

Rhythm's own activity, session, and note data (Section 2) is never
shared with or used by the advertising SDK for ad targeting, for either
kind of ad. Ads are not shown on macOS, Windows, or Linux builds — the
Mobile Ads SDK doesn't run on desktop, so the rewarded-ad unlock option
is only ever available from a paired phone, never from the desktop
itself.

## 6. Third-party services

- **Google AdMob** — see Section 5.
- **Device backups** — if your device's operating system (e.g. Android
  auto-backup, iOS/iCloud backup) is configured to back up app data,
  Rhythm's local data may be included in that backup under your
  platform's own backup and account settings, outside of our control.

Rhythm does not use any analytics or crash-reporting SDKs, and does not
use any third-party service for device pairing or sync (Section 4) —
that connection is directly between your own devices.

## 7. Permissions Rhythm requests

**Android:**
- **Camera** — used only to scan another device's pairing QR code
  (Section 4). Not used anywhere else in the app.
- **Internet / network state / Wi-Fi state** — to load ads and for
  device pairing/sync (Section 4).
- **Local network device discovery** — used only while pairing or
  syncing is active, so a paired device can be found again on the
  network after its address changes, instead of needing to be re-paired.

**iOS:**
- **Camera** — same use as Android, above.
- **Local Network** — used only while device pairing/sync is active, so
  your phone can find and reach a paired desktop on the same Wi-Fi
  network.

**macOS, Windows, and Linux (desktop):**
- **Camera** — same use as above (used only on machines with a built-in
  or connected camera, for showing/verifying a pairing code).
- **Local network (incoming and outgoing connections)** — the desktop
  app is the side a paired phone connects to, so it listens for those
  connections on your local network; on Windows/Linux this may surface
  as a one-time firewall prompt to allow Rhythm to accept them.
- **Keychain access (macOS only)** — used to store the encryption keys
  for paired devices (Section 4) using the operating system's own
  secure storage.

Rhythm does not request access to your contacts, photos, microphone, or
precise location on any platform.

## 8. Data retention and deletion

Since your activity/session data lives only on your own device(s), you're
always in control of it:

- Delete individual sessions or activities from within the app at any
  time — if that device is paired and syncing (Section 4), the deletion
  syncs to your other paired devices too.
- Remove a paired device at any time to stop it from syncing further
  (Section 4).
- Uninstalling the app removes its local data from that device (subject
  to Section 6's note on backups).

Because there's no account or server-side copy of your data, there's
nothing for us to delete on request — the data simply isn't anywhere
but your own device(s) (and any device backups you've configured, per
Section 6).

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
omransoliman.osdevapps@gmail.com
