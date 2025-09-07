# YetkoShop – E-Ticaret Uygulaması

ASP.NET Core MVC ile geliştirilmiş e-ticaret uygulaması.  
Özellikler: ürün/kategori yönetimi, rol tabanlı admin paneli, sepet/checkout, kargo & teslimat hesaplama, yorum aç/kapa, sayfalama vb.

## Özellikler
- Ürün: listele, oluştur, düzenle, sil
- Kategori: hiyerarşik yapı (üst/alt), filtreleme barı
- Sepet & Sipariş: teslimat/kargo opsiyonları ve toplam hesaplama
- Üyelik: giriş/kayıt, roller (Admin/Moderator/User)
- Admin panel: ürünler, kullanıcılar, kategoriler
- EF Core + SQL Server, Migration’lar dahil

## Gereksinimler
- .NET 7/8 SDK
- SQL Server (LocalDB/Express)
- Visual Studio 2022 veya `dotnet` CLI

## Kurulum
1. `appsettings.json` içinde `DefaultConnection` bağlantı bilgisini güncelleyin.
2. Veritabanı oluşturun:
   ```bash
   dotnet ef database update
