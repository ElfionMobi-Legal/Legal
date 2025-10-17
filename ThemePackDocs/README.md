# GitHub Pages Setup Rehberi

Bu klasör, ThemeAI uygulamasının gizlilik politikası ve kullanım koşulları için GitHub Pages hosting'i içerir.

## 🚀 GitHub Pages Kurulumu

### 1. GitHub Repository Ayarları

1. GitHub repository'nize gidin
2. **Settings** sekmesine tıklayın
3. Sol menüden **Pages** seçin
4. **Source** kısmında **Deploy from a branch** seçin
5. **Branch** olarak **main** seçin
6. **Folder** olarak **/docs** seçin
7. **Save** butonuna tıklayın

### 2. URL Yapısı

GitHub Pages aktif olduktan sonra URL'ler şu şekilde olacak:

- **Gizlilik Politikası**: `https://oguncanlnx.github.io/ThemePack/privacy.html`
- **Kullanım Koşulları**: `https://oguncanlnx.github.io/ThemePack/terms.html`

### 3. Özel Domain (İsteğe Bağlı)

Gelecekte özel domain eklemek isterseniz:

1. Domain satın alın
2. GitHub Pages ayarlarında **Custom domain** kısmına domain adresinizi yazın
3. DNS ayarlarını yapın

## 📁 Dosya Yapısı

```
docs/
├── privacy.html          # Gizlilik politikası
├── terms.html           # Kullanım koşulları
└── README.md           # Bu dosya
```

## 🔄 Güncelleme Süreci

1. HTML dosyalarını düzenleyin
2. Değişiklikleri commit edin
3. GitHub'a push edin
4. Değişiklikler otomatik olarak yayınlanır

## 📱 Android Uygulamasında Kullanım

Android uygulamasında bu URL'ler `Constants.kt` dosyasında tanımlanmıştır:

```kotlin
object Legal {
    const val PRIVACY_POLICY_URL = "https://oguncanlnx.github.io/ThemePack/privacy.html"
    const val TERMS_OF_USE_URL = "https://oguncanlnx.github.io/ThemePack/terms.html"
}
```

## 🎨 Tasarım Özellikleri

- **Responsive Design**: Mobil ve desktop uyumlu
- **Modern UI**: Material Design benzeri tasarım
- **Türkçe Dil Desteği**: Tam Türkçe içerik
- **Kolay Okunabilirlik**: Açık ve anlaşılır format

## 📞 Destek

Herhangi bir sorun yaşarsanız:

- **E-posta**: elfionmobi@gmail.com
- **GitHub Issues**: Repository'de issue açın

---

**Not**: Bu dosyalar ThemeAI uygulamasının yasal gerekliliklerini karşılamak için oluşturulmuştur.
