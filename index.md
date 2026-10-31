# CurrencyLens privacy policy

Effective 31 October 2026

CurrencyLens ("the app") is an Android app by German Casares March that reads prices through your phone's camera and shows
them in your own currency. This page says what the app does with your information. The short version: the app has no
account, no ads and no tracking of its own, and the pictures it reads never leave your phone.

## What the app uses

**Camera and photos.** The app uses the camera to find prices on what you point it at, and can read a photo you choose from
your gallery. The text in the picture is recognised on your phone, using Google's ML Kit text recognition (a model that
comes inside the app). Text in photos is also read by PaddleOCR models bundled in the app; they run entirely on your phone.
The pictures are not uploaded anywhere and are not kept, unless you tap **Save**: then the photo with the converted prices is
saved to Pictures/CurrencyLens on your phone. If you tap **Share**, the photo goes to the app you pick in Android's share
menu, and nothing else.

**What stays on your phone.** The app remembers your home currency, the menu currency you picked by hand (and the country you
were in when you picked it), how you chose to have photos read (Fast, Balanced or Accurate), and the last exchange rates it
downloaded. This is stored only on your phone. Clearing the app's
data or uninstalling the app removes it. The app does not use your location. To guess the menu currency it reads, on the phone
only, the country of the mobile network you are connected to, the country of your SIM card and your phone's region setting.

## What leaves your phone

**Exchange rates.** When the rates it has are more than a few hours old, the app downloads the current ones from
open.er-api.com, a service run by ExchangeRate-API (exchangerate-api.com). The request carries no account, no identifier and
nothing from your pictures. As with any website, their server sees your phone's IP address and the technical details of the
request, and handles them under its own privacy policy. The app works with the rates it last saved when you have no network,
and it ships with a built-in set for the first start.

**Diagnostics from Google's text recognition.** The text recognition library (Google ML Kit) can send technical diagnostics
to Google while the app runs: the phone's make, model and Android version, the app's name and version, performance figures
such as how long recognition took, error codes, and an identifier for this installation that is not meant to identify you or
your phone. It does not send your pictures or the text read from them. Google describes this at
https://developers.google.com/ml-kit/android-data-disclosure.

## What the app does not do

- It has no account or login and asks for no name, email address or phone number.
- It shows no ads and contains no advertising or analytics library of its own.
- It does not sell or share your information, and does not track you across apps or websites.
- It does not send your pictures, or the prices read from them, to anyone.

## Payment

The app is a paid app sold through Google Play. Google handles the payment; the developer does not receive your card or
payment details.

## Children

The app collects no personal information from anyone, including children.

## Changes

If the app starts doing something that changes this page, the page will be updated and the date above changed before the
update reaches you.

## Contact

Questions about this policy: german95n@gmail.com
