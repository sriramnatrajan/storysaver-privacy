# Privacy Policy

**StorySaver** (`com.sriram.storyproject`)

Effective date: 11 November 2026

This policy explains what information StorySaver (“the App”) handles. By using the App, you agree to it. This is a notice for a small independent app. It is not legal advice.

StorySaver does not run its own account system or its own servers. An optional Instagram sign-in stays on your phone. Saved photos, videos, and audio stay on your phone. Google Firebase may receive screen names, which buttons you tap, whether you are logged in, and crash reports. It does not receive your Instagram username or password. Google AdMob serves ads inside the App. We do not sell personal information.

## 1. Who we are

StorySaver is an independent Android app (package `com.sriram.storyproject`). It is not affiliated with, endorsed by, or operated by Instagram or Meta.

Contact: [sriramnat10@gmail.com](mailto:sriramnat10@gmail.com). When the App is listed on Google Play, you can also use the support contact on that listing.

## 2. Summary

- **On your device:** Instagram session cookies, the name shown as logged in, recent profiles, download history, saved files, reminder timing, and a one-day list of profiles unlocked with a rewarded ad.
- **Instagram:** when you are signed in, the App loads stories, highlights, posts, reels, subscription posts you can already open, and profile search through Instagram’s website, using your session.
- **Firebase Analytics:** screen names, button names, and whether you are logged in (yes or no). No Instagram username.
- **Firebase Crashlytics:** crash reports so faults can be fixed.
- **Google AdMob:** banner, native, full-screen, and rewarded ads.
- **Google Play:** in-app review and app updates, when Play provides them.

## 3. Instagram sign-in

Sign-in is optional. You sign in on instagram.com inside the App. Instagram (Meta) receives that login under [Instagram’s privacy policy](https://privacycenter.instagram.com/policy). The App does not operate the login form and does not store your Instagram password.

After you sign in, the session cookie stays in the App’s WebView cookie store on the device. Logging out clears those cookies. The Instagram name shown as “logged in as” is saved only in the App’s preferences on the device. It is not sent to Firebase.

While you are signed in, the App requests content you can already open with that session: stories and highlights from accounts you follow or that are public, posts, reels, subscription posts that Instagram returns for that profile, and profile search. Private accounts you do not follow stay closed. The App does not tell Instagram that you viewed a story.

A profile search query is sent to Instagram so matching accounts can be listed. The query is not sent to Firebase.

## 4. On your device

The App saves this locally, in app preferences or in your gallery:

- Recent profiles: username, user id, profile picture address, and whether stories were already seen.
- Download history: media id, username, kind (story, highlight, post, reel, or subscription), photo / video / audio, a short detail, thumbnail address, size, progress, time, and where the file was saved.
- Saved files in `Pictures/StorySaver`, `Movies/StorySaver`, or `Music/StorySaver`.
- The signed-in Instagram name, until you log out.
- If you watch a rewarded ad to download everything from one profile, that profile name is remembered on the device for the local day.
- Whether a Play review was already requested, and the times used to decide a local reminder.

This stays on the phone unless you clear it in the App, clear app storage, uninstall, or restore a backup. Android Auto Backup may copy app preferences to your Google account if backups are enabled. We do not upload this store to our own servers.

Paste reads the clipboard only when you tap Paste. That text is used to open a profile. It is not sent to Firebase.

A local notification may remind you to open the App if you have not opened it for about a day. That reminder is scheduled on the device. It is not a push message from our server. You can turn notifications off in Android settings.

## 5. Analytics and crashes

The App uses Google Firebase Analytics and Crashlytics.

Analytics events:

- `screen_view` — the screen you open, such as home, downloads, settings, login, a profile tab, a story, or a saved video. The name is a screen label, not an Instagram username.
- `select_content` — the control you tap, such as paste, view stories, a tab, download, or search. The value is a short button id, not the account you opened.
- `login` — you signed in. The method is `instagram`. The username is not included.
- `logout` — you signed out.

User property: `logged_in`, set to `yes` or `no`.

Google may also collect standard SDK data such as an app instance id, device and OS version, country or region, and session information. See [Firebase privacy information](https://firebase.google.com/support/privacy).

Crashlytics may include a stack trace, device model, OS version, and the fact that the App crashed. Reports are used to fix bugs. We do not add your Instagram username to analytics events. A crash report is still a technical log and can include text that was on screen.

Google LLC processes Analytics and Crashlytics data. It may be stored in the United States or other countries where Google operates.

## 6. Ads

The App shows ads from Google AdMob:

- A banner on Home, Downloads, Settings, and a profile.
- A native ad on Home, in a profile grid, and in the downloads list.
- A full-screen ad sometimes after you save a file, and sometimes when you leave the story viewer or the saved-video player after that screen has been open for a few seconds. Full-screen ads are spaced apart. They are not shown when you open the App, when you leave the App, on the login screen, or on top of the video controls.
- A rewarded ad before “Download all.” Closing it early does not start that download. A single-item download does not require that ad.

Google may use the Android advertising ID, IP address, and device information (such as model, OS version, and app version) to choose an ad, limit how often you see it, and measure that it was shown. See [Google’s privacy policy](https://policies.google.com/privacy) and [AdMob and user privacy](https://support.google.com/admob/answer/6128543).

The App does not show its own ad-consent screen. You can reset or delete the advertising ID in Android settings, and you can limit ad personalization in your Google account. If Google shows its own message about ads, that choice is handled by Google.

We do not sell your personal information.

## 7. What we do not collect

- We do not ask you to create a StorySaver account.
- We do not collect your name, email, contacts, precise location, photos outside the files you choose to save, or microphone audio.
- We do not send your Instagram password, username, captions, or saved media to Firebase.
- We do not sell personal information.

## 8. Permissions

- **Internet and network state** — load Instagram content, ads, analytics, and crash reports.
- **Notifications** — a local reminder if you have not opened the App for about a day. Android asks for this permission on Android 13 and later.
- **Storage** — on Android 9 and earlier, to save files into public folders. On newer Android versions the App saves into Pictures, Movies, and Music through the system media library, without that broad storage permission.
- **Advertising ID** — AdMob may use it to choose and measure ads.

## 9. Children

The App is a general-audience utility. It is not directed at children under 13, or under the age required where you live. It does not use child-directed ad treatment. We do not knowingly collect personal information from children. Instagram’s own age rules apply to an Instagram account.

## 10. Retention

On the device: until you log out, clear recent profiles, clear app storage, or uninstall, and subject to device backup. Gallery files remain until you delete them. Firebase and AdMob data are kept according to Google’s policies. We do not keep a separate copy of your downloads or Instagram session on our own servers.

## 11. Your choices

- Use the App without signing in. Some stories, private accounts, posts, reels, and search need an Instagram login.
- Log out in Settings. That clears the Instagram cookies stored by the App.
- Clear recent profiles in Settings.
- Clear StorySaver storage or uninstall in Android settings.
- Turn off notifications in Android settings.
- Reset the advertising ID, or limit ad personalization, in Android or Google account settings.
- For Analytics data held by Google, use Google’s tools. We cannot look up your analytics by email, because we do not run accounts.

## 12. Sharing

We do not sell personal information. Information is shared with Instagram when you use an Instagram session, with Google for Firebase Analytics, Crashlytics, AdMob, and Play services, if the law requires it, or if the App is transferred to a new operator. When you share or repost a file, the app you pick receives what you send.

## 13. Security

Local data stays in the Android app sandbox, except files you save into your gallery. Traffic to Instagram and Google uses HTTPS. No method of storage or transmission is perfectly secure.

## 14. Changes

We may update this policy. The effective date at the top will change. Continued use of the App after the new date means you accept the revised policy.

## 15. Contact

StorySaver — `com.sriram.storyproject`. Email [sriramnat10@gmail.com](mailto:sriramnat10@gmail.com).
