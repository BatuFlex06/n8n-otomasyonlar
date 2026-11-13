# n8n Otomasyonları – Otomasyon Atölyesi

[Otomasyon Atölyesi](https://www.youtube.com/@OtomasyonAtolyesiTR) YouTube kanalındaki videolarda adım adım kurduğumuz n8n akışları. Hepsi ücretsiz, Türkçe ve kod yazmadan kullanılabilir.

| Bölüm | Akış dosyası | Video |
|---|---|---|
| 101 · İlk otomasyonun: sipariş formu → Google Sheets → Gmail | [101-siparis-formu-sheets-gmail.json](101-siparis-formu-sheets-gmail.json) | https://youtu.be/CtwON1UF75c |
| 102 · Yapay zeka ile Gmail e-postalarını ayır, cevap taslağı yazdır | [102-gmail-yapay-zeka-cevap-taslagi.json](102-gmail-yapay-zeka-cevap-taslagi.json) | https://youtu.be/TlLWzEapbbo |

## Nasıl kullanılır?
1. İstediğin `.json` dosyasını aç ve **Download raw file** ile indir.
2. n8n'de yeni bir workflow aç, sağ üstteki **...** menüsünden **Import from File** seç ve dosyayı yükle.
3. Gmail, Google Sheets, OpenAI gibi node'larda **kendi hesabını bağla**. Dosyalarda hiçbir hesap bilgisi yok.
4. Google Sheets node'undaki `TABLO_ID` yerine kendi tablonun linkini yaz.
5. Önce test et, sonra akışı **Active** yap.

Yeni akışlar her hafta yeni videoyla birlikte eklenir. Soruların için videonun altına yorum yazabilirsin.
