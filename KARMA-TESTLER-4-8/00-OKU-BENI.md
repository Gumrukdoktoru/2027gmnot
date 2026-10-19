# GM Karma Testler 4–8 (2. seri)

Gümrük Müşavirliği sınavına hazırlık için 5 karma test × 50 soru = **250 özgün soru**. Seri, önceki
GM Karma Test 1–3'ün devamıdır; aynı kapak, bölüm ve gerekçe biçimi kullanılmıştır.

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

Her testte aynı model uygulandı:

| | KT4 | KT5 | KT6 | KT7 | KT8 |
|---|---|---|---|---|---|
| Gümrük Mevzuatı | 22 | 22 | 22 | 22 | 22 |
| Sair Mevzuat | 14 | 15 | 15 | 15 | 15 |
| Tarife | 8 | 7 | 7 | 7 | 7 |
| Hesaplama | 6 | 6 | 6 | 6 | 6 |
| Çok / orta / az / hiç çıkan konu | 30/13/6/1 | 30/13/6/1 | 30/13/6/1 | 30/13/6/1 | 30/13/6/1 |
| Blok düzeni | 2025 tipi | klasik | 2025 tipi | klasik | 2025 tipi |

- **Konu sınıfları** 2021–2025 sınavlarının 500 sorusunun konu konu sayımına dayanır (çok: 5 yılda 10+, orta: 5–9,
  az: 1–4, hiç: 0). Hiç çıkmamış konudan her testte yalnız 1 soru var: KT4 Varış Öncesi İşlemler/YKTS, KT5 Kota ve
  Tarife Kontenjanı, KT6 Sonradan Kontrol, KT7 İhracat Sayılan Satışlar/99/13812, KT8 Şartlı Muafiyet ve Ekonomik
  Etkili Rejimler.
- **Soru tipleri** Soru Tipi Kataloğu'ndaki alt tiplere (O, D, Ö, G, V, K, B, E, S, H) göre dağıtıldı; olumsuz kökler
  **<u>altı çizili ve kalın</u>** yazıldı.
- **Cevap anahtarı** her testte A–E harfleri 10'ar kez olacak şekilde dengelendi; aynı harf en fazla 3 kez üst üste gelir.
- **Blok düzeni:** "2025 tipi" testler 2025 sınavındaki sırayı (Sair – Hesaplama – GM – Tarife – Sair – GM), "klasik"
  testler ders sırasını (GM – Sair – Tarife – Hesaplama) izler.

## Özgünlük

- Sözel sorular, "Konu Sınıfları ve Çıkan Sorulardan Hap Bilgi" dokümanındaki 565 çıkmış bilgi noktasının
  **dışındaki** hükümlerden ("Beklenen Konulardan Hap Bilgi" ve "Sorulmayan Konular Soru–Cevap") yazıldı.
- Daha önce üretilen 3.483 çoktan seçmeli soruyla (GM Deneme 1–3, GM Karma Test 1–3, GM Deneme 1–2 vb.) karşılaştırıldı;
  aynı bilgi noktasını ölçen sorular elendi.
- **Gümrük Mevzuatı Koleksiyonu'ndan yalnız 1 soru** var: **KT6, soru 5** (Ticaret Bakanlığının 15.04.2026 tarihli
  süre durdurma yazısı; cevap D).

## Kalite kontrolü

- Her soru kaynak mevzuattaki madde ve satırla eşleştirildi; dayanak, Bölüm B'deki gerekçenin sonunda "(MD …)" olarak
  verilir.
- 5 testin her biri, cevap anahtarını görmeden çözen bağımsız bir doğrulamadan geçti. 250 sorunun tamamında
  doğrulayıcının cevabı anahtarla uyuştu; anahtarı yanlış çıkan soru olmadı.
- Doğrulamada bulunan sorunlar düzeltildi: uzun doğru şık ve kökteki kelimenin yalnız doğru şıkta tekrarlanması gibi
  ipuçları, eski kurum adları, HS 2022 ile kalkan GTİP'ler, ikinci cevabı savunulabilir kılan ifadeler ve yazım hataları.
- Sorunlu bulunup yeniden yazılan 12 soru ikinci bir bağımsız kontrolden geçti (12/12 uyum). Bu kontrolde iki soruda
  daha ifade düzeltmesi yapıldı: EFTA sorusunda revize PEM'deki "menşe beyanı" terimi ve DFİF sorusunda süre ifadesi.

## Güncellik notları (19.10.2026 itibarıyla)

- **GK 241/1:** Anayasa Mahkemesi 26.03.2026 tarihli kararıyla fıkrayı kısmen iptal etti. Testlerde bu fıkraya dayanan soru yok.
- **Yatırım teşvik:** Güncel rejim 2025/9903 sayılı Karardır; teşvik sorusu bu Karara göre yazıldı. Seri No: 9 Gümrük Genel
  Tebliği hâlâ eski 2009/15199 sayılı Karara atıf yapıyor. Bu Tebliğden yalnız teminatlı ithalattaki teminat hesabı soruldu
  (Tebliğ md. 16/5-b).
- **EFTA:** 1.1.2026'dan itibaren yalnız revize PEM kuralları uygulanıyor. EFTA soruları buna göre kuruldu; eski kurallara
  dayanan dört aylık EUR.1 geçerlilik süresi bilgisi sorulmadı.
- **Posta ve hızlı kargo:** 2022/9 sayılı Genelgenin 2026 değişiklikleri işlenmiş hâli esas alındı.
- **İlave Gümrük Vergisi:** Karar md. 2/3'teki güncel %50 tavanı kullanıldı.
- **Tarife:** HS 2022 ile kalkan alt pozisyonlar (ör. 9405.40) şıklardan çıkarıldı; eski kurum adları geçen yerlerde güncel ad
  da belirtildi.
