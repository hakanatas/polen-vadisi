# Polen'in Vadisi

Ortaokul Fen Bilimleri dersi için tarayıcıda çalışan, üç boyutlu bir gözlem ortamı. Öğrenciler, saha araştırmacısı bal arısı Polen'in rehberliğinde kiraz çiçekleri açmış bir vadide dört gözlem noktasını geziyor:

1. **Kim kimi besliyor?** Üretici, tüketici, ayrıştırıcı ve besin zinciri
2. **Çiçek meyveye nasıl dönüşür?** Tozlaşma ve çiçekten meyveye geçiş
3. **Bu çakılları kim yuvarladı?** Akarsuyun aşındırması ve biriktirmesi
4. **Su nereden gelip nereye gidiyor?** Su döngüsü ve yükseklikle sıcaklığın değişmesi

**Canlı sürüm:** https://hakanatas.github.io/polen-vadisi/

## Kullanım

Hiçbir kurulum gerekmez; sayfayı açmak yeterli. İlk açılışta Polen kısa bir tanıtım yapar. Tanıtımı başlıktaki **?** düğmesiyle yeniden açabilirsiniz.

- **Gezinme:** Sürükleyerek etrafa bakılır, tekerlekle ya da iki parmakla yakınlaşılır.
- **Klavye:** 1–4 gözlem noktaları, R sıfırla, H arayüzü gizle, T tur, D defter, O öğretmen notları, P sunum modu.
- **Gözlem defteri:** Tahminler, son düşünceler ve kaydedilen görüntüler tek sayfalık bir rapor olarak indirilir. Notlar yalnızca o tarayıcıda saklanır.
- **Sunum modu:** Akıllı tahtada istasyonun sorusunu büyük yazıyla gösterir.
- **Kalite:** Zayıf cihazlarda hafif mod kendiliğinden açılır. Adrese `?q=light` ya da `?q=high` eklenerek sabitlenebilir.

## Gereksinimler

Güncel bir tarayıcı (WebGL desteği) ve internet bağlantısı gerekir. Sayfa şu adreslere erişir:

- `cdn.jsdelivr.net` (three.js)
- `fonts.googleapis.com` ve `fonts.gstatic.com` (yazı tipleri)

Okul ağı bunları engelliyorsa erişime izin verilmesi gerekir.

## Öğretmenler için

Polen'in tüm metinleri, görev adımları, besin zinciri kuralları, yükseklik değerleri ve öğretmen notları `index.html` dosyasının başındaki `POLEN_METINLERI` nesnesinde toplanmıştır. Dosyayı bir metin düzenleyiciyle açıp metinleri değiştirmek yeterlidir.

Öğrenme çıktısı eşleştirmeleri, MEB Türkiye Yüzyılı Maarif Modeli Fen Bilimleri Dersi Öğretim Programı (2026) metnine göre yapılmıştır. Ayrıntılar uygulamadaki **Öğretmen** penceresindedir.

## Geliştirme

Uygulama Claude ile birlikte geliştirildi. Kullanılan prompt ve geliştirme istekleri [`PROMPT.md`](PROMPT.md) dosyasındadır.

## Lisans ve atıf

Bu uygulama FTC #24230 AG Robotik takımı tarafından geliştirilmiştir.

© 2026 Hakan Ataş ve FTC #24230 AG Robotik takımı. [CC BY-NC 4.0](LICENSE) ile lisanslanmıştır. Atıf yapılarak ve ticari olmayan amaçlarla paylaşılabilir ve uyarlanabilir.
