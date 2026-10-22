# Çatı ustası sitesi

`index.html` ana sayfadır ve beş tasarımı listeler. Her tasarım kendi klasöründe, tek dosyadır, sunucu gerektirmez:

| Klasör | Tasarım |
|---|---|
| `1-usta/` | Sıcak, kişisel, kiremit rengi |
| `2-santiye/` | Koyu zemin, ikaz sarısı, çatı katmanları bölümü |
| `3-hizli-fiyat/` | Lacivert, WhatsApp'a fotoğraf gönderen hızlı fiyat kartı |
| `4-premium/` | Grafit ve bronz, malzemeler ve garanti belgesi |
| `5-mahalle/` | Açık, illüstrasyonlu, "Sorununuz hangisi?" kartları |

`onizleme/` ana sayfadaki ekran görüntüleridir. `taslaklar/` ilk üç taslağın eski halleridir, artık kullanılmıyor.

## Yayına almadan önce değiştirilecekler

Beş dosyada da aynı örnek değerler kullanıldı. Bul-değiştir ile güncellenebilir:

| Örnek | Ne ile değişecek |
|---|---|
| `Kemal Arslan`, `Kemal Usta` | Ustanın adı |
| `0532 000 00 00` | Görünen telefon |
| `905320000000`, `+905320000000` | Linklerdeki telefon (başında 90, boşluksuz) |
| `Bursa` ve ilçe listesi | Şehir ve hizmet verilen ilçeler |
| `2004`, `20 yıl`, `600+` | Gerçek yıl ve iş sayısı |
| `5 yıl` garanti | Verilen garanti süresi |
| `4,9` / `87 değerlendirme` ve yorumlar | Google profilindeki puan ve yorumlar |
| `https://www.ornek-alanadi.com/` | Sitenin alan adı |

Seçilen site yayına alınırken en üstteki "Diğer tasarımlara bak" çubuğunu silin (`<!--TASARIMLAR-->` ile `<!--/TASARIMLAR-->` arası ve `<head>` içindeki `<!--TASARIMLAR-STIL-->` bloğu).

## Fotoğraflar

Fotoğrafları ilgili sitenin `img/` klasörüne şu adlarla koyun. Fotoğraf yoksa kiremit desenli yer tutucu görünür.

- `usta.jpg` — çatıda çekilmiş portre, dikey (4:5), en az 800×1000
- `kapak.jpg` — yalnızca 4-premium: bitmiş bir çatının dikey fotoğrafı
- `is-1-once.jpg`, `is-1-sonra.jpg` … `is-3-once.jpg`, `is-3-sonra.jpg` — kare, en az 600×600 (4-premium'da bunun yerine `is-1.jpg` … `is-3.jpg`, yatay)
- `paylasim.jpg` — WhatsApp'ta link paylaşılınca çıkan görsel, 1200×630

Önce/sonra altındaki yazıları (ilçe, iş türü, m², süre) gerçek işlere göre güncelleyin.
