> **Effective date:** October 15, 2026
>
> **Data controller:** Manuel Montagna, Copenhagen, Denmark
>
> **Contact:** maunamove@gmail.com

NeverLate ("the app") is a personal-productivity app made by Manuel
Montagna (sole proprietorship, Copenhagen, Denmark). In this policy, "we,"
"us," and "our" refer to Manuel Montagna, the data controller. This
describes what data the app collects, why, and your rights over it.

### 1.1 Data we collect

- **Account info** — your name and email address, provided at sign-up via
  email/password or Apple Sign In. Apple Sign In may relay a private email
  address instead of your real one; we accept either.
- **User content** — the timelines, tasks, sessions, templates, and todos
  you create inside the app. This is the core data the app exists to
  manage.
- **Profile picture** — only if you choose to upload one.
- **Feedback submissions** — when you use the in-app Feedback / Requests
  screen, we collect the subject, message, your name and email (so we can
  reply), and any optional screenshot you attach.
- **Diagnostics** — when the app encounters an error, we record the error
  details, the screen you were on, a short trail of your recent actions
  inside the app ("you tapped Save," "fetched timelines," etc.), and your
  user ID if you were signed in. We do not capture passwords, payment
  details, or the content of any text field.
- **Notification tokens** — Apple push tokens used solely to deliver
  notifications: (a) an anonymous, per-session Live Activity token that
  updates the lock screen, and (b) a device token linked to your account
  used to send notifications such as free-trial reminders. Never used for
  advertising or cross-app tracking.
- **Subscription information** — when you start a free trial or subscribe,
  we record your subscription status, plan, trial end date, and
  sandbox/production environment, linked to your account, so we can unlock
  paid features and send trial reminders. Kept in sync server-side from
  Apple's App Store Server Notifications via Superwall. **Apple handles all
  billing — we never receive or store payment details.**
- **Onboarding progress** — while you go through onboarding, and before any
  account exists, we record which step you reached, your app and iOS
  version, and whether you allowed notifications, against a random id
  generated on your device. We use it only to see where people get stuck so
  we can improve onboarding. If you go on to create an account, that record
  is linked to it. It never contains your answers to the onboarding
  questions — only which screen you reached.
- **Ad attribution** — NeverLate advertises on the App Store through Apple
  Ads. If you install the app after tapping one of these ads, Apple's
  AdServices framework tells us which campaign, ad group and search keyword
  led to the install. This is not cross-app tracking and needs no tracking
  permission. The information is passed to Superwall, which links it to
  your account ID so we can see which ads lead to subscriptions. We don't
  use it to show you ads, and we don't sell it.

We do **not** collect: your location, contacts, health data, browsing
history, search history, financial or payment details, advertising
identifiers, or any data from outside the app.

### 1.2 How we use your data (legal bases)

Every category is used solely to run the app for you. GDPR legal bases:

- **Provide the app** (account, sync, unlock paid features) — *contract*
  (Art. 6(1)(b)).
- **Send notifications** (trial reminders, Live Activity/session updates) —
  *consent* (Art. 6(1)(a)); withdraw anytime in iOS Settings.
- **Reliability & security** (diagnostics, abuse prevention) — *legitimate
  interests* (Art. 6(1)(f)).
- **Improving onboarding** (which step people reach, drop-off analysis) —
  *legitimate interests* (Art. 6(1)(f)).
- **Measuring our App Store ads** (which ad led to an install and whether
  it led to a subscription) — *legitimate interests* (Art. 6(1)(f)).
- **Feedback/support** — *contract / legitimate interests*.
- **Legal obligations** — *legal obligation* (Art. 6(1)(c)).

We do not sell your data, show ads, share with advertisers, track you
across other apps/websites, or make solely-automated decisions with legal
effect.

### 1.3 Where your data lives / processors

- **Supabase** (backend, hosted on AWS) stores your account, user content,
  profile picture, feedback submissions, device notification token,
  onboarding progress record, and subscription status. Every row is
  protected by Row Level Security, so only you (signed in as yourself) can
  read or modify your own data.
- **Apple** processes purchases/subscriptions (Apple is the seller and
  handles all billing) and delivers push notifications + Live Activity
  updates via APNs. App Store Server Notifications V2 feed subscription
  events to Superwall.
- **Superwall** manages the paywall and subscription state. We pass
  Superwall your **account user ID**, and it receives subscription
  lifecycle events (trial start, renewal, cancellation) so paid features
  unlock correctly and we can measure paywall performance. For installs
  that came from an Apple Ads ad, it also receives the ad attribution
  described in §1.1 (campaign, ad group and search keyword). Superwall
  publishes its own privacy details.
- **Resend** delivers feedback submissions to our inbox as email.

International transfers (US/outside EEA) are covered by Standard
Contractual Clauses or another lawful mechanism.

### 1.4 Data retention and deletion

- Your account, user content, profile picture, notification tokens, and
  subscription record remain until you delete your account.
- **Delete Account** (Settings → Account → Delete Account) permanently
  removes your authentication record, all user content, profile picture,
  notification tokens, and subscription record. Apple accounts also have
  their Sign in with Apple token revoked with Apple.
- Two records deliberately survive, neither linked to you afterwards: a
  record of the deletion (timestamp + plan) and your onboarding progress
  record, which is unlinked from your account on deletion. Both are kept
  purely as anonymous statistics.
- Feedback submissions (including attached screenshots) are retained as long
  as needed to follow up.
- Diagnostic / error records are retained for up to 90 days.
- Onboarding progress records follow the account while it exists. Once they
  are no longer linked to one — abandoned onboarding, or an account since
  deleted — they are removed after 12 months.

### 1.5 Your rights

EU/UK users: access, rectification, erasure, restriction, objection,
portability, and withdrawal of consent. Access/edit profile in Settings →
Account; delete account in-app; email us for anything else (one-month
response). Right to complain to your supervisory authority — in Denmark,
**Datatilsynet** (datatilsynet.dk). California users: right to know,
delete, correct; we do not sell or share personal information.

### 1.6 Children

NeverLate is intended for users **aged 13 and over** and is not directed to
children under 13. We do not knowingly collect data from children under 13.

### 1.7 Security

TLS in transit, Row Level Security on every table, scoped storage
policies, short-lived signed sessions.

### 1.8 Changes

Routine changes: we bump the effective date and publish. Material changes
(new data category, longer retention, new processor): we notify you
directly **by email or in the app** before they take effect, and ask for
consent where the law requires it.
