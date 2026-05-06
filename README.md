---

## ⚠️ Önemli Notlar

*   **Antivirüs Uyarıları:** Uygulama, pencereleri kontrol etmek için `window.activate` ve `ctrl+w` komutlarını kullandığından bazı antivirüs programları tarafından "şüpheli" olarak işaretlenebilir. Bu tamamen güvenlidir, kaynak kodları yukarıda açıktır.
*   **Kapatma:** Programı kapatmak isterseniz sağ alttaki SMY ikonuna sağ tıklayıp "Çıkış" diyebilir veya Görev Yöneticisi'nden işlemi sonlandırabilirsiniz.

---

## 🎯 Hedef
Bu proje **Gazi MTAL Bilişim Bölümü** hedefiyle yola çıkan bir öğrenci tarafından, tüm kader arkadaşları için geliştirilmiştir. 

**"Zeka, disiplinle birleştiğinde başarı kaçınılmazdır."**

---

## 👨‍💻 Yapımcı]
Mehmet Kerem / Wekstra - https://github.com/wekstratr

---
*(Bu proje eğitim amaçlıdır ve ders çalışma verimliliğini artırmak için tasarlanmıştır.)*

---

# 🚀 SMY - Sosyal Medya Yasağı (Big Sınav Edition)

**SMY**, özellikle LGS ve YKS gibi kritik sınav dönemlerinde öğrencilerin odaklanmasını sağlamak amacıyla geliştirilmiş, "irade destekleyici" bir açık kaynaklı otomasyon aracıdır. Bilgisayar başında ders çalışırken elin alışkanlıkla sosyal medyaya giderse, SMY senin yerine o sekmeyi imha eder ve sana hedefini hatırlatır!

---

## ✨ Özellikler

*   **🕵️ Görünmez Pusu:** Arka planda sessizce çalışır, sistem kaynaklarını tüketmez.
*   **🎯 Nokta Atışı İnfaz:** Sadece yasaklı sekmeyi (Instagram, Shorts, TikTok vb.) kapatır; diğer ders sekmelerine dokunmaz.
*   **🔴 Agresif Uyarı:** Sekme kapandığı an ekrana titreyen, animasyonlu ve "vicdan azabı" çektiren özel bir HTML sayfası fırlatır.
*   **🦾 Otomatik Başlangıç:** Bir kez çalıştırıldığında kendini Windows Başlangıç (Startup) klasörüne kopyalar, PC her açıldığında aktif olur.
*   **📥 Sistem Tepsisi Entegrasyonu:** Sağ alt köşedeki (System Tray) ikonu üzerinden yönetilebilir.
*   **🛠️ GitHub Entegrasyonu:** İlk kurulumda yapımcının diğer projelerine göz atmanız için sizi yönlendirir.

---

## 🛠️ Kurulum ve Kullanım

### 1. Hazır Versiyon (EXE)
Eğer Python ile uğraşmak istemiyorsan:
1.  [Releases](../../releases) sekmesinden en güncel `SMY_Pro.zip` dosyasını indir.
2.  Zipli dosyayı bir klasöre çıkart (Önemli: `index.html` ve `.exe` aynı klasörde olmalı).
3.  `SMY_Pro.exe` dosyasını çalıştır.
4.  Ekranda "Kuruldu" mesajını gördüysen artık güvendesin!

### 2. Kaynak Koddan Çalıştırma
Geliştiriciysen veya kodu incelemek istersen:
```bash
# Kütüphaneleri yükle
pip install pygetwindow pyautogui pystray pillow

# Scripti çalıştır
python SMY_Pro.pyw
