# GitBook Import Sorunu Çözümü

## 🔴 Sorun

GitBook ZIP dosyasını kabul etmiyor: "Content type not supported"

## ✅ Çözüm Yöntemleri

### Yöntem 1: GitHub ile Import (ÖNERİLEN)

1. **GitHub'da repository oluşturun**
   - https://github.com → New repository
   - Repository adı: `tebex-gitbook`
   - Public seçin

2. **Dosyaları GitHub'a yükleyin**
   - Repository'de "uploading an existing file" tıklayın
   - Tüm dosyaları sürükle-bırak
   - Commit yapın

3. **GitBook'da GitHub'ı bağlayın**
   - GitBook.com → Settings → Integrations
   - GitHub'ı seçin ve bağlayın
   - Repository'nizi import edin

### Yöntem 2: Manuel Dosya Yükleme

1. **GitBook'da yeni Space oluşturun**
2. **Her dosyayı tek tek yükleyin:**
   - book.json
   - README.md
   - SUMMARY.md
   - styles/website.css klasörünü oluşturup CSS'i yükleyin

### Yöntem 3: GitBook CLI Kullanın

```bash
# GitBook CLI kurun
npm install -g gitbook-cli

# Projeye gidin
cd "C:\Users\Monster\Desktop\Tebex-GitBook"

# Build yapın
gitbook install
gitbook build

# _book klasörünü bir web sunucusuna yükleyin
```

## 🎯 En Kolay: GitHub Import

GitHub ile import yapmak en garantili yöntemdir ve otomatik güncellemeler de yapılabilir.

