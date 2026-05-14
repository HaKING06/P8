# 📦 Endüstriyel Depo ve Stok Yönetim Sistemi (Proje 8)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green.svg)
![OOP](https://img.shields.io/badge/Mimari-OOP-orange.svg)

İstanbul Kültür Üniversitesi Bilgisayar Programcılığı bölümü "Proje 8" kapsamında geliştirilen bu uygulama, işletmelerin depo ve stok yönetim süreçlerini dijitalleştirmeyi amaçlayan Nesne Tabanlı Programlama (OOP) tabanlı bir masaüstü otomasyonudur.

Koyu gri ve kehribar (amber) tonlarının kullanıldığı "Endüstriyel Tema" arayüzü, depo personeline göz yormayan ve verimli bir çalışma ortamı sunar.

## ✨ Öne Çıkan Özellikler

* **📊 Canlı Depo Dashboard:** Toplam kayıtlı barkod, fiziksel depo stoğu ve tamamlanan sipariş çıkışlarını anlık takip etme imkanı.
* **📦 Ürün ve Envanter Yönetimi:** Depoya yeni ürün (ID, Ad, Başlangıç Stoğu, Fiyat) tanımlama ve mevcut ürünlerin stoğunu artırma işlemleri.
* **🚚 Sipariş ve Çıkış İşlemleri:** Depodan ürün çıkışı yapma, stok düşme ve tüm sipariş geçmişini (Tarih, Adet, Toplam Tutar) log halinde görüntüleme.
* **🎨 Endüstriyel UI Tasarımı:** PyQt5 ile tasarlanmış, gölgelendirme (Drop Shadow) efektlerine sahip modern, akıcı ve tematik kullanıcı arayüzü.

## 🛠️ Kullanılan Teknolojiler & Mimari

* **Dil:** Python
* **Arayüz (GUI):** PyQt5
* **Mimari:** Nesne Tabanlı Programlama (OOP)
    * **Backend Sınıfları:** `Urun` (Envanter), `Siparis` (Çıkış İşlemleri), `DepoMerkezi` (Veri ve İşlem Yönetimi)
    * **Frontend Sınıfları:** Özelleştirilmiş KPI kartları (`KpiCard`) ve sayfa yapıları (`DashboardPage`, `UrunPage`, `SiparisPage`)

## 📸 Ekran Görüntüleri

<img width="1150" height="731" alt="image" src="https://github.com/user-attachments/assets/4ce8301e-f34e-4760-b240-0fba481d7d50" />
<img width="1152" height="733" alt="image" src="https://github.com/user-attachments/assets/b0371a76-f480-4c66-8ba3-d6a75c64450e" />
<img width="1150" height="732" alt="image" src="https://github.com/user-attachments/assets/facb49cc-3f54-4a16-94af-e41e23f55d79" />


## 🚀 Kurulum ve Çalıştırma

Projeyi lokal ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/KULLANICI_ADIN/depo-sistemi.git](https://github.com/KULLANICI_ADIN/depo-sistemi.git)
   cd depo-sistemi

  2. Gerekli kütüphaneleri yükleyin (Arayüz için PyQt5 gereklidir):
     pip install PyQt5
