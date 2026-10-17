# KP Keshav Player - Android (APK)

Same app as the Windows EXE (same screen, scenes, media, PDF, YouTube, transitions, audio mixer, profiles),
running fully on the phone. No PC needed.

## APK banavvano sauthi saral rasto (Android Studio vagar) - GitHub
1. github.com par free account -> **New repository** (Private chalse).
2. Aa folder ni badhi files upload karo (**.github** folder sathe!).
3. Repository -> **Actions** tab -> "Build APK" -> **Run workflow**. 3-5 minute.
4. Run khule -> neeche **Artifacts** -> `KPKeshavPlayer-APK` download -> zip ma `KPKeshavPlayer.apk`.
5. Phone ma APK kholo -> "Install unknown apps" allow -> Install.

## Android Studio thi
File > Open > aa folder -> Gradle sync -> Build > Build APK(s).

## Projector connect karvana 3 raste
| Rasto | Kya kaam kare | Phone par shu dekhay |
|---|---|---|
| **1. External display** (HDMI/USB-C adapter ke Miracast/Cast jyare Android "second display" aape) | app aapoaap second screen par stage kholse | phone par control, projector par fakt stage |
| **2. This phone screen** (Options > Projection screen > "This phone screen") | phone ni screen full-screen stage bane; phone Cast/mirror thi projector par jay | projector par stage; phone par tap karo -> nanu bar (prev / play / next / black / mute / Exit) |
| **3. Projector/TV browser** (Options ma "Projector browser" link) | smart projector/TV/stick na browser ma link kholo (same Wi-Fi / phone hotspot) | phone par control, projector par fakt stage |

Bijo phone remote: Options > "Phone remote" QR scan -> bija phone thi scene/next/prev/volume/upload.

## Limits (imandari thi)
- Redmi 9 Power / Galaxy A04 ma USB-C thi seedho HDMI video out hoy ej nahi - rasto 2 ke 3 vapro, ke Miracast support karta projector.
- Windows ni "separate window" (pop-out) feature phone ma nathi. Baaki features UI ma che.
- MKV/MOV/FLAC playback phone na WebView par depend kare; MP4 (H.264) + MP3/AAC sauthi safe.
- YouTube mate internet joie; ketlak video embed block kare che.
- Live program pehla badhu ek vaar test karo.
