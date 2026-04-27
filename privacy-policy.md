# Privacy Policy — Money Lens

  **Last updated: April 27, 2026**

  Money Lens ("we", "our", or "the app") is a personal finance app that reads
  bank transaction SMS to help you understand your spending. This Privacy Policy
  explains what data we collect, how we use it, and your rights.

  By using Money Lens, you agree to the practices described in this policy.

  ---

  ## 1. Information We Collect

  ### a) Account information
  When you create an account, we collect your **email address**. This is used
  solely for authentication and to associate your transaction data with your
  account.

  ### b) Transaction data
  We extract structured records from your bank SMS messages, including:
  - Merchant or payee name
  - Transaction amount
  - Transaction date
  - Spending category

  This structured data is stored on our servers to power your spending insights,
  daily summaries, and monthly reports.

  ### c) Bank message text (selected messages)
  For a small number of transactions where the merchant cannot be identified
  automatically, we store and process the original bank message text using an
  AI-powered categorisation service. Only messages from recognised bank and
  financial institution senders are ever processed — we never read or store
  personal messages, OTPs, or SMS from non-financial senders.

  ### d) Device token
  We collect a Firebase Cloud Messaging (FCM) registration token from your device
  to deliver push notifications. This token is stored on our servers and rotated
  automatically by the Firebase SDK.

  ---

  ## 2. How We Use Your Information

  | Data | Purpose |
  |---|---|
  | Email address | Account authentication |
  | Transaction records | Spending insights, daily and monthly summaries |
  | Bank message text | Merchant identification, spending categorisation |
  | FCM token | Push notifications (daily summary, monthly report) |

  We do **not** use your data for advertising, profiling, or any purpose beyond
  providing the features described above.

  ---

  ## 3. SMS Access

  Money Lens requests permission to read SMS messages on your device. We use
  this access to detect and parse bank transaction messages in real time and from
  your recent inbox (last 90 days at first launch).

  We apply strict sender filters: only messages from known bank and financial
  institution sender IDs are read. Personal conversations, OTPs, and messages
  from non-financial senders are never accessed or stored.

  This permission is used solely to provide the core functionality of the app —
  automatic expense tracking. Without it, the app cannot function.

  ---

  ## 4. AI-Powered Categorisation

  To identify merchants and categorise spending automatically, we use an
  AI-powered service. When a transaction cannot be categorised from our local
  rules, the bank message text is sent to this service for analysis.

  - Only bank transaction messages are sent (never personal SMS)
  - The content is used solely to produce a merchant name and spending category
  - It is not used for advertising, training third-party AI models, or profiling
  - All communication with the AI service is encrypted in transit

  ---

  ## 5. Third-Party Services

  ### Firebase Cloud Messaging (Google)
  We use Firebase Cloud Messaging to deliver push notifications. Firebase may
  collect device identifiers as part of this service. For details, see
  [Google's Privacy Policy](https://policies.google.com/privacy).

  We do not integrate any advertising SDKs, analytics platforms, or other
  third-party data processors beyond those listed above.

  ---

  ## 6. Data Storage and Security

  - All data is transmitted over encrypted HTTPS connections
  - Transaction data is stored on our servers and is accessible only by you
  - We do not sell, rent, or share your data with any third party for commercial
    purposes
  - We retain your data for as long as your account is active

  ---

  ## 7. Data Retention

  We keep your account and transaction data for as long as you use the app. If
  you request deletion (see Section 8), we will permanently remove your data
  within **7 days**.

  ---

  ## 8. Your Rights

  You have the right to:

  - **Access** your data — your spending history is visible in the app at all times
  - **Delete** your account and all associated data — see below

  ### How to request data deletion

  Send an email to **moneylensapp@gmail.com** with the subject line
  **"Data Deletion Request – Money Lens"** and include the email address
  registered to your account. We will confirm and permanently delete your data
  within 7 days.

  ---

  ## 9. Children's Privacy

  Money Lens is not directed at children under 13 years of age. We do not
  knowingly collect personal information from children. If you believe a child
  has provided us with personal data, please contact us and we will delete it
  promptly.

  ---

  ## 10. Changes to This Policy

  We may update this Privacy Policy from time to time. When we do, we will
  update the "Last updated" date at the top of this page. Continued use of the
  app after changes are posted constitutes your acceptance of the updated policy.

  ---

  ## 11. Contact Us

  If you have any questions, concerns, or requests regarding this Privacy Policy
  or your data, please contact us:

  **Email:** moneylensapp@gmail.com

  ---

  *Money Lens is an independent app. It is not affiliated with any bank or
  financial institution.*

  ---
