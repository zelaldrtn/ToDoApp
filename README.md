# Minimalist To-Do Uygulaması

Bu proje, günlük görevleri tarih ve kategori bazlı olarak organize etmeyi sağlayan, modern ve minimalist tasarıma sahip bir mobil görev yönetim uygulamasıdır. Kullanıcı deneyimini (UI/UX) ön planda tutarak, iş ve kişisel planlamaları kolaylaştırmak amacıyla geliştirilmiştir.

## Öne Çıkan Özellikler & Performans Optimizasyonları

* **Gelişmiş Veri Kalıcılığı:** Görevler, yerel veri tabanı entegrasyonu (SQLite) kullanılarak güvenli bir şekilde saklanır.
* **Asenkron Veri Yönetimi (Async/Await):** Veri tabanı sorguları ve özellikle "Tamamlanan Görevler" listesi asenkron olarak arka planda işlenir. Bu sayede UI thread kilitlenmez, donma/kasma yaşanmadan akıcı bir kullanıcı deneyimi sunulur.
* **Responsive Layout (Esnek Tasarım):** Farklı ekran çözünürlüklerinde elemanların üst üste binmesini engelleyen, dinamik ve esnek arayüz yerleşimleri (Grid & StackLayout) kullanılmıştır.
* **Kategori ve Durum Yönetimi:** Görevler; İş, Kişisel veya özel kategorilere ayrılabilir. Süresi geçen görevler sistem tarihiyle karşılaştırılarak otomatik olarak tespit edilir.

## Kullanılan Teknolojiler

* **Framework:** .NET MAUI / C# (XAML)
* **Veri Tabanı:** SQLite 
* **Tasarım:** Minimalist & Modern UI/UX Standartları
