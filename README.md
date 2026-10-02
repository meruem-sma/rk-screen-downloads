# RK Screen

Windows için ekran paylaşımı ve kullanıcı onayıyla uzaktan destek uygulaması.

**Beta 1 · 1.0.0-beta.1 · Windows x64 · Taşınabilir**

[Taşınabilir sürümü indir](https://github.com/meruem-sma/rk-screen-downloads/releases/download/v1.0.0-beta.1/RK-Screen-Portable-1.0.0-beta.1.exe) · [Sürüm notları](https://github.com/meruem-sma/rk-screen-downloads/releases/tag/v1.0.0-beta.1) · [Web sitesi](https://rkscreen.com.tr)

## Kullanım

1. Releases bölümünden taşınabilir EXE dosyasını iki Windows bilgisayarına indirin. Kurulum paketi gerektirmez.
2. Uygulamayı açın; ekranını paylaşacak kişinin cihaz kimliğini bağlantı alanına girin.
3. Ekranını paylaşan kişi isteği ve izinleri onayladığında oturum başlar.
4. İşiniz bittiğinde uygulamadaki bağlantıyı bitirme düğmesini kullanın.

## Özellikler

- Ekran paylaşımı ve izin verilen oturumlarda klavye/fare kontrolü.
- Ağ ve işlemci koşullarına göre uyarlanan kalite profilleri.
- Adlandırılmış işaretçiler, sohbet ve dosya aktarımı.
- Kullanıcı tarafından yönetilen pano ve kontrol izinleri.
- Koyu arayüz ve bağlantı durum göstergeleri.

## Beta sınırları

Bu sürüm test amaçlıdır. İki fiziksel bilgisayarda farklı ağlarda uzun süreli kullanım doğrulaması tamamlanmadı. Gerçek çözünürlük, FPS ve gecikme ağ ile donanım koşullarına bağlıdır; sabit FPS garantisi yoktur.

Uygulama henüz kod imzalama sertifikasına sahip değildir; Windows tanınmayan yayıncı uyarısı gösterebilir. Yönetici uygulamaları ve UAC güvenli masaüstü normal kullanıcı yetkisiyle kontrol edilemeyebilir.

Bağlantı kurulumu genel PeerJS/STUN/TURN hizmetlerine bağlıdır. Özel bağlantı altyapısı ve doğrulanmış cihaz kimliği henüz sunulmaz. Bağlantı isteğini yalnızca tanıdığınız kişiler için onaylayın. Bağımsız güvenlik denetimi tamamlanmış değildir.

## Dosya doğrulama

Yayınla birlikte verilen `SHA256SUMS.txt` dosyası EXE'nin SHA-256 değerini içerir. PowerShell'de indirdiğiniz dosyayı kontrol edebilirsiniz:

```powershell
Get-FileHash .\RK-Screen-Portable-1.0.0-beta.1.exe -Algorithm SHA256
```

## Bu depo hakkında

Bu depo yalnızca yayın dosyaları ve sürüm açıklamaları içindir; uygulamanın kaynak kodunu içermez. Açık kaynak lisansı verilmemiştir. GitHub'ın otomatik oluşturduğu “Source code” arşivleri yalnızca bu deponun belgelerini içerir; uygulamayı çalıştırmak için EXE dosyasını indirin.

Hata bildirirken uygulama sürümünü, Windows sürümünü ve sorunu yeniden oluşturma adımlarını yazın. Özel dosyalarınızı, cihaz kimliğinizi veya oturum bilgilerinizi herkese açık paylaşımlara eklemeyin.
