# Katkılar

Türkçe yapay zekâ ve [EVREN](https://evren.ssyz.org.tr) ekosistemine yaptığım açık kaynak katkıların listesi. Her madde doğrulanabilir bir bağlantıya dayanır; durumlar aşağıdaki tarih itibarıyladır.

*Son güncelleme: 5 Kasım 2026*

## Upstream katkılar

| Proje | Katkı | Durum |
|---|---|---|
| [speker/evren-sdk](https://github.com/speker/evren-sdk) (EVREN'in resmî Python SDK'sı) | [PR #4](https://github.com/speker/evren-sdk/pull/4): Python 3.10–3.13 matrisinde `pytest` çalıştıran CI iş akışı. Uygulama koduna dokunmaz, secret gerektirmez. Fork'ta 4 sürümde 46/46 test geçti. | ✅ Kabul edildi, 4 Kasım 2026'da `main`'e alındı ([49d7101](https://github.com/speker/evren-sdk/commit/49d7101)) |

## Kendi projelerim

| Proje | Ne yapıyor | Doğrulama |
|---|---|---|
| [evren-cookbook](https://github.com/otomuhbulent-ctrl/evren-cookbook) | EVREN için çalışan, test edilmiş Türkçe örnekler. İlk örnek: taranmış Türkçe PDF'e OCR + embedding + rerank ile sayfa atıflı soru-cevap; uydurma atıfları yakalayan denetim. Resmî KVKK metninde (21 sayfa) 5 soruyla doğrulandı: doğru madde/sayfa atıfları ve belgede olmayan sorulara doğru ret. İkinci örnek: EVREN'in Türkçe karar modeli laya ile şikâyet sınıflandırma; 24 elle etiketli kurgusal örnek ve sorular yayımlandı, sonuçlar ve hata örüntüleri olduğu gibi raporlandı. | [CI](https://github.com/otomuhbulent-ctrl/evren-cookbook/actions/workflows/test.yml) (anahtarsız testler) · gerçek EVREN API çıktıları [örnek README'sinde](https://github.com/otomuhbulent-ctrl/evren-cookbook/tree/main/examples/01-pdf-soru-cevap) tarihli olarak |
| [awesome-turkce-ai](https://github.com/otomuhbulent-ctrl/awesome-turkce-ai) | Türkçe yapay zekâ modelleri, veri setleri, araçları ve platformları için derlenmiş liste. | Haftalık [link kontrolü](https://github.com/otomuhbulent-ctrl/awesome-turkce-ai/actions/workflows/link-check.yml) · [aranabilir site](https://otomuhbulent-ctrl.github.io/awesome-turkce-ai/) |

## Yayımlanmış içerik

| İçerik | Tür |
|---|---|
| [EVREN'e Başlangıç Rehberi](https://github.com/otomuhbulent-ctrl/awesome-turkce-ai/blob/main/rehberler/evren-baslangic-rehberi.md) | Adım adım Türkçe rehber: e-Devlet ile giriş, API anahtarı, kullanım şartları, Python ile ilk istek |

## Çalışma yöntemi

Bu projeler yapay zekâ asistanlarıyla (Claude, ChatGPT) birlikte geliştirildi; commit'lerde ortak yazar olarak belirtilir. Kararlar iki asistanın karşılıklı incelemesiyle alındı, her çıktı yayımlanmadan önce test edildi ve gerçek API ile doğrulandı.
