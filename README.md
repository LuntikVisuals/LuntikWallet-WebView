# LuntikWallet WebView APK

HTML/CSS/JS crypto wallet interface packaged as Android APK using WebView.

**Black · Red · White** accent colors.

## Features
- Full-screen WebView loads local `assets/index.html`
- Offline capable
- JavaScript enabled
- Modern dark theme

## Build
Push to main → GitHub Actions builds debug APK automatically.

Download from Actions → Artifacts or Releases.

applicationId: `com.luntik.wallet`

## Structure
- `app/src/main/assets/` — your HTML/CSS/JS
- `app/src/main/java/com/luntik/wallet/MainActivity.java` — WebView shell
