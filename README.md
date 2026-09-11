# BatchMode Privacy Policy

Developer: Daria Kalmykova  
App: BatchMode  
Effective date: September 11, 2026

BatchMode helps you reduce interruptions by snoozing Android notifications and letting Android restore them at scheduled intervals. Your notification data is processed on your device. BatchMode does not send it to the developer or to a server.

## Notification access

BatchMode needs Android's Notification Access permission to receive notification events, snooze eligible notifications, and show how many notifications are currently snoozed by app. This access operates in the background, including when the app's screen is closed.

Depending on what Android makes available, notifications may contain message text, sender information, timestamps, and other sensitive information. BatchMode processes notification content and metadata locally to decide whether to snooze a notification and to distinguish new content from a notification that has already been released. It may inspect attachment references included in notifications; it does not download attachments.

BatchMode creates a content fingerprint (a hash) for change detection. It does not save notification titles, message bodies, sender names, or attachment contents as a notification history. Message timestamps used to distinguish new messages from delayed releases are processed in memory, not stored separately.

Android grants notification access broadly. Adding an app to exceptions prevents BatchMode from intentionally snoozing its notifications; it does not remove that app's notifications from the access Android grants. Turning batching off also does not revoke notification access.

## Information stored on your device

BatchMode stores the information needed to operate:

- Your batching settings, including the selected period, whether batching is enabled, a pause end time, and identifiers of apps you exclude.
- Android notification identifiers, content fingerprints, snooze states, and known release deadlines. Notification identifiers can contain app-provided identifiers; they are not necessarily anonymous.

BatchMode also reads app names and icons locally to show the app exceptions list and group snoozed notifications by app. Notification counts are obtained from Android. If you add the home screen widget, it displays batching status and related information on your home screen.

Stored settings and notification tracking data are kept in Android's app-private storage, in a location excluded from Android backup. BatchMode does not provide cloud storage or synchronization.

## Data transmission and third parties

BatchMode does not have an Internet permission and does not upload notification content, fingerprints, app lists, or settings. It does not include advertising, analytics, or automatic crash-reporting services, and does not sell or share this on-device data with third parties.

Android, Google Play, and the apps that originally send your notifications operate independently and have their own privacy practices. This policy covers BatchMode's handling of data.

## Diagnostic logs

The production release of BatchMode does not write diagnostic logs.

## Retention and deletion

Settings remain on your device until changed or the app's storage is cleared. Notification tracking records are updated or removed as BatchMode receives notification events and reconciles its records with Android. They have no fixed time-based retention period and may remain if Android does not report a removal.

You can:

- Revoke Notification Access in Android settings to stop BatchMode receiving notifications through that access.
- Clear BatchMode's storage in Android's app settings, or uninstall BatchMode, to remove its locally stored settings, and tracking records.
- Pause or turn off batching to allow new notifications through. This does not delete stored data or revoke notification access.

Android manages the original notifications and their snooze timers separately. Pausing batching, changing the period, or deleting BatchMode's local data does not instruct Android to immediately release notifications already snoozed.

BatchMode has no user accounts and the developer has no remote copy of your app data to delete.

## Contact

For privacy questions, contact Daria Kalmykova at [moonchild174@gmail.com](mailto:moonchild174@gmail.com).

If you choose to email the developer, your email address and the information you provide are handled through the email service to respond to your request. Please do not include notification contents or other sensitive information unnecessarily.

## Policy updates

This policy may be updated when BatchMode's functionality or data handling changes. The current policy will be published at the same public policy address, with an updated effective date.
