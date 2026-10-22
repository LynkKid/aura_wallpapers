# Privacy Policy & Terms of Use — AuraWall AI

**Effective Date:** October 22, 2026  
**Public URL:** `https://lynkkid.github.io/aura_wallpapers/privacy-policy.html`  
**Terms of Service URL:** `https://lynkkid.github.io/aura_wallpapers/terms-of-service.html`  
**Support & Privacy Contact:** `lynk.kid.gappmota@gmail.com` / `lynk.kid.hva@gmail.com`

---

## 1. Data Collection & Processing
- **No Personal Data Collection:** AuraWall AI does not require account registration and does not collect, sell, rent, or transmit your name, email address, phone number, contacts, or precise geographic location.
- **Local On-Device Storage (`SharedPreferences`):**
  - Saved Favorites (`aurawall_favorite_ids_v1`)
  - Smart Auto-Changer preferences (`aurawall_auto_enabled_v1`, `aurawall_auto_interval_hours_v1`, `aurawall_auto_source_v1`, `aurawall_auto_target_v1`, `aurawall_auto_updated_utc_v1`)
  - Cached catalog metadata (`aurawall_cached_catalog_json_v3_thumbs`)
  - Content feedback / report logs (`aurawall_reported_items_v1`)
- **Device Motion Sensors:** Gyroscope and accelerometer readings are processed strictly in-memory on your device to render real-time 4D Parallax effects. Sensor streams are never recorded or transmitted off-device.

## 2. Media & Photo Library Permissions
- **Android (`minSdk 29` / Android 10+):** Uses scoped `MediaStore` write operations (`Pictures/AuraWall`) and `WallpaperManager`. No `READ_MEDIA_IMAGES` or `WRITE_EXTERNAL_STORAGE` permissions are requested.
- **iOS (`iOS 14.0+`):** Requests write-only Photo Library access (`PHPhotoLibrary.requestAuthorization(for: .addOnly)`) via `NSPhotoLibraryAddUsageDescription` to export 4K UHD wallpapers to your Photo Library without reading your personal photos. Because iOS does not provide a public API for third-party apps to silently change the system Lock or Home Screen wallpaper, exported images on iOS are saved to the Photo Library so you can apply them via **iOS Settings > Wallpaper**.

## 3. Data Retention & User Deletion Rights
- All user preferences, favorite lists, and local report logs remain strictly on your device until you reset or delete them.
- **How to Reset / Delete Local Data:**
  1. Open **AuraWall AI** -> tap the **Settings (Gear)** icon -> open **Privacy Policy, Terms & Artwork License** -> tap **Clear Local App Data** to reset your Favorites queue and Auto-Changer schedule immediately, OR
  2. Uninstall the application (or clear app storage in OS Settings), which permanently erases all local `SharedPreferences` and `UserDefaults` storage (including cached catalog metadata and local report logs).

## 4. Curated AI Artwork License & Copyright / DMCA
- All 40 4K UHD wallpapers (`2160 × 3840`) and 18 multi-layer parallax assets bundled in AuraWall AI are pre-generated, curated AI artworks owned by AuraWall Studio and embedded with ISO 19566-5 JUMBF (`c2pa.claim`) provenance metadata.
- Users are granted a personal, non-exclusive license to customize their device Lock Screen and Home Screen.
- For copyright/DMCA inquiries or content takedown requests, contact `lynk.kid.gappmota@gmail.com` or use the in-app **Report Content** tool.
