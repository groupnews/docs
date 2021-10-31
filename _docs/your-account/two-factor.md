---
layout: default
has_children: false
title: Two Factor Authentication
parent: Your Account
nav_order: "3"

---
# Two Factor Authentication (2FA)

(NOTE: THIS WAS STOLEN VERBATIM FROM THE SLACK WEBSITE)

For an added layer of security, turn on two-factor authentication (2FA) for your GroupNews account. If your password is compromised or stolen, you'll have peace of mind knowing that only you can sign in.

## How 2FA works:

* **You’ll need access to your mobile phone when you sign in to Slack.**
* You'll enter a verification code and your password each time you sign in.
* You can choose to send your verification code by text message or from an authentication app.

## Step 1: Download and install an authentication app

Before you can set up 2FA on your account, you’ll need to download and install an authentication app on your device. GroupNews 2FA can be used with most Time-Based, One-Time Password (TOTP) applications. Here are a few options to get you started:

* **iPhone:** [Google Authenticator](https://itunes.apple.com/us/app/google-authenticator/id388497605?mt=8), [Duo Mobile](http://guide.duosecurity.com/), [1Password](https://guides.agilebits.com/1password-ios/5/en/topic/setting-up-one-time-passwords), [Authy](https://itunes.apple.com/us/app/authy/id494168017?mt=8), [Microsoft Authenticator](https://app.adjust.com/h66ftb_42hbak?campaign=appstore_ios&fallback=https://itunes.apple.com/app/microsoft-authenticator/id983156458)
* **Android:** [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en), [Duo Mobile](http://guide.duosecurity.com/), [1Password](https://support.1password.com/getting-started-android/), [Authy](https://play.google.com/store/apps/details?id=com.authy.authy&hl=en), [Microsoft Authenticator](https://app.adjust.com/h66ftb_42hbak?campaign=appstore_android&fallback=https://play.google.com/store/apps/details?id=com.azure.authenticator&hl=den)
* **Windows Phone:** [Duo Mobile](https://guide.duosecurity.com)

**Note:** GroupNews doesn't support Universal 2nd Factor (U2F) yet.

***

## Step 2: Turn on 2FA in GroupNews

1. Sign in to the appropriate workspace, and visit your **Account** page at **(?)**
2. Next to **Two-factor Authentication**, click **Expand**. Then, click **Set Up Two-Factor Authentication**.
3. Enter your password, and click **Use an app** to retrieve authentication codes from the authentication app on your device.
4. Add a new account. In most apps, you can do this by tapping the **+** icon.
5. Scan the QR code by using your device's camera. If you prefer, you can choose to enter the code by hand.
6. On Slack's 2FA configuration page, enter the 6-digit verification code that your authentication app generates.
7. To finish, press **Verify Code**.

When you sign in to GroupNews, just open your authentication app and enter a code along with your password.