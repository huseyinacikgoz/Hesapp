# Katkıda Bulunma Rehberi

Hesapp projesine katkıda bulunmak istediğiniz için teşekkür ederiz! Bu belge, projeye nasıl katkıda bulunabileceğinizi açıklar.

## 🚀 Başlangıç

1. Projeyi fork edin: [github.com/huseyinacikgoz/Hesapp](https://github.com/huseyinacikgoz/Hesapp/)
2. Yerel ortamınızda klonlayın:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Hesapp.git
   cd Hesapp
   ```
3. Yeni bir branch oluşturun:
   ```bash
   git checkout -b feature/amazing-feature
   ```

## 📝 Kod Standartları

### Genel Kurallar

- **Kod Stili**: Mevcut kod stilini takip edin
- **Yorumlar**: Karmaşık mantık için açıklayıcı yorumlar ekleyin
- **İsimlendirme**: Açıklayıcı değişken ve fonksiyon isimleri kullanın
- **Modülerlik**: Yeni özellikler için ayrı modüller oluşturun

### JavaScript

- ES6+ özelliklerini kullanın
- Modül yapısını koruyun (`import`/`export`)
- Async/await tercih edin
- Hata yönetimi için try-catch kullanın

### Güvenlik

- **XSS Koruması**: Tüm kullanıcı girdilerini `escapeHtml()` ile temizleyin
- **Input Validation**: Tüm girdileri doğrulayın
- **Şifreleme**: Mevcut şifreleme standartlarını koruyun (AES-GCM, PBKDF2)

## 🔧 Geliştirme Ortamı

### Yerel Sunucu

```bash
# Python ile
python3 -m http.server 8080

# veya Node.js ile
npx http-server -p 8080
```

Tarayıcıda `http://localhost:8080` adresini açın.

## 🐛 Hata Bildirimi

1. [Issues](https://github.com/huseyinacikgoz/Hesapp/issues) sayfasına gidin
2. Yeni bir issue oluşturun
3. Şu bilgileri ekleyin:
   - Hatanın açıklaması
   - Tekrarlanabilir adımlar
   - Beklenen davranış
   - Gerçek davranış
   - Tarayıcı ve sürüm bilgisi

## ✨ Yeni Özellik Önerisi

1. Önce bir issue açarak özelliği tartışın
2. Geliştirici onayı aldıktan sonra geliştirmeye başlayın
3. Pull Request açarken:
   - Değişiklikleri açıklayın
   - Test sonuçlarını ekleyin
   - Ekran görüntüleri ekleyin (UI değişiklikleri için)

## 📤 Pull Request Süreci

1. Değişikliklerinizi commit edin:
   ```bash
   git commit -m "Add: amazing feature"
   ```

2. Branch'inizi push edin:
   ```bash
   git push origin feature/amazing-feature
   ```

3. GitHub'da Pull Request oluşturun

4. Pull Request şablonunu doldurun:
   - Değişiklik açıklaması
   - Test edildi mi?
   - Breaking changes var mı?

## ✅ Kontrol Listesi

Pull Request göndermeden önce:

- [ ] Kod mevcut stil standartlarına uygun
- [ ] Yorumlar ve dokümantasyon güncel
- [ ] Güvenlik kontrolleri yapıldı (XSS, input validation)
- [ ] Farklı tarayıcılarda test edildi
- [ ] Mobil uyumluluk kontrol edildi
- [ ] Hata yönetimi eklendi
- [ ] Console.log'lar temizlendi (production için)

## 🎯 Öncelikli Alanlar

- Güvenlik iyileştirmeleri
- Performans optimizasyonları
- Erişilebilirlik (accessibility) iyileştirmeleri
- Dokümantasyon geliştirmeleri
- Test kapsamı artırma

## 📚 Kaynaklar

- [Proje Dokümantasyonu](README.md)
- [Güvenlik Raporu](SECURITY_REPORT.md)
- [Kod Yapısı](README.md#proje-yapısı)

## 💬 İletişim

Sorularınız için:
- Issue açın
- Email: mail@huseyinacikgoz.com.tr

---

**Not**: Tüm katkılar [MIT Lisansı](LICENSE) altında lisanslanacaktır.

