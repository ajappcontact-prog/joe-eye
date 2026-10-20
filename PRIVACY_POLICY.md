# Joe Eye: Privacy Policy

_Last updated: 20 October 2026. Host this page at a public web address (a GitHub Pages page works). Paste that address into Play Console > App content > Privacy policy, and into `cloud.properties` as `privacyPolicyUrl=` so the app links to it._

Joe Eye ("the app") is a camera and audio recorder. This policy explains what the app does with your information.

## The short version
- Your recordings stay on your phone unless **you** link a Google Drive or Dropbox account and turn on Cloud backup.
- The developer does not receive your recordings, location, name, email or any other data. There is no Joe Eye server, and no advertising, analytics or tracking in the app.
- The debug log leaves your phone only if you choose to email it to the developer.
- Joe Eye is a visible recorder: while it records, Android shows a notification. Please use it lawfully (see "Recording other people").

## What the app accesses, and why
| Access | Why | Where it goes |
|---|---|---|
| Camera | To record video, and to detect movement if you turn on motion-triggered recording | Video is saved on your phone. Movement is detected on the phone from the live picture; those frames are not saved or sent anywhere. |
| Microphone | To record sound with video | Saved on your phone |
| Location (optional) | Only if you choose "Date, time and GPS" on the video; the position is drawn into the video picture | Saved inside the video on your phone; not sent anywhere by the app |
| Notifications | To show that recording is running and to report problems | Stays on your phone |
| Internet | Only for Cloud backup and "Sign in with Google" | Google Drive, Dropbox or Google sign-in, as described below |
| Battery-optimization exemption (optional) | So Android doesn't stop a long recording you started | Stays on your phone |
| Fingerprint / screen lock (optional) | Only to lock the app if you turn on App lock | Handled by Android; the app never sees your fingerprint |

## Sign in with Google (optional at first)
If you tap "Sign in with Google", Google asks you to share your name, email address and Google account ID with Joe Eye. They are stored only on your phone, to show who is signed in, and are never sent to the developer or any server. Signing in is not required to start using the app. If you later sign out (or choose Delete account data), Joe Eye locks and cannot be used until you sign in with Google again; nothing is deleted from your phone while it is locked. Google handles the sign-in under its own privacy policy. Signing in also links Google Drive backup in the same step (one Google screen); if you untick the Drive permission there, only the profile is saved.

## Terms & License Agreement
Before first use you are asked to accept the Terms & License Agreement. The phone stores only that you accepted, which version, and when. This is kept on your phone and is not sent to the developer or anyone else. You can read the terms again in Settings > Account > Terms & License.

## Free trial and subscription
Accepting the Terms & License Agreement starts a free 7-day trial; no payment details are asked for. After the trial, recording needs a subscription of $3 a month (the price shown by Google Play applies), bought and billed by Google Play and renewed monthly until you cancel it in Google Play. Joe Eye never sees your card or payment details. The app asks Google Play whether you have an active subscription and keeps the answer, and the date your trial started, on your phone. After the trial or a cancelled subscription ends, the Library stays open so you can still reach, share and delete your recordings. Google handles payments under its own privacy policy.

## Cloud backup (optional)
If you link Google Drive, the app asks Google for the limited `drive.file` permission, which lets it see and manage only the files the app itself uploads. If you link Dropbox, the app uses its own "App folder" (Apps/Joe Eye), so it cannot see the rest of your Dropbox. It also reads the email address of the linked Dropbox account, to show which account is linked in Settings; the address is kept only on your phone. Uploads go straight from your phone to your account over HTTPS. Sign-in tokens are stored on your phone and are excluded from Android backup. If you link an account, the app also asks Google Drive or Dropbox how much storage the account uses and has in total. It shows these figures in Settings and uses them to decide when new recordings switch to your other linked account. The figures are read on your phone and are not sent to the developer or any other server. Unlinking stops uploads and does not delete what is already in your account. While the app is open it checks, now and then, that Dropbox still allows access; this is a small request from your phone straight to Dropbox. If the Joe Eye folder or the app's access is removed in Dropbox, Joe Eye unlinks Dropbox by itself, shows a message and a notification, and recordings that were backed up there show as not backed up. **Your cloud folders are yours to look after:** if you or anyone else delete the folders or files where your recordings are saved, any information lost is not the responsibility of the developer. Files you upload are subject to Google's or Dropbox's own privacy policies.

## Encryption (optional)
If you turn on "Encrypt recordings", the app stores your recordings encrypted (AES-256) in its private storage, using a key held in the Android Keystore. They are hidden from the gallery and other apps. If you uninstall the app or clear its data, those recordings cannot be recovered. Cloud backup uploads a normal, readable copy.

## Debug log (optional)
The app keeps a small log of app events, errors and crashes on your phone, with your phone model and Android version. It contains no video, audio, location or account details. It leaves your phone only when you tap "Send debug log to the developer" and press Send in your email app; it goes to aj.appcontact@gmail.com. You can clear it at any time in Settings.

## How long data is kept
Recordings, the optional profile and the debug log stay on your phone until you delete them (or uninstall the app). The developer holds no copy, so there is nothing for the developer to keep or delete. Emailed debug logs are kept only as long as needed to fix the problem.

## Delete your account and data
Joe Eye has no server-side accounts. To delete everything it holds about you:
1. In the app, open **Settings > Account > Delete account data**. This removes your name, email and Google ID from the phone and clears the debug log. Joe Eye then asks you to sign in again before it can be used.
2. Delete any recordings you no longer want in the Library (or uninstall the app, which removes all app data).
3. To stop Joe Eye having access to your Google account, remove it at https://myaccount.google.com/permissions. For Dropbox, remove it at https://www.dropbox.com/account/connected_apps. Files already uploaded to your own Drive or Dropbox stay there until you delete them.
4. If you emailed a debug log and want it deleted, write to aj.appcontact@gmail.com.

## Children
The app is not directed at children under 13 (or the age set by your country).

## Recording other people
Laws about recording video, audio and location of other people differ by country. You are responsible for using the app lawfully and for getting any consent the law requires. Do not use Joe Eye to record people secretly.

## Changes to this policy
If the app's data practices change, this page is updated and the date above changes.

## Contact
Jonse, AJ Developer, aj.appcontact@gmail.com
