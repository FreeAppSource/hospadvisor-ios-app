# HospAdvisor iOS App

> 👨‍💻 Developed by **[Suresh Kumar Meesala](https://github.com/SureshKumarMeesala)** · 🎨 UI design by **Uladzislau Luchkouski** (credits below)

A mobile app built with **React Native (0.88+)**, **Expo SDK 58+** and **Expo Router**, using **JavaScript and JSX (`.js`, `.jsx`)**. Every screen is built from the original Sketch design `hospadvisor-ios-design-uladzislau-luchkouski.sketch` by **Uladzislau Luchkouski**: one route per artboard, with the artboard's layout, colours, images and text.

![HospAdvisor iOS App screens](./showcase.jpg)

## 📱 Screens (47 design artboards)

Listed in the order of the app's flow. "Taps" is the number of tap targets wired on the screen (buttons, tabs, back arrows, list rows).

| # | Screen (artboard) | Route | Size | Taps |
|---|---|---|---|---|
| 1 | **onboarding stp1** · start screen | `src/app/onboarding-stp1.jsx` | 375 × 812 | 3 |
| 2 | **onboarding stp2** | `src/app/onboarding-stp2.jsx` | 375 × 812 | 3 |
| 3 | **registration** | `src/app/registration.jsx` | 375 × 812 | 3 |
| 4 | **login** | `src/app/login.jsx` | 375 × 812 | 4 |
| 5 | **onboarding stp3** | `src/app/onboarding-stp3.jsx` | 375 × 812 | 3 |
| 6 | **registration - input focus** | `src/app/registration-input-focus.jsx` | 375 × 812 | 2 |
| 7 | **registration - input - error** | `src/app/registration-input-error.jsx` | 375 × 812 | 1 |
| 8 | **login - input focus** | `src/app/login-input-focus.jsx` | 375 × 812 | 3 |
| 9 | **login - input - error** | `src/app/login-input-error.jsx` | 375 × 812 | 2 |
| 10 | **password recovery** | `src/app/password-recovery.jsx` | 375 × 812 | 2 |
| 11 | **registration - input foces - scrollUP** | `src/app/registration-input-foces-scrollup.jsx` | 375 × 812 | 2 |
| 12 | **registration - input** | `src/app/registration-input.jsx` | 375 × 812 | 1 |
| 13 | **login - input - done** | `src/app/login-input-done.jsx` | 375 × 812 | 2 |
| 14 | **registration - input - done** | `src/app/registration-input-done.jsx` | 375 × 812 | 2 |
| 15 | **hospital** | `src/app/hospital.jsx` | 375 × 812 | 7 |
| 16 | **hospital - detail** | `src/app/hospital-detail.jsx` | 375 × 812 | 7 |
| 17 | **chekin - start** | `src/app/chekin-start.jsx` | 375 × 812 | 2 |
| 18 | **profile** | `src/app/profile.jsx` | 375 × 812 | 8 |
| 19 | **hospital - search** | `src/app/hospital-search.jsx` | 375 × 812 | 3 |
| 20 | **hospital - map** | `src/app/hospital-map.jsx` | 375 × 812 | 2 |
| 21 | **hospital scroll up** | `src/app/hospital-scroll-up.jsx` | 375 × 812 | 8 |
| 22 | **hospital - detail - feedback** | `src/app/hospital-detail-feedback.jsx` | 375 × 812 | 10 |
| 23 | **hospital - detail - statistic** | `src/app/hospital-detail-statistic.jsx` | 375 × 812 | 6 |
| 24 | **hospital - detail - information** | `src/app/hospital-detail-information.jsx` | 375 × 812 | 7 |
| 25 | **hospital - detail - hospital** | `src/app/hospital-detail-hospital.jsx` | 375 × 812 | 9 |
| 26 | **hospital - share** | `src/app/hospital-share.jsx` | 375 × 812 | 6 |
| 27 | **chekin - done** | `src/app/chekin-done.jsx` | 375 × 812 | 3 |
| 28 | **settings** | `src/app/settings.jsx` | 375 × 812 | 4 |
| 29 | **about app** | `src/app/about-app.jsx` | 375 × 812 | 1 |
| 30 | **terms** | `src/app/terms.jsx` | 375 × 812 | 1 |
| 31 | **hospital - location** | `src/app/hospital-location.jsx` | 375 × 812 | 5 |
| 32 | **hospital - search - success** | `src/app/hospital-search-success.jsx` | 375 × 812 | 3 |
| 33 | **hospital - search - not found** | `src/app/hospital-search-not-found.jsx` | 375 × 812 | 2 |
| 34 | **hospital - map - detail** | `src/app/hospital-map-detail.jsx` | 375 × 812 | 2 |
| 35 | **hospital - detail - feedback - focusInput** | `src/app/hospital-detail-feedback-focusinput.jsx` | 375 × 812 | 1 |
| 36 | **hospital - detail - feedback - scrollUp** | `src/app/hospital-detail-feedback-scrollup.jsx` | 375 × 812 | 6 |
| 37 | **hospital - detail - hospital - scrollUp** | `src/app/hospital-detail-hospital-scrollup.jsx` | 375 × 812 | 8 |
| 38 | **chekin - done - goodFeedback** | `src/app/chekin-done-goodfeedback.jsx` | 375 × 812 | 3 |
| 39 | **chekin - done - badFeedback** | `src/app/chekin-done-badfeedback.jsx` | 375 × 812 | 3 |
| 40 | **change email** | `src/app/change-email.jsx` | 375 × 812 | 1 |
| 41 | **change pass** | `src/app/change-pass.jsx` | 375 × 812 | 1 |
| 42 | **chekin** | `src/app/chekin.jsx` | 375 × 812 | 4 |
| 43 | **hospital - detail - feedback - send** | `src/app/hospital-detail-feedback-send.jsx` | 375 × 812 | 1 |
| 44 | **hospital - detail - hospital - scrollUp2** | `src/app/hospital-detail-hospital-scrollup2.jsx` | 375 × 812 | 6 |
| 45 | **chekin - feedback** | `src/app/chekin-feedback.jsx` | 375 × 812 | 2 |
| 46 | **chekin - thankyou** | `src/app/chekin-thankyou.jsx` | 375 × 812 | 1 |
| 47 | **checkin - search** | `src/app/checkin-search.jsx` | 375 × 812 | 2 |

Screenshots of every screen are in [`screenshots/`](./screenshots).

## 🧩 How it's built

- `src/screens/*.json`: each design artboard converted to screen data (vector shapes, gradients, image fills, masks, shadows, blurs and rich text, positioned as in the design), plus its tap targets
- `src/sketch/SketchScreen.jsx`: draws a screen at the device's width with `react-native-svg`, native `Text`/`TextInput` and `expo-blur`, and handles navigation between screens
- `src/app/`: Expo Router routes, one per artboard (`index.jsx` opens the start screen)
- `assets/images/`: images used by the design

## 🛠️ Tech Stack

- **Framework**: React Native 0.88+ / Expo SDK 58+
- **Navigation**: Expo Router (file-based routing)
- **Language**: JavaScript & JSX (`.js`, `.jsx`)
- **Rendering**: `react-native-svg`, `expo-blur`
- **Fonts**: Google Fonts via `@expo-google-fonts` (Inter), standing in for the design's original fonts where those aren't free

<!-- run-locally:start -->

## ▶️ Run locally

```bash
npm install
npx expo start
```

Then press `i` for the iOS simulator, `a` for Android, or `w` for the web, or scan the QR code with Expo Go.

<!-- run-locally:end -->

<!-- developer:start -->

## 👨‍💻 Developer

This React Native app was developed by **Suresh Kumar Meesala**.

| | |
|---|---|
| Developer | [Suresh Kumar Meesala](https://github.com/SureshKumarMeesala) |
| GitHub | [@SureshKumarMeesala](https://github.com/SureshKumarMeesala) |
| Organization | [FreeAppSource](https://github.com/FreeAppSource) |
| Repository | <https://github.com/FreeAppSource/hospadvisor-ios-app> |

<!-- developer:end -->

---

<!-- design-credits:start -->

## 🎨 Design Credits

This app is based on the free **Hospital Adviser iOS App Concept** design by **Uladzislau Luchkouski**, downloaded from Sketch App Sources. All visual design credit goes to the designer. The screens are reproduced from the original Sketch file; fonts that aren't free are replaced with similar Google Fonts, so some details may differ slightly from the original.

| | |
|---|---|
| Designer | [Uladzislau Luchkouski](https://www.sketchappsources.com/contributor/vladlucha) |
| Original design | [Hospital Adviser iOS App Concept](https://dribbble.com/shots/11611527-Hospadviser) |
| Downloaded from | [Sketch App Sources](https://www.sketchappsources.com/free-source/4445-hospital-advisor-ios-hospital-patient-app-sketch-freebie-resource.html) |
| Dribbble | <http://www.dribbble.com/vladlucha> |
| Website | <https://www.behance.net/vladlucha> |
| Original file | `hospadvisor-ios-design-uladzislau-luchkouski.sketch` |
| License / usage | Not stated on the page. Free download; give credit (Sketch App Sources Terms). Confirm with the designer before commercial use. The design's About screen shows "© Vluch-design 2018". |

**Attribution:**

> UI design: "Hospital Adviser iOS App Concept" by Uladzislau Luchkouski (https://dribbble.com/shots/11611527-Hospadviser), downloaded from Sketch App Sources (https://www.sketchappsources.com/free-source/4445-hospital-advisor-ios-hospital-patient-app-sketch-freebie-resource.html).

The original design source files are not included in this repository; get them from the links above. This app's **code** is released under the [MIT License](./LICENSE); the visual design remains the designer's (see [NOTICE](./NOTICE)).

Photos, brand logos and avatars inside the design may belong to third parties and are not covered by the designer's permission.

<!-- design-credits:end -->
