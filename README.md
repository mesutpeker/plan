# 10. Sınıf Türk Dili ve Edebiyatı - Meslek Lisesi Mobil Öğretim Kılavuzu

Bu web uygulaması, **Mesleki ve Teknik Anadolu Liselerinde (MTAL)** haftalık **4 saatlik (iki farklı günde 2+2 blok)** Türk Dili ve Edebiyatı dersi okutan öğretmenler için hazırlanmış, mobil uyumlu (Android ve iOS), kompakt ve kullanımı son derece kolay bir dijital kılavuzdur.

## 🚀 Özellikler

- 📱 **Tam Mobil Uyumlu (Android & iOS):** Tek elle kullanıma uygun butonlar, büyük dokunma alanları ve akıcı geçişler.
- 📅 **Hafta Hafta & 2+2 Gün Dağılımı:** 18 haftanın her birinde 1. Gün (2 Saat) ve 2. Gün (2 Saat) ne yapılacağı tek ekranda.
- 📖 **Ders Kitabı Sayfa ve Etkinlik Rehberi:** Hangi sayfanın açılacağı ve hangi adımların izleneceği net belirtilmiştir.
- ✂️ **Etkinlik Eleme / Sadeleştirme:** Meslek lisesi öğrencisini boğan ağır kuramsal sayfaları atlama yönergeleri (kırmızı uyarı kutuları).
- 💡 **Yaratıcı Yazma ve Atölye Önerileri:** Tek tıkla kopyalanabilir sınıf içi mikro yazma, çizgi bant (storyboard) ve podcast fikirleri.
- ✅ **Ders İçi Kontrol Listesi (Checklist):** Ders esnasında işlenen adımları işaretleme (telefonunuzun hafızasında - `localStorage` saklanır).
- 🔍 **Anlık Arama:** "masal", "tamlamalar", "gazel", "podcast", "saf şiir" gibi kavramları anında arayıp ilgili haftaya zıplama.
- 📍 **"Bu Hafta" Butonu:** Takvime göre o haftanın planına otomatik odaklanma.
- 🌓 **Karanlık / Aydınlık Mod:** Gece veya gündüz göz yormayan arayüz.
- ⚡ **Tamamen Çevrimdışı (Offline) Çalışır:** Sıfır dış kütüphane/CDN bağımlılığı, okul atölyelerinde internet çekmese dahi açılır.
- 🖨️ **Yazdırma Desteği:** Sayfa düzenini bozmadan temiz PDF / çıktı alma.

---

## 🌐 GitHub Pages Üzerinden Yayınlama Adımları (2 Dakika)

1. Bu klasördeki dosyaları (`index.html`, `manifest.json`, `sw.js`, vb.) GitHub'da yeni bir depoya (repository) yükleyin:
   ```bash
   git init
   git add .
   git commit -m "10. Sınıf TDE Meslek Lisesi Kılavuzu"
   git branch -M main
   git remote add origin https://github.com/KULLANICI_ADINIZ/tde10-kilavuz.git
   git push -u origin main
   ```
2. GitHub deponuzda **Settings (Ayarlar)** sekmesine tıklayın.
3. Sol menüden **Pages** seçeneğine girin.
4. **Branch** kısmını `main` ve klasörü `/ (root)` seçip **Save** butonuna tıklayın.
5. 1-2 dakika içinde size özel linkiniz hazır olacaktır:  
   `https://KULLANICI_ADINIZ.github.io/tde10-kilavuz/`
6. Telefonunuzun tarayıcısından (Safari veya Chrome) linki açıp **"Ana Ekrana Ekle" (Add to Home Screen)** diyerek bir mobil uygulama gibi kullanabilirsiniz!

---

## ⚖️ Not Baremi Hatırlatması (MEB Mevzuatı)
`Dönem Sınav Puanı = (Yazılı Sınav × 0,70) + (Dinleme Sınavı × 0,15) + (Konuşma Sınavı × 0,15)`
- **1. Sınav:** 5. haftadaki *Şiir Dinletisi* doğrudan Konuşma Sınavı (%15) notudur.
- **2. Sınav:** 16. haftadaki *Edebî Şahsiyet Podcasti* doğrudan Konuşma Sınavı (%15) notudur.
