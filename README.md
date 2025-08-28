
# SMS → Webhook (Android)

Simple app that forwards incoming bank SMS to a webhook URL (JSON POST).

## Build
- Open in Android Studio (Giraffe+), Gradle sync.
- Run on Android 7.0+ (minSdk 24).

## Setup in the app
- Webhook URL: https://cricketlivelinevip271.shop/upi-auto/sms_webhook.php?key=CHANGE_ME_123
- Allowed senders: HDFCBK,AXISBK,SBIINB,ICICIB,KOTAKB,UPI
- Keywords: credited,INR,UPI,received
- Enable "Run foreground" for reliability.

## Permissions
- RECEIVE_SMS, READ_SMS, INTERNET, POST_NOTIFICATIONS (Android 13).

