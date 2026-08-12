# Privacy Policy for Monster Remote

Effective date: 2026-08-12

Monster Remote is an unofficial companion app and Alexa skill for supported Gym Monster machines. Monster Remote is not affiliated with, endorsed by, or sponsored by Speediance.

This policy explains which information Monster Remote processes, why it is used, and the choices available to you. Features that use cloud sync, Apple Health, AI, Alexa, or speech recognition are optional.

## Information We Process

Depending on the features you use, Monster Remote may process:

- **Account information:** A private Sign in with Apple account identifier and, when Apple provides them, a display name or private relay email. Monster Remote never receives your Apple password. Identifiers and email addresses are stored as one-way hashes on the Monster Remote Intelligence server.
- **Training information:** Workout history and summaries such as exercise names or identifiers, sets, repetitions, resistance, volume, duration, distance, muscle load, and related machine measurements.
- **Optional Apple Health context:** Only categories you explicitly authorize, such as sleep duration, resting heart rate, heart-rate variability, and workout heart-rate context. You can change Health access at any time in iOS Settings or the Health app.
- **Machine and app information:** Machine identifiers or serial numbers, firmware and app versions, platform, first and last seen timestamps, connection state, trial status, and premium entitlement status.
- **Training Buddies information:** Your friend code, optional display name and avatar URL, buddy relationships and requests, sharing preference, live training state, current exercise or workout title, training start time, cheers, and related delivery events. Live activity is shared only when you enable buddy sharing and only with accepted buddies.
- **Push notification information:** An Apple Push Notification service device token and notification environment used to deliver buddy requests, confirmations, and cheers. The token identifies an app installation, not your Apple password or payment details.
- **AI Coach input:** Questions or workout requests you submit, together with the minimum relevant training and optional Health context needed to answer them.
- **Subscription information:** App Store product identifier, transaction identifier, subscription status, and expiration information. Apple handles payment details; Monster Remote does not receive your payment card number.
- **Alexa linking information:** Temporary linking codes and the Alexa account identifier used to route commands.
- **Diagnostics:** Logs and diagnostic reports when you choose to share them for support.
- **Optional unsupported-firmware archive:** If your Gym Monster runs an unsupported firmware and no archive is already available, the app may offer an explicit upload action. When you choose it, the Helper packages the installed firmware application, encrypts it before upload, and sends the encrypted archive plus firmware version, build fingerprint, size, and integrity hashes to private Cloudflare storage. A server-side reservation prevents routine duplicate uploads. This archive is used only to build Monster Remote compatibility support.

## How We Use Information

We use this information to:

- provide Progress analytics, training history sync, MCP access, AI Coach responses, workout drafts, and Training Buddies;
- keep your private Monster Remote account and subscription available across your Apple devices;
- verify App Store subscriptions and enforce fair-use limits;
- connect the app to a supported Gym Monster and route Alexa commands;
- deliver buddy requests, confirmations and cheers, and share live training status with accepted buddies when you enable sharing;
- analyze an encrypted unsupported-firmware archive when you explicitly choose to help add compatibility;
- prevent abuse, improve reliability, and troubleshoot problems.

Progress analytics remain available as deterministic, rule-based analysis and do not require an AI request. AI Coach data is sent only when you explicitly submit a question or workout request.

## Speech Input and Spoken Answers

If you use dictation or voice commands, speech recognition is provided through Apple's Speech framework. Monster Remote does not store raw microphone recordings. Recognized text entered into the AI Coach is sent to the AI service only after you submit it. Optional spoken answers are generated on your Apple device and can be disabled in the app.

For Alexa, Amazon handles the raw recording and speech recognition under Amazon's privacy terms. Monster Remote receives only the resulting command and any applicable amount.

## Cloud Sync, MCP, and AI

Monster Remote Intelligence is hosted on Cloudflare. Synced training and optional Health summaries are associated with your private account and protected by a bearer access key stored in the iOS Keychain. Treat this key like a password when adding the MCP server to another AI client.

When you use the built-in AI Coach, the submitted request and relevant context are processed by OpenAI to generate the response. Requests are made with API response storage disabled. Monster Remote stores operational metadata such as request status, token usage, latency, and a one-way prompt hash for quota enforcement and diagnostics; it does not store the full AI prompt in its request log.

An external MCP-compatible AI client that you choose to connect is governed by that provider's own privacy policy. Monster Remote cannot control how that external client processes information you ask it to retrieve.

## Data Storage and Retention

Cloud-synced training summaries and related account records are generally retained for up to 1,095 days while the service is in use, unless a longer period is legally required. Buddy relationships, sharing settings, device tokens and buddy events are retained while needed to provide the feature and are deleted with the cloud account, subject to short operational retention required for security and reliable delivery. Short-lived linking codes, upload reservations and authentication nonces expire automatically. Operational and entitlement records may be kept as needed for security, billing verification, fraud prevention, and legal compliance. Encrypted unsupported-firmware archives may be retained for ongoing compatibility research and are not used for advertising or user profiling.

On-device information, including the MCP access key in the iOS Keychain, remains until you remove the app data or use the relevant iOS controls. You can permanently delete your Monster Remote cloud account and its linked data inside the app's private-account settings. You may also contact us for help with deletion.

## Data Sharing

We do not sell personal information. Limited information is shared only with processors needed to provide the selected features, including:

- Apple for Sign in with Apple, Health permissions, speech recognition, push notifications, and App Store purchases;
- Cloudflare for hosting, database, private object storage, networking, and security;
- OpenAI when you submit an AI Coach request;
- Amazon when you choose to use the Alexa skill.

Accepted Training Buddies receive only the live training information you choose to share, such as that you are training, the current exercise or workout title, and the start time. They do not receive your complete training history, Apple Health information, AI Coach conversations, account email, subscription information, or machine credentials through the buddy feature.

We may disclose information when required by law or when necessary to protect users, the service, or our legal rights.

## Your Choices

You can use core local and rule-based features without enabling Apple Health, AI Coach, Training Buddies, Alexa, firmware upload, or an external MCP client. You can revoke Health and notification permissions, stop using speech input or spoken answers, disable buddy sharing, remove or decline buddy relationships, disconnect external clients, and delete your cloud account in the app.

## Security

We use reasonable technical and organizational safeguards, including encrypted network transport, hashed account identifiers, scoped access keys, replay protection, and server-side entitlement checks. No internet-connected service can be guaranteed completely secure.

## Children's Privacy

Monster Remote is not intended for children under 13. We do not knowingly collect personal information from children under 13.

## Changes to This Policy

We may update this policy as the app changes. Updates will be posted at this location with a revised effective date.

## Contact

For privacy questions or deletion requests, contact:

info@emudev.de
