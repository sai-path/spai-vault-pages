# Privacy Policy for SPAI Vault

**Last updated:** March 2026

**Effective date:** March 2026

---

## 1. Introduction

SPAI Vault ("the App") is a document storage and organization app that helps you keep copies of important documents (such as passports, licenses, and IDs) secure on your device. This Privacy Policy explains how the App handles your information.

**We do not collect, transmit, or sell your personal data.** All document data and app data stay on your device unless you explicitly share or export it.

---

## 2. Who We Are

SPAI Vault is an iOS application. For the purposes of this policy, "we," "us," and "our" refer to the developer(s) of SPAI Vault. You can reach out via the support or contact options provided in the App or on the App’s project page (e.g., GitHub).

---

## 3. Information We Do Not Collect

- We do **not** collect your name, email, phone number, or other contact information.
- We do **not** collect the contents of your documents, photos, or any data you store in the App.
- We do **not** use analytics, tracking, or advertising SDKs that would collect your usage data.
- We do **not** transmit your documents or vault data to our servers (the App has no backend server for your document storage).

---

## 4. Information Stored Only on Your Device

All of the following stay **only on your device** (and, where applicable, in your iCloud backup if you have enabled it for the app):

### 4.1 Document and Vault Data

- **Document images and metadata** (e.g., document type, name, number, expiry date) that you add to the App are stored locally on your device.
- **Encryption:** Document data is encrypted on device using keys stored in the iOS Keychain. We use industry-standard encryption (CryptoKit) to protect your vault contents.

### 4.2 Profile and App Usage Data

- **Profiles:** Names and avatar choices for profiles (e.g., family members) are stored locally.
- **Preferences:** Settings such as theme (e.g., light/dark), onboarding completion, and custom reminder intervals are stored locally (e.g., using UserDefaults).
- **In-app purchases:** If you make optional in-app purchases (e.g., tips), Apple may process the transaction. We do not receive or store your payment details; we only receive standard App Store purchase notifications as provided by Apple (e.g., to unlock or acknowledge a tip). Any record of “purchased” tips may be stored locally on your device so the App can show the correct state.

### 4.3 Biometric and Device Security

- **Biometric authentication:** The App uses Face ID or Touch ID to unlock access. Biometric data is handled entirely by iOS; we do not receive, store, or transmit your face or fingerprint data.
- **Keychain:** Encryption keys used to protect your vault are stored in the iOS Keychain with access restricted to when the device is unlocked (`kSecAttrAccessibleWhenUnlockedThisDeviceOnly` or equivalent), in line with Apple’s security guidelines.

---

## 5. Notifications

- The App can schedule **local notifications** (e.g., document expiry reminders) on your device. These are created and stored only on your device and are not sent to or processed by our servers.

---

## 6. When Data Might Leave Your Device

Your data may leave your device only in these cases:

- **You choose to share:** If you use the App’s share or export features (e.g., sharing a document image), the data you select is shared according to your choice (e.g., to another app or contact). We do not control or receive that data after you share it.
- **Apple services:** Your use of the App is subject to Apple’s terms and privacy policy. For example:
  - **iCloud Backup:** If you back up your device (including the App) to iCloud, Apple may store that backup according to its policies.
  - **App Store and in-app purchases:** Downloads and purchases are processed by Apple; their privacy policy applies to that processing.
- **Legal requirement:** We may be required to disclose information if a valid legal process (e.g., court order) compels us to do so. Because we do not collect or hold your document data on our systems, we would only be able to respond to the extent we possess relevant information (e.g., what is stored on a device we control, which for a local-only app is typically none of your vault content).

---

## 7. Children’s Privacy

The App is not directed at children under 13. We do not knowingly collect personal information from children. If you believe a child has provided information through the App, please contact us and we will work to remove it in line with applicable law (noting that we do not maintain a central database of user data).

---

## 8. Data Security

- Document and vault data are encrypted on device.
- Access to the vault is protected by biometric authentication (Face ID / Touch ID) when enabled.
- Encryption keys are stored in the iOS Keychain with strong access controls.
- We do not transmit your documents or vault contents over the internet to our own servers.

You are responsible for keeping your device and Apple ID secure (e.g., passcode, not sharing device access).

---

## 9. Your Rights and Choices

- **Access and deletion:** Because all data is stored on your device, you can:
  - **Delete data:** Remove documents and profiles from within the App, or delete the App to remove all app data from the device (subject to your backup settings).
  - **Stop using the App:** Simply uninstall it; no account or server-side profile exists to delete.
- **Notifications:** You can disable notifications for the App in iOS Settings at any time.
- **Biometrics:** You can disable Face ID / Touch ID for the App in iOS Settings if you prefer not to use biometric unlock.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. The "Last updated" and "Effective date" at the top will be revised when we do. For significant changes, we may provide additional notice (e.g., in the App or on the App’s website/GitHub page). Continued use of the App after the effective date of changes constitutes acceptance of the updated policy.

---

## 11. Contact

If you have questions about this Privacy Policy or the App’s data practices, please contact us through the support or contact channel linked in the App or on the SPAI Vault project page (e.g., GitHub repository or linked website).

---

*This Privacy Policy is intended to be clear and accurate for use when hosting the policy on a site such as GitHub Pages. It is not legal advice; consider having it reviewed by a lawyer for your jurisdiction and use case.*
