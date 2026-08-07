# ShiftScan Privacy Policy

**Last updated: 6 August 2026**

ShiftScan turns a work schedule into calendar events and alarms. It is built so that
your schedule never leaves your phone. This policy describes exactly what that means.

## What stays on your device

Everything that identifies you or your work:

- **Photos of your schedule.** The image is processed on your device and is never
  uploaded. We cannot see it.
- **Your schedule itself** — shift dates, times, codes, and the name or row you
  identified as yours.
- **Your calendar.** ShiftScan requests *write-only* calendar access. It can add the
  shifts you confirm. It cannot read your existing events, and it never does.
- **Your alarm rules.**

There is no account, no sign-in, and no server holding your data. Nothing above is
transmitted anywhere.

## What is sent off the device

Two things, neither containing your schedule:

**1. Anonymous usage counts.** ShiftScan reports which steps of the app are being used,
so we know which parts work. The complete list of events is:

`scan_started` · `scan_parsed` · `commit_done` · `alarm_armed` · `paywall_shown` ·
`purchase_started` · `purchase_completed` · `purchase_cancelled` ·
`share_flow_shown` · `share_flow_completed`

These are counts only. No shift times, no dates, no names, no image data, and no free
text is attached to them. Alongside them, TelemetryDeck sends your **device model and
app version**, so we can tell whether a problem is specific to one iPhone or one
release. TelemetryDeck does not build user profiles or advertising identifiers.

**2. Purchase status.** If you subscribe, RevenueCat processes the purchase and tells
the app whether your subscription is active. Apple handles the payment itself; we never
see your payment details. Your subscription is tied to an anonymous identifier, not to a
name or email.

## What ShiftScan never does

- No advertising, and no advertising SDKs.
- No selling or sharing of data with third parties.
- No tracking across apps or websites.
- No location collection.
- No reading of your existing calendar events.
- No account, so nothing to breach or leak.

## Sharing a schedule with us

If a schedule fails to read, ShiftScan may offer to let you send us the photo so we can
improve it. This is entirely optional, always asks first, and never happens
automatically. If you choose to share, the photo is stripped of location and other EXIF
metadata before it is handed to the iOS share sheet, and you choose where it goes.
Declining changes nothing about how the app works.

## Children

ShiftScan is intended for people of working age and does not knowingly collect data
from children.

## Your rights

Because ShiftScan holds no account and no personal data on any server, there is no
personal data for us to export, correct, or delete. Deleting the app removes your
schedule and alarm rules from your device. Shifts already written to your calendar stay
there — they are your calendar's events, and you can delete them yourself at any time.

There is currently no in-app switch to turn off the anonymous usage counts described
above. They contain no schedule content and no identifier that points back to you, but
we would rather state the limitation plainly than imply a control that does not exist.
Deleting the app stops them.

## Changes

If this policy changes, the date at the top changes with it. Material changes will be
noted in the app's release notes.

## Contact

Questions about this policy: open an issue at
<https://github.com/volat1/shiftscan-support>.
