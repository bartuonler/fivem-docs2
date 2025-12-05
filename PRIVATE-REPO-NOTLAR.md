# Private Repository ve GitBook

## ⚠️ Önemli Notlar

### Private Repository Kullanımı

GitBook **private repository'lere** erişebilir, ancak bazı kısıtlamalar var:

## ✅ PRIVATE REPO İLE ÇALIŞIR

1. **GitBook'un GitHub'a Erişim İzni Vermelisiniz**
   - GitBook Settings > Integrations > GitHub
   - GitHub bağlantısında **"Private repositories"** iznini vermeniz gerekir
   - Bu izni verdiğinizde private repo'lara erişebilir

2. **Ücretsiz Plan ile Çalışır**
   - GitBook'un ücretsiz planında private repo desteği var
   - Ama bazı özellikler sınırlı olabilir

## 🔒 PRIVATE REPO İÇİN YAPILMASI GEREKENLER

1. **GitHub'da Repository'yi Private Yapın**
   - Repository Settings > "Change repository visibility" > Private

2. **GitBook'da GitHub İzni Verin**
   - GitBook Settings > Integrations > GitHub
   - "Connect GitHub" butonuna tıklayın
   - GitHub'da size izin penceresi açılacak
   - **MUTLAKA "Private repositories" checkbox'ını işaretleyin**
   - İzinleri onaylayın

3. **Repository'yi Import Edin**
   - Artık private repo'yu görebilirsiniz
   - Import edebilirsiniz

## ⚡ ÖNERİLER

### Seçenek 1: Private Repo (Önerilir)
- ✅ Kodunuz gizli kalır
- ✅ GitBook'a erişim için GitHub izni vermeniz yeterli
- ✅ Ücretsiz plan ile çalışır

### Seçenek 2: Public Repo
- ✅ Hiçbir izin gerekmez
- ✅ Herkes görebilir (dokümantasyon için sorun değil)
- ✅ En kolay kurulum

## 🎯 SONUÇ

**Evet, private repository kullanabilirsiniz!**

Sadece:
1. GitHub'da repo'yu private yapın
2. GitBook'da GitHub bağlantısında **"Private repositories" iznini verin**
3. Import edin

**Sorun çıkmaz**, sadece ekstra bir izin adımı var.

## 📝 NOTLAR

- Public repo dokümantasyon için genelde yeterlidir (kod değil, sadece dokümantasyon)
- Private repo daha güvenlidir
- İki yöntem de çalışır, tercih size kalmış

