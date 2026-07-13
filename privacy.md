# NeverLate — Privacy Policy

**Effective date:** May 30, 2026

**Contact:** maunamove@gmail.com

NeverLate ("the app," "we," "us") is a personal-productivity app made by
Manuel Montagna. This policy explains what data the app collects, why it
collects it, and your rights over that data.

## 1. Data we collect

- **Account info** — your name and email address, provided at sign-up via
  email/password or Apple Sign In. Apple Sign In may relay a private
  email address instead of your real one; we accept either.
- **User content** — the timelines, tasks, sessions, templates, and
  todos you create inside the app. This is the core data the app exists
  to manage.
- **Profile picture** — only if you choose to upload one.
- **Feedback submissions** — when you use the in-app Feedback / Requests
  screen, we collect the subject, message, your name and email (so we
  can reply), and any optional screenshot you attach.
- **Diagnostics** — when the app encounters an error, we record the
  error details, the screen you were on, a short trail of your recent
  actions inside the app ("you tapped Save," "fetched timelines," etc.),
  and your user ID if you were signed in. We do not capture passwords,
  payment details, or the content of any text field.
- **Push tokens** — an anonymous Apple push token used to update the
  Live Activity on your lock screen as your session progresses.
- **Subscription state** — if and when in-app purchases ship, we record
  which subscription tier you are on so we can unlock paid features.

We do **not** collect: your location, contacts, health data, browsing
history, search history, financial information, advertising identifiers,
or any data from outside the app.

## 2. How we use your data

Every category above is used solely for **app functionality** — to sign
you in, sync your data across your devices, render widgets and Live
Activities, reply to your feedback, and surface helpful error messages
when something goes wrong. We do not sell your data, share it with
advertisers, or use it to track you across other apps or websites.

## 3. Where your data lives

- **Supabase** (our backend, hosted on AWS) stores your account, your
  user content, your profile picture, and your feedback submissions.
  Each row is protected by Row Level Security, so only you (signed in
  as yourself) can read or modify your own data.
- **Apple** (APNs and Live Activity infrastructure) receives push
  tokens and Live Activity payloads as required by iOS to update your
  lock screen. Apple's privacy terms apply to this transit.
- **Superwall** processes anonymous funnel
  analytics so we can tell if a paywall is working. Superwall publishes
  its own privacy details in its SDK.
- **Resend** delivers feedback submissions to our inbox as email.

## 4. Data retention and deletion

- Your account, your user content, and your profile picture remain
  until you delete your account.
- **You can delete your account from inside the app**: Settings →
  Account → Delete Account. This permanently removes your
  authentication record, every row of your user content, your profile
  picture, and all associated tokens. A minimal record of the deletion
  (anonymous timestamp and reason, if you provided one) is retained for
  our own analytics; it is not linked to your identity after deletion.
- Feedback submissions you send are retained as long as we may need
  them to follow up. You can ask us to delete them at the contact
  address above.
- Diagnostic / error records are retained for up to 90 days.

## 5. Your rights

You can:

- **Access and edit** your profile data from Settings → Account.
- **Delete your account** in-app at any time.
- **Contact us** at the email above to request a copy of your data or
  to ask any other privacy question.

Depending on where you live (EU, UK, California, etc.) you may have
additional rights under GDPR, UK GDPR, or CCPA — including the right to
object to processing or to lodge a complaint with your supervisory
authority. Contact us and we will help you exercise any of these rights.

## 6. Children

NeverLate is not directed to children under 13. We do not knowingly
collect data from children under 13. If you believe a child has
provided us data, contact us and we will delete it.

## 7. Security

We use industry-standard measures to protect your data, including TLS
in transit, Row Level Security on every database table, scoped storage
policies, and short-lived signed sessions. No system is perfectly
secure, but we treat your data as if it were our own.

## 8. Changes

If we change this policy in a way that affects your rights, we will
notify you in-app before the change takes effect.
