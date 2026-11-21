# Just In Charge

AC şarjda aracın tam istediğin saatte hedef şarja ulaşması için gereken akımı (amper) hesaplar. Böylece şarj erken bitip araç boşta beklemez ve işgaliye ödemezsin.

- İlk açılışta batarya kapasitesini sorar ve cihazda saklar. Birden fazla araç kaydedilebilir.
- Varsayılanlar: 3 faz, 230 V, %90 verim, 6–32 A.
- Sunucu yok, veri yalnızca kullanıcının tarayıcısında durur.
- PWA: iPhone'da Safari → Paylaş → "Ana Ekrana Ekle".

Hesap: `amper = ceil( kapasite × (hedef − mevcut)/100 / verim / (saat × faz × gerilim/1000) )`

Güncelleme yayınlarken `sw.js` içindeki `VERSION` değerini artır.
