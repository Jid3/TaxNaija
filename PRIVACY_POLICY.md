# Privacy Policy for TaxNaija: Nigerian Tax Calculator

Effective Date: 1 April 2026
Last Updated: 1 April 2026 
App Name: TaxNaija: The Nigerian Tax Calculator 
Developer: Jide Dev (com.jideDev.taxnaija) 
Contact: taxcalculatorng@gmail.com

# Disclaimer
TaxNaija: The Nigerian Tax Calculator is not a product of, nor affiliated with, the Nigerian Government. All tax information and calculations within the app are sourced from the publicly available Nigeria Tax Act, 2025 (https://www.nrs.gov.ng/uploads/NIGERIA_TAX_ACT_2025_ef6bb812a5.pdf).
Users are advised to consult a certified legal or financial adviser before making any financial decision. This app is a tool to help you quickly estimate and keep track of your taxable income — it does not constitute professional tax or legal advice.

# Introduction
Welcome to TaxNaija, a Nigerian personal and business income tax calculator designed to help individuals and businesses estimate their tax obligations under the 2026 Nigeria Tax Act.
We are committed to protecting your privacy. This Privacy Policy explains what information the App collects, how it is stored, and how it is used. By downloading or using TaxNaija, you agree to the practices described in this policy.

## Information We Collect
Financial Data You Enter
TaxNaija is an offline-first application. All financial information you enter is processed entirely on your device and is never transmitted to our servers. The following data is entered and stored locally on-device only:

## Data	Purpose
Gross income (monthly / weekly / annual)	Tax calculation
Pension contributions	Tax relief calculation
National Housing Fund (NHF) contributions	Tax relief calculation
NHIS contributions	Tax relief calculation
Life insurance premiums	Tax relief calculation
Annual rent paid	Tax relief calculation
Business turnover & business type	Business tax calculator
Company size	Business tax calculator
Custom deduction names and amounts	Tax calculator
Daily income and expense entries	Calendar tracker
Saved tax calculation history	My Taxes tab

## Security Credentials
If you enable the App Lock feature, the following is stored only on your device using the platform's hardware-backed secure storage:

A SHA-256 hashed version of your 6-digit PIN — your raw PIN is never stored anywhere
Your biometric unlock preference (an on/off flag only)
Your auto-lock timeout preference (stored in AsyncStorage)

## Notification Preferences
If you enable daily reminders, the App stores your chosen reminder times locally on your device. No notification content or schedule data is transmitted to external servers.

# Advertising Data (Google AdMob)
TaxNaija displays advertisements through Google AdMob. AdMob may automatically collect certain data from your device, including but not limited to:

Device identifiers (e.g., Android Advertising ID / iOS IDFA)
IP address
General device and OS information
App usage and interaction data
This data is collected and processed by Google LLC under their own privacy policy. We do not have access to or control over this data.

Google's Privacy Policy: https://policies.google.com/privacy
AdMob's policies: https://support.google.com/admob/answer/6128543
To opt out of personalised advertising:
Android: Settings → Google → Ads → Delete advertising ID (Android 12+), or opt out of Ads Personalisation

# How We Use Your Information
Purpose >>	Legal Basis

Performing tax calculations on your device >>	Providing the service you requested
Storing your calculation history >>	Your explicit "Save" action within the app
Sending daily tax reminder notifications >>	Your explicit notification settings
Locking the app with a PIN or biometrics >>	Your explicit security settings
Displaying in-app advertisements >>	AdMob's consent and interest-based advertising framework
We do not use your financial data for any purpose other than performing calculations locally on your device.

# Data Storage
## On-Device Storage (AsyncStorage)
All user-entered financial data — including tax calculations, calendar entries, and history — is stored locally on your device using React Native's AsyncStorage. This data:

Never leaves your device via our systems
Is accessible only within the TaxNaija app
Is permanently deleted when you uninstall the App

## Secure Storage (Hardware-Backed)
Your hashed PIN and biometric preferences are stored using Expo SecureStore, which is backed by:

Android: The Android Keystore system (hardware-backed)
These cannot be read by other apps on your device.

## Clipboard Protection
As a security measure, TaxNaija automatically clears your device clipboard whenever the App moves to the background. This prevents sensitive financial figures you may have copied from being accessible to other applications.

## Data Sharing
We do not sell, rent, trade, or transfer your personal or financial information to any third parties.

The only third party that may receive limited, automatically-collected technical data from your device is Google AdMob, solely for the purpose of serving advertisements (see Section 2.4 above).

# Permissions Requested
Permission ||	Platform ||	Reason
USE_BIOMETRIC / USE_FINGERPRINT ||	Android ||	To allow fingerprint unlock of the app
Face ID || iOS ||	To allow Face ID unlock of the app
POST_NOTIFICATIONS ||	Android 13+ ||	To send you daily tax reminder notifications (only if you choose to enable them)

TaxNaija does not request or use access to your contacts, camera, microphone, location, files, or any other device data beyond those listed above.

# Children's Privacy
TaxNaija is not directed at or intended for use by children under the age of 13 (or 16 in the European Union / United Kingdom). We do not knowingly collect personal information from children. If you believe a child has provided information through this App, please contact us at taxcalculatorng@gmail.com and we will take appropriate steps.

## Data Retention
Because all data is stored locally on your device, retention is entirely in your control:

Data Category ||	Retained Until
Tax calculations and history	|| You delete individual records in the app, or uninstall the App
Calendar income/expense entries	|| You delete the entries, or uninstall the App
Security credentials (hashed PIN, biometrics setting)	|| You disable App Lock in Settings, or uninstall the App
Notification preferences	|| You remove reminder times in Settings, or uninstall the App

# Your Rights
Depending on your jurisdiction, you may have the right to:

Access your data — viewable directly within the App (My Taxes, Calendar, Settings)
Delete your data — by clearing records within the App or uninstalling it
Opt out of personalised advertising — see Section 2.4
Withdraw consent for notifications — by removing reminder times in Settings or revoking notification permission in your device settings
Since all data is stored exclusively on your device and we hold no server-side copy, all data requests can be fulfilled directly through App settings and your device's app management tools.

# Security Measures
We implement the following security measures within the App:

PIN hashing: Your 6-digit PIN is hashed with SHA-256 before storage. The raw PIN is never persisted anywhere.
Hardware-backed secure storage: Security credentials are stored in the platform's hardware secure enclave (iOS Keychain / Android Keystore) via Expo SecureStore.
Auto-lock: The App automatically locks after a configurable inactivity period of 1, 5, or 10 minutes.
Clipboard clearing: The clipboard is automatically wiped each time the App enters the background.
No financial data transmission: No financial data you enter into TaxNaija is transmitted to any external server by our application.
Despite these measures, no method of electronic storage is 100% secure. We encourage you to enable App Lock and keep your device's operating system and security software up to date.

# Third-Party Services
Service	Purpose	Privacy Policy
Google AdMob	Displaying in-app advertisements	https://policies.google.com/privacy
Expo (EAS)	App build and distribution infrastructure	https://expo.dev/privacy

# Changes to This Policy
We may update this Privacy Policy from time to time to reflect changes in the App or applicable laws. Any changes will be posted to this document with an updated "Last Updated" date at the top. Continued use of the App after changes are posted constitutes your acceptance of the revised policy. We encourage you to review this policy periodically.

# Contact Us
If you have any questions, concerns, or requests relating to this Privacy Policy or TaxNaija's data practices, please contact:

Developer: Jide Dev Email: taxcalculatorng@gmail.com
GitHub: https://github.com/Jid3/TaxCalculatorNG

This privacy policy was prepared based on the technical implementation of TaxNaija v1.8.0. It is provided for informational purposes only and does not constitute legal advice. You should consult a qualified legal professional to ensure this policy complies with all laws and regulations applicable in your jurisdiction, including but not limited to the Nigeria Data Protection Act (NDPA) 2023, GDPR (if applicable), and Google Play / App Store requirements.
