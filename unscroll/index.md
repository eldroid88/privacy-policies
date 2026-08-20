# Privacy Policy for ScrollPace

**Effective date: August 20, 2026**

ScrollPace is an Android digital wellbeing application published by **Eldroid Apps**, an independent developer.

This Privacy Policy explains what information ScrollPace accesses, processes, stores, and shares.

For privacy questions, contact:

**Eldroid Apps**  
**Email:** eldroid.apps@gmail.com

## 1. Overview

ScrollPace helps users manage time spent in a selected application. When a chosen daily limit is reached, ScrollPace can offer a walking challenge that unlocks additional usage time.

Most wellbeing and usage information is processed and stored locally on the user's device.

ScrollPace does not require an account and does not ask for a user's name, email address, contacts, messages, passwords, photos, precise location, or payment information.

ScrollPace uses Firebase Analytics and Firebase Crashlytics for application analytics and technical diagnostics.

## 2. Information stored locally

ScrollPace processes and stores the following information locally on the user's device:

- Package name and display name of the application selected for protection
- Selected daily usage limit
- Days on which protection is active
- Time spent using the protected application
- Daily and recent usage history
- Walking challenge progress and completion
- Earned bonus time
- Challenge-related events and timestamps
- Onboarding completion state
- Technical state indicating whether the Accessibility Service is connected

This information is stored using Android DataStore or private application preferences.

ScrollPace does not intentionally transmit this local wellbeing information to Eldroid Apps, Firebase Analytics, Firebase Crashlytics, advertisers, or data brokers.

Android backup is disabled for ScrollPace.

## 3. Installed applications

ScrollPace accesses the list of launchable applications installed on the device so that the user can select an application to protect.

The installed application list is:

- Read and processed locally
- Displayed only in the application picker
- Not uploaded to Eldroid Apps or Firebase
- Not used for advertising

Only the application selected by the user is stored locally as the protected application.

## 4. Accessibility Service

ScrollPace uses the Android AccessibilityService API to provide its core digital wellbeing functionality.

ScrollPace is **not an accessibility tool** and does not claim that its primary purpose is to assist users with disabilities.

### Information accessed

The Accessibility Service observes Android window-change events and accesses the package identity of the application currently visible in the foreground.

ScrollPace compares that identity with the application selected by the user for protection.

### How this information is used

Foreground application identity is used only to:

- Detect when the selected protected application is open
- Measure how long it remains in the foreground
- Compare usage against the user's selected daily limit
- Display a wellbeing challenge when the limit is reached
- Stop counting when another application becomes active

Only the selected protected application's identity and usage information are stored locally.

### What the Accessibility Service does not do

ScrollPace does not use Accessibility access to:

- Read messages or notifications
- Read or collect passwords
- Inspect screen text or content
- Monitor keyboard input or typed text
- Capture screenshots
- Record audio
- Perform clicks, gestures, or actions on the user's behalf
- Change device settings
- Control other applications
- Make autonomous decisions
- Collect unrelated user information

Information obtained through Accessibility access is not shared with Firebase, advertisers, data brokers, or other third parties.

### Consent and user control

Before directing the user to Android Accessibility settings, ScrollPace displays a separate in-app disclosure explaining:

- What information is accessed
- Why the information is needed
- How the information is used
- That the information is stored locally
- That the information is not shared with third parties

The user must affirmatively confirm consent before continuing to Android Accessibility settings.

Accessibility access is optional and may be declined or revoked at any time through Android settings. Protection and foreground usage tracking will not function while the service is disabled.

## 5. Physical activity and step information

ScrollPace may request Android's `ACTIVITY_RECOGNITION` permission.

This permission is used during walking challenges to receive step information from the device's step detector or step counter sensor.

Step information is used to:

- Display walking challenge progress
- Determine when a challenge is completed
- Award additional protected-app usage time

ScrollPace does not use GPS and does not collect precise or approximate location data.

Walking challenge information is processed locally and is not intentionally sent to Firebase Analytics or Firebase Crashlytics.

The user may deny or revoke physical activity permission through Android settings. Walking challenges may not function without this permission.

## 6. Firebase Analytics

ScrollPace uses Google Analytics for Firebase to understand general application usage.

Analytics collection starts automatically when the application runs.

Information processed through Firebase Analytics may include:

- Names of screens visited within ScrollPace
- Whether the application build is a debug or release build
- Application interactions and session information
- Application version
- Device and operating system information
- Firebase installation identifiers
- General technical information automatically processed by Firebase
- Approximate geographic information derived by Google from network information, where applicable

ScrollPace does not intentionally include the following in Analytics events:

- Identity of the protected application
- Protected-application usage duration
- Walking step counts
- Messages
- Passwords
- Typed text
- Screen content

Analytics information is used to understand feature usage and improve ScrollPace.

Firebase Analytics data is not used by Eldroid Apps for third-party advertising.

## 7. Firebase Crashlytics

ScrollPace uses Firebase Crashlytics to identify crashes and improve application stability.

Crashlytics may process:

- Crash stack traces
- Exception types and messages
- Crash timestamps
- Application version and package identifier
- Device model and operating system
- Device architecture, memory, and storage information
- Application foreground or background state
- Firebase and Crashlytics installation identifiers
- Other technical diagnostics required to investigate crashes

ScrollPace does not intentionally attach protected-app identity, usage history, walking progress, messages, passwords, typed text, or screen content to Crashlytics reports.

Google states that Crashlytics crash information and associated identifiers are generally retained for 90 days before deletion begins.

## 8. Third-party service provider

Firebase Analytics and Firebase Crashlytics are provided by **Google LLC**.

Google processes analytics and technical information according to applicable Firebase, Google Analytics, privacy, and data-processing terms.

Information may be processed on Google infrastructure outside the user's country of residence. Google applies safeguards for international data transfers where required.

More information is available at:

- [Firebase Privacy and Security](https://firebase.google.com/support/privacy)
- [Google Privacy Policy](https://policies.google.com/privacy)

## 9. Sharing of information

Eldroid Apps does not sell personal information.

Information may be disclosed only:

- To Google as the provider of Firebase Analytics and Firebase Crashlytics
- When required by applicable law or a valid legal request
- When reasonably necessary to protect users, the application, or legal rights

Information obtained through the Accessibility Service is not shared with Google or other third parties.

## 10. Data retention and deletion

Local ScrollPace data remains on the device until the user:

- Removes the protected application from ScrollPace
- Clears ScrollPace's application data through Android settings
- Uninstalls ScrollPace

Because ScrollPace does not provide user accounts, locally stored information is not associated with an Eldroid Apps account.

Firebase Analytics information is retained according to the retention settings and terms of the Firebase and Google Analytics services.

Firebase Crashlytics generally retains crash reports and associated identifiers for 90 days before deletion begins.

Users may contact Eldroid Apps regarding remotely processed information. Because ScrollPace does not use user accounts, Eldroid Apps may require an applicable installation identifier to locate pseudonymous technical data.

## 11. Security

ScrollPace uses Android private application storage for locally stored information.

Information sent to Firebase is transmitted using encrypted network connections. Google states that Firebase services use encryption in transit and applicable security controls.

No electronic storage or transmission method can be guaranteed to be completely secure.

## 12. User choices and rights

Users can:

- Choose whether to enable the Accessibility Service
- Disable Accessibility access through Android settings
- Choose whether to grant physical activity permission
- Revoke physical activity permission through Android settings
- Remove the protected application from ScrollPace
- Clear local data through Android application settings
- Delete local data by uninstalling ScrollPace
- Contact Eldroid Apps regarding privacy questions or applicable data rights

Depending on their location, users may have rights to access, correct, object to, restrict, or request deletion of personal information.

## 13. Children's privacy

ScrollPace is not directed to children under 13 years of age.

Eldroid Apps does not knowingly collect personal information from children under 13. If you believe that a child has provided personal information through ScrollPace, contact eldroid.apps@gmail.com.

## 14. Changes to this policy

This Privacy Policy may be updated when ScrollPace's functionality, data practices, or legal requirements change.

The updated policy will be published at the same public URL with a revised effective date.

## 15. Contact

For privacy questions or requests:

**Eldroid Apps**  
**eldroid.apps@gmail.com**
