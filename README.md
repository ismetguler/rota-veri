# rota-veri

Rota uygulamasının okuduğu veri dosyası.

`veri.json` içinde:

- `siradakiDers`: sıradaki ders numarası
- `tekrar`: bitmiş derslerin tekrar soruları (`ders`, `soru`, `cevap`)
- `ilanlar`: staj ilanları (`id`, `ad`, `sirket`, `tur`, `sonTarih`, `link`)

Tarihler `YYYY-AA-GG` biçimindedir. Son tarihi bilinmeyen ilanlarda `sonTarih` değeri `null` olur.
