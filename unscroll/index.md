<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Privacy Policy for ScrollPace</title>
</head>
<body>
  <h1>Privacy Policy for ScrollPace</h1>
  <p><strong>Effective date: August 21, 2026</strong></p>

  <p>
    ScrollPace is an Android digital wellbeing application published by Eldroid Apps,
    an independent developer.
  </p>
  <p>
    This Privacy Policy explains what information ScrollPace accesses, processes,
    stores, and shares.
  </p>
  <p>
    For privacy questions, contact:<br />
    Eldroid Apps<br />
    Email: eldroid.apps@gmail.com
  </p>

  <h2>1. Overview</h2>
  <p>
    ScrollPace helps users manage time spent in selected applications. When a chosen
    daily limit is reached, ScrollPace can offer a walking challenge that unlocks
    additional usage time.
  </p>
  <p>
    Free users can protect one application. Premium subscribers can protect unlimited
    applications through an optional Google Play subscription.
  </p>
  <p>
    Most wellbeing and usage information is processed and stored locally on the user’s
    device.
  </p>
  <p>
    ScrollPace does not require an account and does not ask for a user’s name, email
    address, contacts, messages, passwords, photos, precise location, or payment card
    information.
  </p>
  <p>
    ScrollPace uses Firebase Analytics and Firebase Crashlytics for application
    analytics and technical diagnostics. Payments for Premium are processed by Google Play.
  </p>

  <h2>2. Information stored locally</h2>
  <p>
    ScrollPace processes and stores the following information locally on the user’s device:
  </p>
  <ul>
    <li>Package names and display names of applications selected for protection</li>
    <li>Selected daily usage limits</li>
    <li>Days on which protection is active for each protected application</li>
    <li>Time spent using protected applications</li>
    <li>Daily and recent usage history</li>
    <li>Walking challenge progress and completion</li>
    <li>Earned bonus time</li>
    <li>Challenge-related events and timestamps</li>
    <li>Onboarding completion state</li>
    <li>Technical state indicating whether the Accessibility Service is connected</li>
    <li>
      Local Premium entitlement status (whether Premium appears active), used to unlock
      features after restart or brief offline use
    </li>
  </ul>
  <p>
    This information is stored using Android DataStore or private application preferences.
  </p>
  <p>
    ScrollPace does not intentionally transmit local wellbeing information, protected-app
    identities, usage history, or entitlement status to Eldroid Apps servers, advertisers,
    or data brokers.
  </p>
  <p>Android backup is disabled for ScrollPace.</p>

  <h2>3. Installed applications</h2>
  <p>
    ScrollPace accesses the list of launchable applications installed on the device so
    that the user can select applications to protect.
  </p>
  <p>The installed application list is:</p>
  <ul>
    <li>Read and processed locally</li>
    <li>Displayed only in the application picker</li>
    <li>Not uploaded to Eldroid Apps or Firebase</li>
    <li>Not used for advertising</li>
  </ul>
  <p>
    Only applications selected by the user are stored locally as protected applications.
  </p>

  <h2>4. Accessibility Service</h2>
  <p>
    ScrollPace uses the Android AccessibilityService API to provide its core digital
    wellbeing functionality.
  </p>
  <p>
    ScrollPace is not an accessibility tool and does not claim that its primary purpose
    is to assist users with disabilities.
  </p>

  <h3>Information accessed</h3>
  <p>
    The Accessibility Service observes Android window-change events and accesses the
    package identity of the application currently visible in the foreground.
  </p>
  <p>
    ScrollPace compares that identity with the user’s currently active protected
    applications.
  </p>

  <h3>How this information is used</h3>
  <p>Foreground application identity is used only to:</p>
  <ul>
    <li>Detect when a protected application is open</li>
    <li>Measure how long it remains in the foreground</li>
    <li>Compare usage against the user’s selected daily limit</li>
    <li>Display a wellbeing challenge when the limit is reached</li>
    <li>Stop counting when another application becomes active</li>
  </ul>
  <p>
    If Premium ends, additional protected applications may remain saved on the device but
    paused. Paused applications are not monitored and are not interrupted until Premium
    is renewed or the user changes configuration.
  </p>
  <p>
    Only selected protected applications’ identity and usage information are stored locally.
  </p>

  <h3>What the Accessibility Service does not do</h3>
  <p>ScrollPace does not use Accessibility access to:</p>
  <ul>
    <li>Read messages or notifications</li>
    <li>Read or collect passwords</li>
    <li>Inspect screen text or content</li>
    <li>Monitor keyboard input or typed text</li>
    <li>Capture screenshots</li>
    <li>Record audio</li>
    <li>Perform clicks, gestures, or actions on the user’s behalf</li>
    <li>Change device settings</li>
    <li>Control other applications</li>
    <li>Make autonomous decisions</li>
    <li>Collect unrelated user information</li>
  </ul>
  <p>
    Information obtained through Accessibility access is not shared with Firebase,
    advertisers, data brokers, or other third parties.
  </p>

  <h3>Consent and user control</h3>
  <p>
    Before directing the user to Android Accessibility settings, ScrollPace displays a
    separate in-app disclosure explaining:
  </p>
  <ul>
    <li>What information is accessed</li>
    <li>Why the information is needed</li>
    <li>How the information is used</li>
    <li>That the information is stored locally</li>
    <li>That the information is not shared with third parties</li>
  </ul>
  <p>
    The user must affirmatively confirm consent before continuing to Android Accessibility
    settings.
  </p>
  <p>
    Accessibility access is optional and may be declined or revoked at any time through
    Android settings. Protection and foreground usage tracking will not function while the
    service is disabled.
  </p>

  <h2>5. Physical activity and step information</h2>
  <p>ScrollPace may request Android’s ACTIVITY_RECOGNITION permission.</p>
  <p>
    This permission is used during walking challenges to receive step information from the
    device’s step detector or step counter sensor.
  </p>
  <p>Step information is used to:</p>
  <ul>
    <li>Display walking challenge progress</li>
    <li>Determine when a challenge is completed</li>
    <li>Award additional protected-app usage time</li>
  </ul>
  <p>
    ScrollPace does not use GPS and does not collect precise or approximate location data.
  </p>
  <p>
    Walking challenge information is processed locally and is not intentionally sent to
    Firebase Analytics or Firebase Crashlytics.
  </p>
  <p>
    The user may deny or revoke physical activity permission through Android settings.
    Walking challenges may not function without this permission.
  </p>

  <h2>6. Purchases and Google Play subscriptions</h2>
  <p>
    ScrollPace offers an optional auto-renewing Premium subscription through Google Play
    Billing. Premium currently unlocks unlimited protected applications. Features marked
    as coming later in the app are not part of the current paid entitlement.
  </p>
  <p>
    Google Play processes payment information. ScrollPace does not collect credit card
    numbers, bank account details, or other payment credentials.
  </p>
  <p>
    ScrollPace may store a local entitlement status on the device so Premium features can
    work after an app restart or brief offline use. A successful Google Play purchase query
    replaces that cached status.
  </p>
  <p>
    Subscriptions are associated with the Google account used for the purchase. Restore
    purchases uses that Google account. ScrollPace does not create its own user accounts
    and cannot transfer a subscription between different Google accounts.
  </p>
  <p>
    If Premium ends, protected-app configurations and history are kept on the device. The
    oldest protected application remains active under the free plan; additional
    applications remain saved but paused until Premium is renewed or the user removes them.
  </p>
  <p>
    Cancellation, renewals, refunds, and payment history are handled by Google Play under
    Google’s policies. Users can manage or cancel subscriptions in Google Play.
  </p>

  <h2>7. Firebase Analytics</h2>
  <p>
    ScrollPace uses Google Analytics for Firebase to understand general application usage.
  </p>
  <p>Analytics collection starts automatically when the application runs.</p>
  <p>Information processed through Firebase Analytics may include:</p>
  <ul>
    <li>Names of screens visited within ScrollPace</li>
    <li>Whether the application build is a debug or release build</li>
    <li>Application interactions and session information</li>
    <li>High-level subscription funnel events such as paywall view, purchase started,
      purchase success, purchase cancelled, purchase error, restore started, restore success,
      restore not found, and manage subscription opened</li>
    <li>Application version</li>
    <li>Device and operating system information</li>
    <li>Firebase installation identifiers</li>
    <li>General technical information automatically processed by Firebase</li>
    <li>Approximate geographic information derived by Google from network information, where applicable</li>
  </ul>
  <p>
    ScrollPace does not intentionally include the following in Analytics events:
  </p>
  <ul>
    <li>Identity of protected applications</li>
    <li>Protected-application usage duration</li>
    <li>Walking step counts</li>
    <li>Purchase tokens, order IDs, or other billing identifiers</li>
    <li>Messages</li>
    <li>Passwords</li>
    <li>Typed text</li>
    <li>Screen content</li>
  </ul>
  <p>
    Analytics information is used to understand feature usage and improve ScrollPace.
    Firebase Analytics data is not used by Eldroid Apps for third-party advertising.
  </p>

  <h2>8. Firebase Crashlytics</h2>
  <p>
    ScrollPace uses Firebase Crashlytics to identify crashes and improve application stability.
  </p>
  <p>Crashlytics may process:</p>
  <ul>
    <li>Crash stack traces</li>
    <li>Exception types and messages</li>
    <li>Crash timestamps</li>
    <li>Application version and package identifier</li>
    <li>Device model and operating system</li>
    <li>Device architecture, memory, and storage information</li>
    <li>Application foreground or background state</li>
    <li>Firebase and Crashlytics installation identifiers</li>
    <li>Other technical diagnostics required to investigate crashes</li>
  </ul>
  <p>
    ScrollPace does not intentionally attach protected-app identity, usage history, walking
    progress, purchase tokens, messages, passwords, typed text, or screen content to
    Crashlytics reports.
  </p>
  <p>
    Google states that Crashlytics crash information and associated identifiers are generally
    retained for 90 days before deletion begins.
  </p>

  <h2>9. Third-party service providers</h2>
  <p>
    Firebase Analytics and Firebase Crashlytics are provided by Google LLC.
    Google Play Billing and subscription processing are provided by Google Play.
  </p>
  <p>
    Google processes analytics, technical, and payment-related information according to
    applicable Firebase, Google Analytics, Google Play, privacy, and data-processing terms.
  </p>
  <p>
    Information may be processed on Google infrastructure outside the user’s country of
    residence. Google applies safeguards for international data transfers where required.
  </p>
  <p>More information is available at:</p>
  <ul>
    <li>Firebase Privacy and Security</li>
    <li>Google Privacy Policy</li>
    <li>Google Play Terms of Service</li>
  </ul>

  <h2>10. Sharing of information</h2>
  <p>Eldroid Apps does not sell personal information.</p>
  <p>Information may be disclosed only:</p>
  <ul>
    <li>To Google as the provider of Firebase Analytics, Firebase Crashlytics, and Google Play services</li>
    <li>When required by applicable law or a valid legal request</li>
    <li>When reasonably necessary to protect users, the application, or legal rights</li>
  </ul>
  <p>
    Information obtained through the Accessibility Service is not shared with Google Analytics,
    advertisers, data brokers, or other third parties.
  </p>

  <h2>11. Data retention and deletion</h2>
  <p>Local ScrollPace data remains on the device until the user:</p>
  <ul>
    <li>Removes a protected application from ScrollPace</li>
    <li>Clears ScrollPace’s application data through Android settings</li>
    <li>Uninstalls ScrollPace</li>
  </ul>
  <p>
    Because ScrollPace does not provide user accounts, locally stored information is not
    associated with an Eldroid Apps account.
  </p>
  <p>
    Google Play retains purchase and subscription records according to Google’s policies.
    Firebase Analytics information is retained according to the retention settings and terms
    of the Firebase and Google Analytics services.
  </p>
  <p>
    Firebase Crashlytics generally retains crash reports and associated identifiers for 90 days
    before deletion begins.
  </p>
  <p>
    Users may contact Eldroid Apps regarding remotely processed information. Because
    ScrollPace does not use user accounts, Eldroid Apps may require an applicable installation
    identifier to locate pseudonymous technical data.
  </p>

  <h2>12. Security</h2>
  <p>
    ScrollPace uses Android private application storage for locally stored information.
  </p>
  <p>
    Information sent to Firebase is transmitted using encrypted network connections. Google
    states that Firebase and Google Play services use encryption in transit and applicable
    security controls.
  </p>
  <p>
    No electronic storage or transmission method can be guaranteed to be completely secure.
  </p>

  <h2>13. User choices and rights</h2>
  <p>Users can:</p>
  <ul>
    <li>Choose whether to enable the Accessibility Service</li>
    <li>Disable Accessibility access through Android settings</li>
    <li>Choose whether to grant physical activity permission</li>
    <li>Revoke physical activity permission through Android settings</li>
    <li>Remove protected applications from ScrollPace</li>
    <li>Manage or cancel Premium in Google Play</li>
    <li>Restore purchases using the Google account that bought Premium</li>
    <li>Clear local data through Android application settings</li>
    <li>Delete local data by uninstalling ScrollPace</li>
    <li>Contact Eldroid Apps regarding privacy questions or applicable data rights</li>
  </ul>
  <p>
    Depending on their location, users may have rights to access, correct, object to, restrict,
    or request deletion of personal information.
  </p>

  <h2>14. Children’s privacy</h2>
  <p>ScrollPace is not directed to children under 13 years of age.</p>
  <p>
    Eldroid Apps does not knowingly collect personal information from children under 13. If you
    believe that a child has provided personal information through ScrollPace, contact
    eldroid.apps@gmail.com.
  </p>

  <h2>15. Changes to this policy</h2>
  <p>
    This Privacy Policy may be updated when ScrollPace’s functionality, data practices, or
    legal requirements change.
  </p>
  <p>
    The updated policy will be published at the same public URL with a revised effective date.
  </p>

  <h2>16. Contact</h2>
  <p>
    For privacy questions or requests:<br />
    Eldroid Apps<br />
    eldroid.apps@gmail.com
  </p>
</body>
</html>
