# Privacy Policy — OmniPlay Mobile

**Last updated:** May 23, 2026
**Version:** 1.0

## 1. Who we are

This Privacy Policy describes how **Internet Play Ltda**, registered under CNPJ 09.356.818/0001-16, headquartered in [city/state, Brazil], hereinafter referred to as "**Netplay**" or "**we**", collects, uses, stores, and protects the personal data of users of the **OmniPlay** mobile application (hereinafter "**Application**") when used in a professional context as a support agent working at a company that subscribes to the OmniPlay platform.

Netplay acts as a **data processor** for end-customer personal data (the contacts who receive support), while the **data controller** for that data is the client company that uses the OmniPlay platform to provide customer support. For data related to support agents themselves (you, the Application user), Netplay acts as the **data controller**.

This Policy complies with Brazil's **General Data Protection Law (Lei nº 13.709/2018 — LGPD)** and incorporates principles from the **GDPR** for international users.

## 2. Who can use the Application

OmniPlay Mobile is a corporate omnichannel customer service tool intended exclusively for **professional support agents** working at companies that have subscribed to the OmniPlay platform. The Application is **not intended** for end consumers nor for users under 18.

To use the Application, you must have corporate credentials provided by the administrator of the company you work for.

## 3. What data we collect

### 3.1. Data you provide directly

- **Authentication data:** corporate email and password.
- **Profile data:** name, profile photo (optional), associated company(ies), and role.
- **Support content:** text messages, photos, videos, audio, documents, locations, and contacts that you send or receive through the configured channels (WhatsApp Business API, Instagram, Facebook Messenger, email, live chat, etc.).

### 3.2. Data collected automatically

- **Push notification token:** unique identifier assigned by Apple Push Notification Service (APNs) or Firebase Cloud Messaging (FCM), associated with your device. Used to deliver new message notifications.
- **Device identifier:** model, operating system, and app version — used exclusively for technical diagnostics.
- **Operational usage data:** records of which tickets you opened, messages sent, and actions performed — necessary for audit trails, metrics, and platform business rules.
- **Presence status:** "online" / "typing" / "last active" indicator visible to other users in the same company.

### 3.3. Data we DO NOT collect

- We do not use third-party analytics tools (Google Analytics, Facebook Pixel, Mixpanel, etc.).
- We do not track your activity outside the Application.
- We do not access your contacts, photos, microphone, camera, or location without your explicit action (see Section 5).
- We do not sell your data to third parties.

## 4. How we use your data

| Purpose | Legal basis (LGPD Art. 7º/11) |
|---|---|
| Authenticate you and keep your session active | Contract performance |
| Deliver real-time messages (push, in-app) | Contract performance |
| Distribute and assign tickets per company rules | Contract performance |
| Store ticket history for later consultation | Contract performance + legal obligation |
| Diagnose technical errors and improve the app | Legitimate interest |
| Comply with legal obligations (tax, regulatory) | Legal compliance |

## 5. Device permissions

The Application requests the following permissions on iOS. All have justified use:

| Permission | Purpose | When requested |
|---|---|---|
| **Camera** | Take a photo to attach to a ticket | When tapping "Attach → Camera" |
| **Photos (library)** | Select photo/video from gallery to send | When tapping "Attach → Gallery" |
| **Save photos** | Save media received from customers | When tapping "Save to gallery" |
| **Microphone** | Record an audio message | When holding the microphone button |
| **Location (when in use)** | Share current location with a customer | When tapping "Attach → Location" |
| **Contacts** | Select contact to share with a customer | When tapping "Attach → Contact" |
| **Face ID / Touch ID** | Protect app access (optional) | When enabling biometric lock in Profile |
| **Notifications** | Alert about new messages | On first login |

You can revoke any permission at any time in **iOS Settings → OmniPlay**.

## 6. Push notifications

When you enable notifications, the Application registers a unique token from your device on OmniPlay servers. This token is used **exclusively** to deliver new message notifications via Apple Push Notification Service (APNs) — operated by Apple Inc.

The token is automatically discarded when you log out or uninstall the app. You can disable all notifications in **Profile → Notifications → App notifications**.

## 7. Who we share your data with

Netplay **does not sell** personal data. We share data only with:

- **Your employer company:** all ticket data is accessible by the OmniPlay client company according to the permissions and roles configured.
- **Infrastructure providers:** Apple Inc. (push notifications via APNs), Meta Platforms Inc. (sending/receiving messages via WhatsApp Business API), cloud hosting providers for media storage. All these providers have contractual data protection clauses.
- **Public authorities:** upon a court order or binding legal request.

## 8. Where your data is stored

Data is stored on servers located in **Brazil**, on infrastructure compliant with LGPD. Some specific operations may involve international transfer (e.g., push delivery via APNs/Apple) — always under conditions that respect data subject rights.

## 9. How long we retain data

- **Active authentication data:** as long as your account is active with the client company.
- **Ticket history:** per the retention policy of the client company (configurable by admin), with a minimum of 6 months for tax obligations when applicable.
- **Push notification token:** discarded within 24h after logout or extended inactivity.
- **Technical logs:** retained for up to 90 days for diagnostics, then anonymized or discarded.

## 10. Your rights as a data subject (LGPD Art. 18 / GDPR Art. 12-22)

You have the right, at any time, to:

- **Confirm** the existence of data processing
- **Access** your personal data
- **Correct** incomplete, inaccurate, or outdated data
- **Anonymize, block, or delete** unnecessary data or data processed in non-compliance
- **Request portability** of your data
- **Delete** data processed based on consent
- **Withdraw consent** previously provided
- **Obtain information** about who we share your data with

To exercise any of these rights, contact **dpo@netplay.net.br** or the web panel at **Profile → Privacy**. We will respond within 15 days.

## 11. Security

We implement technical and organizational measures to protect your data:

- **Encryption in transit:** all communications use HTTPS/TLS 1.2+.
- **Encryption at rest:** authentication tokens are stored in Apple Keychain (Secure Enclave). Production databases use AES-256 encryption.
- **Authentication:** passwords stored with bcrypt. Biometric authentication support (Face ID/Touch ID) on device.
- **Access control:** granular role and permission system with audit logging of sensitive actions.
- **Continuous monitoring:** anomaly detection, daily backups, and continuity plan.

## 12. Cookies and similar technologies

The mobile Application **does not use cookies**. It uses local storage (AsyncStorage and iOS SecureStore) exclusively to:
- Keep your session active
- Remember your preferences (theme, notifications, language)
- Local message cache for offline use

## 13. Changes to this Policy

We may update this Policy periodically. When there are significant changes, you will be notified:
- By email (to the registered corporate account)
- By in-app notice on the next opening

The latest version will always be available at **julianotarga.github.io/omniplay-privacy**.

## 14. Data Protection Officer (DPO)

**Data Protection Officer:** [DPO Name]
**Email:** dpo@netplay.net.br
**Address:** [Netplay Address]

## 15. Brazilian Data Protection Authority (ANPD)

You have the right to file a complaint with the ANPD regarding the processing of your data by OmniPlay. More information at **www.gov.br/anpd**.

## 16. Contact

For any questions about this Policy or about the processing of your data:

- **Email:** privacy@netplay.net.br
- **General support:** support@netplay.net.br
- **Website:** omni.netplay.net.br/landing
