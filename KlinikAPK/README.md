# Kişilik Testi — Android Studio Kurulum Rehberi

## Gereksinimler
- Android Studio (ücretsiz): https://developer.android.com/studio
- Java JDK (Android Studio ile birlikte gelir)

## Adımlar

### 1. Android Studio'yu Aç
- File → Open → Bu klasörü seç (KlinikAPK)
- "Trust Project" dersen Gradle sync başlar (~2-3 dakika)

### 2. APK Derle
- Menüden: Build → Build Bundle(s) / APK(s) → Build APK(s)
- Derleme biter (1-2 dk), sağ altta "locate" linki çıkar
- APK yolu: `app/build/outputs/apk/debug/app-debug.apk`

### 3. Telefona Kur
**USB ile:**
- Telefonu USB ile bağla
- Geliştirici seçeneklerini aç (Ayarlar → Hakkında → Derleme no'ya 7 kez bas)
- USB hata ayıklama aç
- Android Studio'da Run → Run 'app'

**APK dosyası ile:**
- APK dosyasını telefona kopyala (WhatsApp, e-posta, USB vb.)
- Dosya yöneticisinden aç
- "Bilinmeyen kaynaklardan kur"a izin ver

## Notlar
- localStorage çalışır (sorular ve ayarlar kaydedilir)
- İnternet bağlantısı gerekmez
- Minimum Android 5.0 (API 21)
