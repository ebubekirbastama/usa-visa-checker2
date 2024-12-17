
Vize Randevu Takip Botu

Bu Python betiği, Amerika Birleşik Devletleri'ne yapılan vize başvurularının randevu tarihlerindeki değişiklikleri izlemek için kullanılır.
Belirli bir web sitesindeki vize randevu sayfasını sürekli olarak kontrol eder ve yeni randevu tarihleri mevcut olduğunda, Telegram botu aracılığıyla bildirim gönderir.

### Özellikler:
- Web sitesindeki randevu tarihlerini periyodik olarak kontrol eder.
- Yeni randevu tarihleri bulunduğunda, Telegram botu aracılığıyla bildirim gönderir.
- Hata durumunda tekrar denemek için 10 dakika bekler.
- Her 5 dakikada bir vize randevusu sayfası kontrol edilir.

### Gereksinimler:
- `requests`: HTTP istekleri için.
- `beautifulsoup4`: HTML verisini işlemek için.
- `time`: Zamanlama işlemleri için.

### Kullanıcı Bilgileri:
1. **USERNAME** ve **PASSWORD**: Sisteme giriş yapabilmek için gerekli bilgiler.
2. **TELEGRAM_BOT_TOKEN** ve **CHAT_ID**: Telegram botu üzerinden bildirim gönderebilmek için gerekli bilgiler.

### Kullanım:
1. Python ortamınızı hazırlayın ve gerekli kütüphaneleri yükleyin:
   ```bash
   pip install requests beautifulsoup4
   ```
2. Botunuzu ve Telegram kanalınızı ayarlayın.
3. Kullanıcı adı, şifre, bot token ve chat id bilgilerini doğru şekilde girin.
4. Betiği çalıştırarak, vize randevularını izlemeye başlayın.

### Uyarılar:
- Bu betik sürekli olarak web sayfasını kontrol eder. Bu nedenle, web sitesindeki değişikliklerin hızına göre API taleplerinizde sınırlandırmalar olabilir.
- Çalışma sırasında oluşabilecek hatalar için hata mesajları Telegram üzerinden gönderilecektir.

