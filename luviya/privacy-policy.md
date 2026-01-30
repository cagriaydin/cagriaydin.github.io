# Privacy Policy for Luviya

**Last Updated: [To be updated upon app publication]**

## Introduction

Welcome to Luviya ("we," "our," or "us"). We are committed to protecting your privacy and being transparent about how we collect, use, and safeguard your personal information. This Privacy Policy explains our data practices for the Luviya mobile application (the "App").

Luviya is an AI-powered numerology and spiritual guidance application that provides personalized insights based on your name and birthdate. We believe in data minimization and only collect information that is essential to provide you with meaningful spiritual guidance.

By using the App, you agree to the collection and use of information in accordance with this Privacy Policy.

## Information We Collect

### Personal Information You Provide

When you use Luviya, we collect the following personal information:

- **Name**: Your first name
- **Surname**: Your last name
- **Birthdate**: Your complete date of birth

This information is necessary for performing numerology calculations and generating personalized spiritual insights.

### Partner Information (Temporary)

For relationship compatibility analysis, you may optionally provide:

- **Partner's Name**
- **Partner's Birthdate**

**Important**: Partner information is sent to our AI service for analysis purposes only and is **not stored** in our databases. This data is processed temporarily and immediately discarded after generating your compatibility report.

### Authentication Data

We use Firebase Anonymous Authentication, which means:

- You do not need to provide an email address or phone number
- A unique anonymous User ID is automatically generated for your account
- No personally identifiable authentication credentials are required

### Device Information

To enable push notifications, we collect:

- **Firebase Cloud Messaging (FCM) Token**: A unique identifier for sending notifications to your device
- **Platform Type**: Whether you're using iOS or Android (for notification compatibility)

### Android Permissions

On Android devices, we request the following system permissions:

- **POST_NOTIFICATIONS**: Display push notifications for daily reminders
- **SCHEDULE_EXACT_ALARM** & **USE_EXACT_ALARM**: Schedule daily notifications at your preferred time
- **RECEIVE_BOOT_COMPLETED**: Restart scheduled notifications after device reboot
- **VIBRATE**: Enable notification vibration
- **WAKE_LOCK**: Wake device to deliver time-sensitive notifications

You can manage these permissions through your device settings at any time.

### Information We Do NOT Collect

We want to be clear about what we **do not** collect:

- ❌ Email addresses or phone numbers
- ❌ Location data or GPS coordinates
- ❌ Browsing history or app usage analytics
- ❌ Device identifiers (IMEI, MAC address, etc.)
- ❌ Payment information (the App is currently free)
- ❌ Contact lists or address books
- ❌ Photos, videos, or other media files
- ❌ Behavioral tracking or user profiling data

## How We Use Your Information

We use the information we collect for the following purposes:

### Numerology Calculations
- Calculate your daily energy number based on your birthdate
- Determine your core soul numbers (Soul Drive, Life Path, Expression, Intuition)
- Analyze element balance (Fire, Water, Air, Earth)
- Generate career path insights

### Personalized Content Generation
- Create daily spiritual guidance and affirmations using Google Gemini AI
- Generate personalized numerology interpretations
- Provide relationship compatibility analysis (when requested)
- Deliver career recommendations based on your numerological profile

### Service Delivery
- Maintain your user profile for consistent personalized experiences
- Enable account management and settings preferences
- Cache AI-generated content locally for faster loading and offline access

### Push Notifications
- Send daily energy reminders (if you enable notifications)
- Deliver important app updates and announcements

### Language Preferences
- Remember your preferred language (Turkish or English)
- Provide localized content and user interface

## Third-Party Services and Data Sharing

We use the following third-party services to operate the App. Your data may be processed by these services:

### Firebase Services (Google LLC)

**Firebase Authentication**
- Purpose: Anonymous user authentication
- Data Processed: Anonymous User ID
- Privacy Policy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

**Cloud Firestore**
- Purpose: Store your user profile and notification tokens
- Data Processed: Name, surname, birthdate, User ID, FCM tokens
- Location: Data is stored on Google Cloud servers
- Privacy Policy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

**Firebase Cloud Messaging**
- Purpose: Deliver push notifications
- Data Processed: FCM tokens, notification content
- Privacy Policy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### Google Gemini AI (Firebase AI)

**Purpose**: Generate personalized numerology interpretations and spiritual guidance

**Data Processed**: Your name, surname, birthdate, and (temporarily) partner information for compatibility analysis

**Important Note**: Your personal data (name, surname, birthdate, and partner information for compatibility analysis) is transmitted to Google's Gemini AI service for content generation. This data is processed according to Google's AI Principles and Privacy Policy. AI-generated responses are cached locally on your device and in cloud storage for performance optimization. Each cached response is associated with your User ID.

**Privacy Policy**: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

### Google Fonts

**Purpose**: Display beautiful, custom typography in the App
**Data Processed**: Font files are fetched from Google's servers; minimal technical data (e.g., IP address) may be logged by Google
**Privacy Policy**: [https://developers.google.com/fonts/faq/privacy](https://developers.google.com/fonts/faq/privacy)

### Data Sharing Policy

We do **not** sell, rent, or trade your personal information to third parties for marketing purposes. Data is only shared with the third-party services listed above, and only to the extent necessary to provide App functionality.

## Data Storage and Security

### Cloud Storage (Firebase Firestore)

Your user profile (name, surname, birthdate, User ID) and notification tokens are stored securely in Google Cloud Firestore with:
- Industry-standard encryption in transit (HTTPS/TLS)
- Encryption at rest on Google's servers
- Access controls and authentication requirements

### Local Storage (Hive)

The following data is cached locally on your device for performance and offline access:
- Your user profile (for offline viewing)
- AI-generated content (daily insights, soul number interpretations)
- App preferences (notification settings, language preference)

Local data is stored using the Hive database, which keeps data in your device's secure application storage folder.

### Security Measures

We implement reasonable security measures to protect your information, including:
- Secure HTTPS connections for all network communications
- Firebase security rules to restrict unauthorized data access
- Anonymous authentication to minimize personal data exposure
- Regular security updates to third-party dependencies

However, no method of transmission over the internet or electronic storage is 100% secure. While we strive to protect your personal information, we cannot guarantee absolute security.

## Data Retention and Deletion

### Retention Period

We retain your personal information only as long as necessary to provide you with App services:

- **Active Users**: Your data is retained while your account is active
- **Cached Content**: AI-generated content is cached until it expires or you clear it
- **Notification Tokens**: Retained until you disable notifications or delete your account

### Data Deletion

You have the right to delete your data at any time:

**Immediate Deletion**: When you delete your account through the App settings, we immediately:
1. Delete your user profile from Cloud Firestore
2. Delete all notification tokens from our database
3. Clear all locally cached data from your device
4. Clear all AI-generated content caches

**How to Delete Your Account**:
1. Open the App and go to Profile
2. Tap on Settings
3. Scroll to "Account Management"
4. Tap "Delete Account"
5. Confirm the deletion

After deletion, your data cannot be recovered. If you wish to use the App again, you will need to create a new profile.

## Your Privacy Rights

Depending on your location, you may have specific privacy rights:

### Rights Under GDPR (European Union Users)

If you are located in the European Union, you have the following rights:

- **Right to Access**: Request a copy of the personal data we hold about you
- **Right to Rectification**: Request correction of inaccurate or incomplete data
- **Right to Erasure**: Request deletion of your personal data (see "Data Deletion" above)
- **Right to Restrict Processing**: Request that we limit how we use your data
- **Right to Data Portability**: Receive your data in a structured, machine-readable format
- **Right to Object**: Object to certain types of data processing
- **Right to Withdraw Consent**: Withdraw your consent at any time

### Rights Under CCPA (California Users)

If you are a California resident, you have the right to:

- **Know**: Request information about the personal data we collect, use, and disclose
- **Delete**: Request deletion of your personal data
- **Opt-Out**: Opt-out of the "sale" of your personal data (Note: we do not sell personal data)
- **Non-Discrimination**: Not receive discriminatory treatment for exercising your privacy rights

### Rights Under KVKK (Turkey Users)

If you are located in Turkey, you have the right to:

- Learn whether your personal data is being processed
- Request information about data processing
- Learn the purpose of data processing and whether it is used appropriately
- Know third parties to whom your data is transferred
- Request correction of incomplete or inaccurate data
- Request deletion or destruction of data under certain conditions
- Object to automated processing that produces legal effects

### How to Exercise Your Rights

To exercise any of these rights, please contact us at **cagriaydin.dev@gmail.com** with:
- The subject line: "Privacy Rights Request - Luviya"
- Your User ID (found in Profile > Settings)
- A description of your request

We will respond to your request within 30 days.

## Children's Privacy

The App is rated 13+ and is intended for users aged 13 years and older.

We do not knowingly collect personal information from children under 13 years of age. If you are under 13, you may not use the App. If you are a parent or guardian and believe your child under 13 has provided us with personal information, please contact us at **cagriaydin.dev@gmail.com**, and we will delete the information immediately.

## International Data Transfers

Your personal data may be transferred to and processed in countries other than your country of residence, specifically:

- **United States**: Google's Firebase and Cloud services operate globally, including in the U.S.
- **European Union**: Data may also be processed in Google's EU data centers

These transfers are necessary to provide the App services. Google complies with applicable data protection frameworks and provides adequate safeguards for international data transfers.

## Push Notifications

We use Firebase Cloud Messaging to send push notifications:

### What We Send
- Daily energy reminders (configurable in settings)
- Important app updates or announcements

### Your Control
- You can enable or disable notifications at any time in the App settings
- You can also manage notification permissions through your device's system settings
- Disabling notifications does not affect other App functionality

### Data Collection
- We collect FCM tokens to identify your device for notification delivery
- We do not track whether you open or interact with notifications

## Analytics and Tracking

**Important**: Luviya does **not** use analytics or tracking services.

We do not collect:
- Usage statistics
- User behavior analytics
- Event tracking
- Crash reporting with user identifiable data
- Marketing or advertising data

This is intentional. We believe in your privacy and do not need to track how you use the App.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or legal requirements. When we make changes:

1. We will update the "Last Updated" date at the top of this policy
2. For material changes, we will notify you through the App or via push notification
3. Continued use of the App after changes constitutes acceptance of the updated policy

We encourage you to review this Privacy Policy periodically.

## Data Breach Notification

In the unlikely event of a data breach that affects your personal information, we will:
1. Notify affected users within 72 hours of discovering the breach
2. Describe the nature of the breach and data involved
3. Provide guidance on protective measures you can take
4. Report the breach to relevant authorities as required by law

## Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**Email**: cagriaydin.dev@gmail.com  
**Developer**: Cagri Aydin  
**Address**: Turkey  
**Subject Line**: Privacy Inquiry - Luviya App  
**Response Time**: We aim to respond within 48 hours

For privacy rights requests or data deletion, please include your User ID (found in Profile > Settings) in your message.

---

## Summary (TL;DR)

- ✅ We collect only essential information: name, surname, and birthdate
- ✅ Anonymous authentication—no email or phone required
- ✅ Partner data is processed temporarily but never stored
- ✅ No analytics, tracking, or behavioral monitoring
- ✅ Data is deleted immediately upon request
- ✅ We use Firebase (Google) and Gemini AI for service delivery
- ✅ You have full rights to access, correct, and delete your data
- ✅ Compliant with GDPR, CCPA, and KVKK regulations

Thank you for trusting Luviya with your spiritual journey. 🌟
