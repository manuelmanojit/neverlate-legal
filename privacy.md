# NeverLate — Privacy Policy

**Effective date:** July 15, 2026

**Data controller:** Manuel Montagna, Copenhagen, Denmark

**Contact:** maunamove@gmail.com

NeverLate ("the app") is a personal-productivity app made by Manuel
Montagna, a sole proprietorship based in Copenhagen, Denmark. In this
policy, "we," "us," and "our" refer to Manuel Montagna, the data
controller responsible for your personal data. This policy explains what
data the app collects, why it collects it, the legal bases we rely on, and
your rights over that data.

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
- **Notification tokens** — Apple push tokens used only to deliver
  notifications to your device: (a) an anonymous, per-session token that
  updates the Live Activity on your lock screen, and (b) a device token
  linked to your account that lets us send you notifications such as
  free-trial reminders. These tokens are used solely to deliver
  notifications — never for advertising or cross-app tracking.
- **Subscription information** — when you start a free trial or subscribe,
  we record your subscription status, the plan, the trial end date, and
  whether the transaction is in Apple's sandbox or production environment,
  linked to your account, so we can unlock paid features and send trial
  reminders. **Billing is handled entirely by Apple** — we never receive
  or store your card or payment details.

We do **not** collect: your location, contacts, health data, browsing
history, search history, financial or payment details, advertising
identifiers, or any data from outside the app.

## 2. How we use your data, and our legal bases

We only use the data above to run the app for you. Under the EU/UK GDPR,
our legal bases are:

- **To provide the app** — creating and securing your account, storing and
  syncing your content across devices, and unlocking paid features:
  *performance of a contract with you* (Art. 6(1)(b)).
- **To send notifications** — free-trial reminders and Live Activity /
  session updates: *your consent* (Art. 6(1)(a)), which you give by
  allowing notifications and can withdraw at any time in iOS Settings.
- **To keep the app reliable and secure** — recording diagnostics,
  preventing abuse, and fixing errors: *our legitimate interests* in
  operating a stable, secure service (Art. 6(1)(f)).
- **To respond to your feedback** — replying to messages you send us:
  *performance of a contract / our legitimate interests*.
- **To meet legal obligations** — where the law requires us to retain or
  disclose data: *legal obligation* (Art. 6(1)(c)).

We do **not** sell your data, show you ads, share your data with
advertisers, or use it to track you across other apps or websites. We do
**not** make decisions about you by solely automated means that produce
legal or similarly significant effects.

## 3. Who processes your data

We use a small number of service providers ("processors") to run the app.
Each acts on our instructions:

- **Supabase** (our backend, hosted on AWS) stores your account, your
  user content, your profile picture, your feedback submissions, your
  device notification token, and your subscription status. Each row is
  protected by Row Level Security, so only you (signed in as yourself) can
  read or modify your own data.
- **Apple** processes your purchases and subscriptions (Apple is the
  seller and handles all billing), and its APNs / Live Activity
  infrastructure delivers push notifications and lock-screen updates.
  Apple's privacy terms apply to this processing.
- **Superwall** manages our paywall and subscription state. We provide
  Superwall with your account's user ID, and Superwall receives
  subscription lifecycle events (trial start, renewal, cancellation) so
  that paid features unlock correctly and we can measure whether the
  paywall works. Superwall publishes its own privacy details in its SDK.
- **Resend** delivers your feedback submissions to our inbox as email.

## 4. International data transfers

Some of our processors (including Supabase/AWS, Apple, Superwall, and
Resend) may process data on servers located in the United States or other
countries outside the European Economic Area. Where personal data is
transferred outside the EEA/UK, that transfer is protected by appropriate
safeguards — such as the European Commission's Standard Contractual
Clauses — or another lawful transfer mechanism. Contact us for more detail
on the safeguards in place.

## 5. Data retention and deletion

- Your account, your user content, your profile picture, your notification
  tokens, and your subscription record remain until you delete your
  account.
- **You can delete your account from inside the app**: Settings →
  Account → Delete Account. This permanently removes your authentication
  record, every row of your user content, your profile picture, your
  notification tokens, and your subscription record. A minimal record of
  the deletion (anonymous timestamp and reason, if you provided one) is
  retained for our own analytics; it is not linked to your identity after
  deletion.
- Feedback submissions you send are retained as long as we may need them
  to follow up. You can ask us to delete them at the contact address
  above.
- Diagnostic / error records are retained for up to 90 days.

## 6. Your rights

Depending on where you live, you have rights over your personal data. For
users in the EU/UK, these include the right to:

- **access** the personal data we hold about you;
- **rectify** inaccurate data;
- **erase** your data ("right to be forgotten");
- **restrict** or **object to** our processing;
- **data portability** — receive your data in a portable format;
- **withdraw consent** at any time (e.g. by turning off notifications),
  without affecting processing done before withdrawal.

You can already **access and edit** your profile from Settings → Account,
and **delete your account** in-app at any time. For any other request,
email us at maunamove@gmail.com and we will respond within one month.

You also have the right to **lodge a complaint with your supervisory
authority**. In Denmark this is Datatilsynet (datatilsynet.dk); in the
EU/UK you may contact your local authority.

## 7. California privacy rights (CCPA/CPRA)

If you are a California resident, you have the right to know what personal
information we collect, to request its deletion or correction, and to not
be discriminated against for exercising these rights. In the past 12
months we have collected the categories described in Section 1 —
identifiers (name, email, user ID), customer records, app-activity /
diagnostic data, and commercial information (subscription status).

We do **not** and will not **sell** your personal information, and we do
**not** **share** it for cross-context behavioral advertising, as those
terms are defined under the CCPA/CPRA. To exercise your rights, email us
at maunamove@gmail.com; we verify requests using the email associated with
your account.

## 8. Children

NeverLate is intended for users **aged 13 and over** and is not directed
to children under 13. We do not knowingly collect personal data from
children under 13. If you believe a child has provided us data, contact us
and we will delete it.

## 9. Security

We use industry-standard measures to protect your data, including TLS in
transit, Row Level Security on every database table, scoped storage
policies, and short-lived signed sessions. No system is perfectly secure,
but we treat your data as if it were our own.

## 10. Changes

If we change this policy in a way that affects your rights, we will update
the effective date above and notify you in-app before the change takes
effect.
