# GM Karma Testler 9–14 (3. seri)

Gümrük Müşavirliği sınavına hazırlık için 6 karma test × 50 soru = **300 özgün soru**. Seri, GM Karma Test 1–8'in
devamıdır; kapak, bölüm ve gerekçe biçimi aynıdır.

## Klasör yapısı

| Klasör | İçerik |
|---|---|
| `pdf/` | Yazdırmaya hazır tam test (soru + cevap anahtarı + gerekçeler) ve ayrı soru kitapçığı |
| `docx/` | Aynı dosyaların düzenlenebilir Word sürümü |
| `md/` | Aynı içerik Markdown olarak |
| `veri/` | Her testin soru, şık, cevap ve gerekçe verisi (JSON) |

Her test için iki dosya vardır:
- `KARMA-TEST-n` — Bölüm A (sorular), cevap anahtarı, Bölüm B (her sorunun konusu, sınıfı ve gerekçesi), dağılım
  tabloları ve hafıza güncellemesi.
- `KARMA-TEST-n_SORU-KITAPCIGI` — yalnız sorular. Süre tutarak çözüp sonra tam dosyadan kontrol etmek için.

## Testlerin yapısı

| | KT9 | KT10 | KT11 | KT12 | KT13 | KT14 |
|---|---|---|---|---|---|---|
| Gümrük Mevzuatı | 22 | 21 | 21 | 22 | 22 | 22 |
| Sair Mevzuat | 15 | 15 | 15 | 15 | 15 | 15 |
| Tarife | 7 | 8 | 8 | 7 | 7 | 7 |
| Hesaplama | 6 | 6 | 6 | 6 | 6 | 6 |
| Çok / orta / az / hiç çıkan konu | 30/13/6/1 | 30/13/6/1 | 30/13/6/1 | 30/13/6/1 | 30/13/6/1 | 30/13/6/1 |
| Blok düzeni | 2025 tipi | klasik | 2025 tipi | klasik | 2025 tipi | klasik |

- **Konu sınıfları** 2021–2025 sınavlarının 500 sorusunun konu konu sayımına dayanır (çok: 5 yılda 10+, orta: 5–9,
  az: 1–4, hiç: 0).
- **Hiç çıkmamış konudan** her testte 1 soru var; 2. seride kullanılan beş konu tekrar edilmedi: KT9 Taşıtların
  Giriş-Çıkışı, KT10 E-İhracat Destekleri ve Dış Ticaret Sermaye Şirketi, KT11 Ham Elmas ve CITES, KT12 Kabotaj,
  KT13 Denizyolu Transiti ve İzinli Gönderici, KT14 Akaryakıt Transiti.
- **Soru tipleri** Soru Tipi Kataloğu'ndaki alt tiplere göre dağıtıldı; olumsuz kökler **<u>altı çizili ve kalın</u>**.
- **Cevap anahtarı** her testte A–E harfleri 10'ar kez; aynı harf en fazla 3 kez üst üste.
- **Blok düzeni:** "2025 tipi" testler 2025 sınavındaki sırayı (Sair – Hesaplama – GM – Tarife – Sair – GM), "klasik"
  testler ders sırasını (GM – Sair – Tarife – Hesaplama) izler.

## Özgünlük

- Sözel sorular, "Konu Sınıfları ve Çıkan Sorulardan Hap Bilgi" dokümanındaki 565 çıkmış bilgi noktasının
  **dışındaki** hükümlerden yazıldı.
- Daha önce üretilen **3.733 soruyla** (GM Deneme 1–3, GM Karma Test 1–8, GM Deneme 1–2 vb.; KT4–KT8'in 250 sorusu
  dahil) karşılaştırıldı; aynı bilgi noktasını cevap olarak ölçen sorular elendi ya da yeniden yazıldı.
- **Gümrük Mevzuatı Koleksiyonu'ndan yalnız 1 soru** var: **KT11** (6183 sayılı Amme Alacaklarının Tahsil Usulü
  Hakkında Kanun).

## Kalite kontrolü

- Her sorunun dayanağı kaynak mevzuattaki madde ve satırla eşleştirildi; Bölüm B'deki gerekçenin sonunda "(MD …)".
- 6 testin her biri, cevap anahtarını görmeden çözen bağımsız bir doğrulamadan geçti: 300 sorunun 299'unda
  doğrulayıcının cevabı anahtarla uyuştu. Uyuşmayan tek soruda (hızlı kargo kıymet hesabı) iki cevap savunulabildiği
  için kök düzeltildi.
- Doğrulamada bulunan 18 sorun (ipuçları, tekrar eden çeldiriciler, eski kurum/belge adları, vurgu eksikleri,
  tartışmalı veriler) düzeltildi; daha önce sorulmuş bilgiye dayanan 4 soru yeniden yazıldı.
- Düzeltilen ve yeniden yazılan sorular ikinci bir bağımsız kontrolden geçti.
  Bu ikinci kontrolde 10 sorunun 10'unda cevap anahtarla uyuştu. Testler arasında bilgi sızdıran bir şık da düzeltildi.

## Güncellik notları (27.10.2026 itibarıyla)

- **GK 241/1:** Anayasa Mahkemesinin 26.03.2026 kararıyla kısmen iptal edilen fıkraya dayanan soru yok.
- **Yatırım teşvik:** Güncel rejim 2025/9903 sayılı Karardır; eski Karara atıf yapan tebliğlerden soru sorulan yerlerde
  açıklamada belirtildi.
- **EFTA:** 1.1.2026'dan beri yalnız revize PEM kuralları uygulanıyor; eski "fatura beyanı/4 ay" bilgisi ve eski
  "doğrudan nakliyat" şartı sorulmadı.
- **Kurum adları:** Kaynakta eski ad geçen yerlerde (Müsteşarlık, Çevre ve Orman Bakanlığı, A/B sınıfı statü belgesi
  vb.) güncel durum açıklamada yazılı.
- **Zamana duyarlı bilgi:** STA müzakere durumu gibi değişebilen bilgiler sınav öncesinde Ticaret Bakanlığı
  sayfasından yeniden kontrol edilmelidir.
