# RK Screen

Windows için ekran paylaşımı ve kullanıcı onayıyla uzaktan destek uygulaması.

**Beta 1 · 1.0.0-beta.1 · Windows x64 · Kurulum**

**Windows 11 uyumluluk notu (6 Ekim 2026):** Mevcut Beta 1 imzasızdır. Akıllı Uygulama Denetimi uygulamanın açılmasını tamamen engelleyebilir; imzalı paket henüz yayımlanmadı. Yeniden indirme veya güvenli mod bu engeli çözmez. Windows güvenlik korumalarını açık bırakın.

[Windows kurulumunu indir](https://github.com/meruem-sma/rk-screen-downloads/releases/download/v1.0.0-beta.1/RK-Screen-Setup-1.0.0-beta.1.exe) · [Sürüm notları](https://github.com/meruem-sma/rk-screen-downloads/releases/tag/v1.0.0-beta.1) · [Web sitesi](https://rkscreen.com.tr)

## Kullanım

1. Releases bölümünden setup dosyasını iki Windows bilgisayarına indirin ve kurulum adımlarını tamamlayın.
2. Masaüstündeki RK Screen kısayolunu açın; ekranını paylaşacak kişinin cihaz kimliğini bağlantı alanına girin.
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
Get-FileHash .\RK-Screen-Setup-1.0.0-beta.1.exe -Algorithm SHA256
```

## Bu depo hakkında

Bu depo yalnızca yayın dosyaları ve sürüm açıklamaları içindir. Uygulamanın güncel kaynakları [MIT lisansıyla ayrı kaynak deposunda](https://github.com/meruem-sma/rk-screen) yayımlanır. GitHub'ın bu indirme deposunda otomatik oluşturduğu “Source code” arşivleri yalnızca belgeleri içerir.

### Code signing policy

[Kod imzalama politikası](https://github.com/meruem-sma/rk-screen/blob/main/CODE-SIGNING-POLICY.md) ve [gizlilik bilgileri](https://github.com/meruem-sma/rk-screen/blob/main/PRIVACY.md) kaynak deposundadır. Ücretsiz SignPath Foundation yolu için hazırlık yapıldı; başvuru kabulü veya imzalı yeni EXE henüz yoktur. 6 Ekim 2026'da dağıtım setup olarak yenilendi; paket hâlâ imzasızdır. Kurulum biçimini değiştirmek Windows güven değerlendirmesini kaldırmaz.

Hata bildirirken uygulama sürümünü, Windows sürümünü ve sorunu yeniden oluşturma adımlarını yazın. Özel dosyalarınızı, cihaz kimliğinizi veya oturum bilgilerinizi herkese açık paylaşımlara eklemeyin.
