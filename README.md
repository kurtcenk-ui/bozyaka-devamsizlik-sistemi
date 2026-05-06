# Devamsızlık Takip Sistemi

## Giriş

Admin:
- Mail: `cnkkrt@gmail.com`
- Şifre: `Ck5272591!`

Öğretmen:
- `Öğretmen Üye Ol` ekranından mail ve şifreyle kayıt olur.
- Öğretmenler veri yükleyemez, öğrenci ekleyemez/silemez.
- Öğretmenler görüntüleme ve Excel çıktı alabilir.

## Netlify

Bu klasörü GitHub reposuna yükleyin. Netlify'da GitHub reposunu seçip deploy edin.

## Not

Bu sürüm Firebase/Netlify Identity kullanmaz. Kullanıcılar tarayıcı localStorage içinde tutulur.
Gerçek merkezi kullanıcı yönetimi istenirse backend gerekir.


## data.json ile yayınlama
Admin devamsızlık Excelini yükledikten sonra **Site Verisini JSON İndir** butonuna basar. İnen `data.json` dosyası GitHub repo kök dizinine yüklenir ve eski `data.json` üzerine yazılır. Netlify otomatik deploy sonrası öğretmenler aynı veriyi görür. Excel dosyasını GitHub’a yüklemeye gerek yoktur.
