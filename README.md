# Expanding Cards Layout

CSS geçişleri (transitions) ve JavaScript etkileşimleri kullanılarak geliştirilmiş, görsel odaklı interaktif **Genişleyen Kartlar (Expanding Cards)** bileşeni. Kartlardan birine tıklandığında ilgili kart yumuşak bir animasyonla genişlerken diğer kartlar daralarak odağı seçili içeriğe toplar.

---

## 📸 Önizleme

<img width="1093" height="798" alt="Animasyonlu Açılan Kartlar - Google Chrome 2026-08-23 at 1 43 11 PM" src="https://github.com/user-attachments/assets/279debd5-f948-42cf-8b35-de4d28958dfe" />


---
## 🚀 Özellikler

* **Dinamik Sınıf Yönetimi (`active` Class):** JavaScript event listener yapısı ile tıklanan karta dinamik olarak aktiflik sınıfı eklenir ve diğerlerinden kaldırılır.
* **Akıcı CSS Animasyonları:** `flex` ve `transition` özellikleri kullanılarak kart genişlemeleri donma olmadan, donanım ivmelenmeli (hardware-accelerated) şekilde gerçekleşir.
* **Tam Responsive Tasarım:** Mobil cihazlarda dikey (column), geniş ekranlarda yatay (row) esnek düzen (Flexbox) geçişi.
* **Erişilebilirlik ve Performans:** Harici hiçbir kütüphane (jQuery, Bootstrap vb.) kullanılmadan, minimum JavaScript ve CSS yüküyle maksimum performans.

---

## 🛠️ Teknolojik Mimari

* **HTML5:** Semantik yapı ve veri öznitelikleri (`data-attributes`).
* **CSS3:** 
  * `flex-grow` / `flex` oranları ile kart boyutlandırma
  * `transition: all 0.7s ease-in-out` ile yumuşak geçişler
  * Media Queries ile cihaz uyumluluğu
* **Vanilla JavaScript (ES6+):** 
  * `querySelectorAll` ile DOM elemanlarının tespiti
  * `forEach` ve `addEventListener` ile olay yönetimi

---

## 📂 Proje Dosya Yapısı

```text
expanding-cards/
│
├── assets/
│   └── preview.png       # README ekran görüntüsü
├── index.html            # İskelet yapı
├── style.css             # Flexbox ve animasyon kuralları
├── script.js            # Tıklama ve active sınıfı mantığı
└── README.md             # Proje dokümantasyonu





