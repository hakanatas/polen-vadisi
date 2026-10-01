# Polen'in Vadisi: kullanılan prompt

Bu uygulama Claude ile birlikte geliştirildi. Aşağıda, işin çıkış noktası olan prompt (İngilizce bir 3B kiraz çiçeği vadisi promptunun ortaokul Fen Bilimleri dersi için Türkçeye uyarlanmış hâli) ve ardından uygulamayı bugünkü hâline getiren geliştirme istekleri sırasıyla yer alıyor.

---

## 1. Ana prompt

Tarayıcıda gerçek zamanlı gezilebilen, cilalı bir 3B peyzaj deneyimi oluştur:
ortaokul Fen Bilimleri dersinde kullanılacak, bir rehber karakter eşliğinde keşfedilen bir kiraz çiçeği vadisi.

Adı: "Polen'in Vadisi"
Hedef kitle: 5–7. sınıf öğrencileri (10–13 yaş). Sınıfta akıllı tahtada öğretmen yönetiminde
ya da öğrencinin kendi cihazında bireysel olarak kullanılacak.
HTML, CSS ve JavaScript kullan. Görsel üretme, yalnızca tasarım konsepti sunma,
tek bir arka plan görseli ve paralaks efektleriyle sahte 3B yapma. Çalışan, gezilebilen, bitmiş bir ürün istiyorum.
Arayüzdeki ve karakterin konuşmalarındaki tüm metinler Türkçe olacak.

### 【1. Öğretim Amacı】

Bu bir oyun değil, bir gözlem ortamı. Öğrenci vadide dolaşırken şu kavramları sahnedeki somut şeylerde görsün:
- Çiçekli bitkilerde üreme ve tozlaşma (kiraz ağacı, çiçeğin yapısı, arı)
- Ekosistem ve besin ilişkileri (bitkiler, böcekler, balıklar, kuşlar; üretici, tüketici, ayrıştırıcı)
- Su döngüsü (buharlaşma, yoğuşma, yağış, akış; bulut, kar, şelale, akarsu)
- Akarsuyun aşındırma ve biriktirme etkisi (yuvarlaklaşmış çakıllar, kıvrımlı yatak, kıyıda biriken kum)
- Yükseklik arttıkça sıcaklığın düşmesi (zirvelerde kar, eteklerde çiçek)

Bilgiler bilimsel olarak doğru, yaşa uygun ve kısa olsun. Ders kitabı paragrafı yığma;
her kavramı sahnede görülebilen bir nesneye bağla. Puan, altın, can sayacı, rozet gibi oyun öğeleri kullanma.

### 【2. Rehber Karakter: Polen】

Polen, vadide yaşayan genç bir işçi bal arısı ve kendini "saha araştırmacısı" olarak tanıtıyor.
Öğrenciye ders anlatmaz, gözlem yaptırır.

Kişilik:
meraklı, sabırlı, biraz titiz; saymayı, ölçmeyi ve not almayı sever.
Cevabı söylemeden önce soru sorar ("Sence bu çakıllar neden köşeli değil?").
Esprili ama çocuksu değil: "vızzz", "yaşasııın" gibi abartılı ünlemler ve ikilemeler yok.
Öğrenciye "sen" diye hitap eder, cümleleri kısa ve açıktır.

Görünüm (sahnenin modern voksel diliyle uyumlu, ince işçilikli):
- Kehribar sarısı ve koyu kahve çizgili gövde; baş, göğüs ve karın ayrı okunur; altı bacak, iki anten, bileşik gözler
- İki çift yarı saydam kanat; uçarken hızlı ve hafif bir titreşim
- Arka bacaklarında turuncu polen sepetleri (gerçek arı anatomisinden küçük bir bilimsel ayrıntı)
- Tek aksesuar: sırtında küçük bir not defteri. Kostüm ve eşya yığını yok
- Ağacın yanında gerçekçi ölçüde küçük, yakın planda sevimli ve okunaklı; sahneyi asla kapatmayacak boyutta

Davranış:
- İstasyonlar arası geçişte Polen bir sonraki noktaya uçar, kamera onu yumuşakça izler
- Boştayken çiçekler arasında dolaşır, zaman zaman bir çiçeğe konar (tozlaşmayı ima eder)
- Yağmurlu atmosferde uçmayı bırakır, bir yaprağın ya da taş fenerin çatısı altına sığınır
  ve bunun nedenini kendisi söyler (arılar yağmurda pek uçmaz)
- Konuşmaları ekranın kenarında, sade bir altyazı şeridinde ya da konuşma balonunda görünür;
  odak noktasını kapatmaz, tek dokunuşla gizlenebilir
- Tüm diyaloglarını kodun başında tek bir düzenlenebilir veri nesnesinde topla ki öğretmen metinleri kolayca değiştirebilsin

### 【3. Yaratıcı Yön】

İzole bir obje, yüzen ada, kaideli diorama ya da teknik demo değil;
yakın ve uzak planlarda net derinliği olan, bütünlüklü, kesintisiz bir vadi peyzajı oluştur.

Stil modern ve rafine voksel sanatı:
kübik geometrinin görsel dilini koru, ama görüntü yüksek çözünürlüklü, kenar yumuşatmalı ve incelikli ışıklandırılmış olsun.
Retro düşük çözünürlüklü pikselleşme, iri blok yapılar ya da sahneye piksel filtresi kullanma.

Görsel kaliteye öncelik ver. Kompozisyondan, malzemeden ya da ışıktan ödün vermektense daha az özellik koy.

### 【4. Sahne Kompozisyonu】

Sayfa açıldığında, kullanıcı kamerayı çevirmek zorunda kalmadan hemen bütünlüklü ve etkileyici bir kompozisyon görmeli.
Ortografik diorama kamerası değil, perspektif kamera kullan. Ön, orta ve arka plan net olsun:

Ön plan:
belirgin, yaşlı bir kiraz ağacı; kayalar, otlar, bitkiler, bir taş fener ve birkaç düşmüş çiçek.
Görüntünün kenarında doğal bir çerçeve oluştursun; nehri, köprüyü ve ana yapıları kapatmasın.
Polen ilk açılışta bu ağacın çevresinde olsun.

Orta plan:
bakışı sahnenin içine çeken kıvrımlı bir nehir ve üzerinde kırmızı ahşap bir köprü;
arazi boyunca dağılmış küçük bir köy, bir çay evi ve patikalar.
Kıyıda gözle seçilebilen yuvarlak çakıllar ve kum birikintileri olsun (aşınma istasyonu için).
Zemin düz bir düzlem değil; yükselti farkları, kıyı çizgileri ve doğal geçişler olsun.

Arka plan:
yamaçta çok katlı bir pagoda, farklı uzaklıklarda ormanlar, sırtlar ve uzakta karlı dağlar;
dağlardan inen ince bir şelale nehri besliyor olsun (su döngüsü bağlantısı).
Uzaklığı yalnızca küçültmeyle değil; ölçek, örtme, sıcaktan soğuğa renk kayması ve atmosferik perspektifle göster.

Öğeleri sahneye eşit dağıtma. Hiyerarşi, yoğunluk farkı, boş alan ve net bir odak noktası kur.

### 【5. Modelleme ve Görüntü Kalitesi】

Kiraz ağacı:
gövdede kıvrımlar, dallar, çatallanmalar ve görünür kökler olsun; taç düzensiz çiçek kümelerinden oluşsun,
aralarında boşluklar, kalınlık farkları ve görünür dallar bulunsun. Birkaç düzgün küre ya da blok yığınından yapma.
Bir dalda, kiraz istasyonunda yakın plana alınabilecek, daha ayrıntılı tek bir çiçek olsun:
taç yapraklar, erkek organlar (başçıklarıyla) ve ortada dişi organ seçilebilsin.

Yapılar:
çatılarda katmanlı kiremitler, saçaklar, kirişler, sütunlar ve kafes pencereler olsun;
yapılar işlev, ölçek ve yükseklik bakımından farklı olsun. Vadiyi aynı evin kopyalarıyla doldurma.

Arazi:
kıyılarda ıslak kayalar, otlar ve bitki örtüsü geçişleri olsun.
Aşırı düzgün basamaklar, tekrar eden şeritler, dama deseni ve belli olan prosedürel ızgaralardan kaçın.

Su:
yüzey çevresini yansıtsın; ölçülü dalgacıklar, derinlik farkı ve kıyılarda doğal geçişler olsun.
Mümkün olduğunca gerçek sahne yansımaları kullan; performans için kaliteyi düşürürken sonuç inandırıcı kalsın.
Titreyen gürültü, aşırı bozulma ya da düz mavi bir düzlem kullanma.

Canlılar ve ayrıntılar:
birkaç balık, uzakta birkaç kuş, çiçeklerde bir iki böcek, düşen çiçek yaprakları, akşamları ateş böcekleri.
Bunlar ekosistem istasyonunda anlatılacağı için seçilebilir olsunlar, ama görüntüyü kalabalıklaştırmasınlar.

### 【6. Keşif İstasyonları (Dört Kamera Görünümü)】

Her istasyonun kendi kompozisyon değeri olsun; geçişler yumuşak olsun ve Polen kameradan önce oraya uçsun.
Her istasyonda Polen: 1–2 cümlelik bir gözlem + bir "Sence?" sorusu + dokununca açılan kısa bir açıklama.
İlgili nesne sahnede zarifçe vurgulansın (ince bir parlama ya da kontur), ok ve etiket yağmuru olmasın.

1. Vadi Panoraması – "Kim kimi besliyor?"
   Genel bakış. Bitkiler, böcekler, balıklar, kuşlar arasındaki besin ilişkisi; üretici ve tüketici kavramı.

2. Yaşlı Kiraz Ağacı – "Çiçek meyveye nasıl dönüşür?"
   Ayrıntılı çiçeğe yakın plan. Tozlaşma, arının rolü, polen sepetleri.

3. Alçak Nehir Kıyısı – "Bu çakılları kim yuvarladı?"
   Su seviyesine yakın açı. Akarsuyun aşındırması ve biriktirmesi, kıyıdaki canlılar.

4. Tepe Seyir Noktası – "Su nereden gelip nereye gidiyor?"
   Karlı dağları, şelaleyi ve nehri aynı karede gösteren yüksek açı.
   Su döngüsü; yükseldikçe sıcaklığın düşmesi.

İsteğe bağlı, varsayılanda kapalı bir "Bilim Katmanı" düğmesi:
açıldığında su döngüsünü ince, yarı saydam akış çizgileriyle (buharlaşma, bulut, yağış, akış) gösterir.
Kapalıyken sahne tamamen temiz kalır.

### 【7. Renk, Atmosfer ve Hava Durumu】

Üç atmosfer olsun. Geçişte gökyüzü, ortam ışığı, sis ve yerel efektler birlikte değişsin; yalnızca arka plan rengi değil.

- Sabah (varsayılan): akıllı tahta ve projeksiyonda rahat okunacak kadar aydınlık;
  yumuşak pembe çiçekler, taze yeşiller, hafif sabah sisi. Soluk ya da gri görünmesin.
- Mavi Saat: serin tonlu vadi ve dağlar, yumuşak pembe çiçekler, yalnızca yerleşim alanlarında toplanan
  sıcak ama patlamayan fener ve pencere ışıkları; ateş böcekleri.
- Yağmurlu: bulutlu gökyüzü, yağmur, sudaki halka izleri, ıslak yüzeylerde parlaklık, nehirde hafif bulanıklık artışı.
  Polen sığınır. Bu atmosfer su döngüsü istasyonuyla bağlantılı kullanılabilsin.

Yumuşak gölgeler, temas gölgelemesi, dengeli pozlama, ölçülü bloom, kenar yumuşatma
ve uzaklığı hissettiren katmanlı sis kullan.
Soluk/gri görüntü, aşırı doygunluk, tüm sahneyi kaplayan yoğun sis, patlayan ışıklar ve belirgin tırtıklanmadan kaçın.

### 【8. Etkileşim ve Arayüz】

Temel etkileşim:
fareyle sürükleyerek etrafa bakma, tekerlekle yakınlaştırma; dokunmatik ekranlarda sürükleme ve iki parmakla yakınlaştırma.
Görünümü sıfırlama, arayüzü gizleme ve anlık görüntüyü kaydetme düğmeleri olsun
(öğrenci kaydettiği görüntüyü gözlem raporunda kullanabilsin).

İsteğe bağlı:
Polen'in dört istasyonu sırayla gezdiği yavaş bir kamera turu (öğretmen sınıfta başlatıp durdurabilsin);
ortam sesi (su, kuş, yağmur). Ses varsayılan olarak kapalı olsun ve yalnızca kullanıcı açınca çalsın.

Arayüz sade ve özenli olsun; peyzaj önde. Başlık ve kontrol çubuğu kenarlarda dursun, odak noktasını kapatmasın.
Akıllı tahtada uzaktan okunabilecek yazı boyutu ve parmakla rahat basılacak düğme büyüklüğü kullan.
Masaüstü ve mobilde düğmeler görüntü alanında kalsın, metinler üst üste binmesin, tüm kontroller kullanılabilir olsun.
Tipografide Inter, Roboto, Arial, sistem fontları gibi aşırı kullanılmış seçimler yerine karakterli,
Türkçe karakterleri (ç, ğ, ı, İ, ö, ş, ü) eksiksiz destekleyen fontlar seç.
Renkleri CSS değişkenleriyle yönet; beyaz üstü mor gradyan gibi klişelerden kaçın.

### 【9. Mühendislik ve Performans】

Three.js / WebGL ve sürümü sabitlenmiş, birbiriyle uyumlu CDN bağımlılıkları kullanabilirsin.
"Sıfır bağımlılık" uğruna motoru baştan yazma; olgun işleme yeteneklerini tercih et.
Özel HTML, CSS ve JavaScript'i mümkün olduğunca tek bir HTML dosyasında düzenli tut.
Manzarayı ve Polen'i prosedürel geometri ve malzemelerle üret; harici görsel ya da 3B model dosyasına bağımlı olma.

Tekrarlanan nesneler için birleştirme (batching) ya da instanced rendering kullan;
alt bölümleri, gölgeleri, yansımaları ve render çözünürlüğünü uygun yönet.
Yüksek kalite ve hafif mod sun. Okullardaki etkileşimli tahtaların grafik gücü düşük olabileceği için
mobilde ve zayıf donanımda hafif mod otomatik açılsın. Ayrıntıyı voksel sayısını sonsuza artırarak arama.

Yükleme göstergesi, WebGL desteklenmediğinde Türkçe bir uyarı ve gerekli hata yönetimini ekle.
Okul ağında CDN engellenirse ne olduğunu açıklayan anlaşılır bir mesaj göster.
Ses açılmadan otomatik çalmasın; sistemdeki "hareketi azalt" tercihine uy
(bu durumda kanat titreşimi ve kamera turu sadeleşsin).

### 【10. Teslim Öncesi Doğrulama】

Kodu yazar yazmaz teslim etme.

Ortam tarayıcı açıp ekran görüntüsü almayı destekliyorsa önce sayfayı aç;
varsayılan kamerayı, dört istasyonu, Polen'in uçuşunu ve konuşmalarını, üç atmosferi,
Bilim Katmanı'nı, masaüstü ve mobil yerleşimi kontrol et;
ekran görüntülerine göre belirgin kompozisyon, pozlama, örtme ve işleme sorunlarını düzelt.

Özellikle şunlara dikkat et:
boş ekran, yükleme hatası ve konsol hataları;
iç içe geçen geometriler, titreme, gölge lekeleri, aşırı pozlama ve bozuk su;
varsayılan görünümün gerçekten bütünlüklü bir peyzaj gibi görünüp görünmediği;
Polen'in sahnede kaybolmadığı ya da sahneyi kapatmadığı;
bilimsel açıklamaların doğruluğu ve yaşa uygunluğu;
düğmelerin gerçekten çalıştığı ve mobilde ekran sınırları içinde kaldığı.

Doğrulama için tarayıcı ekran görüntüsü kullanabilirsin, ama görsel üretme araçlarını çağırma.
Hangi testlerin yapılamadığını dürüstçe belirt; yapılmamış testleri doğrulanmış gibi gösterme.

Son teslimatlar:
1. Açılabilir gerçek bir HTML dosyası ya da ortamın desteklediği etkileşimli bir önizleme.
2. Mümkünse tarayıcıda alınmış gerçek bir ekran görüntüsü.
3. Kontrollerin ve çalışma koşullarının kısa açıklaması; öğretmenin Polen'in metinlerini nereden düzenleyeceğinin notu.

Yapımı doğrudan tamamla; kritik olmayan ayrıntılarda tutarlı tasarım kararlarını kendin ver,
uygulayabileceğin konularda bana tekrar tekrar soru sorma.

---

## 2. Geliştirme istekleri (sırasıyla)

Ana prompttan sonra uygulama aşağıdaki isteklerle bugünkü hâline geldi:

1. **Yönergeler ve terimler:** "Yönergeler biraz daha net olmalı. Ortaokul öğrencileri için erkek organ, dişi organ gibi terimleri kullanmayalım." Sonuç: her karta ayrı bir görev kutusu eklendi. Çiçeğin kısımları başçık, tepecik ve yumurtalık olarak anlatıldı.
2. **İyileştirme listesi:** "Sence daha ne ekleyebiliriz?" sorusuna verilen önerilerin hepsi sırayla uygulandı:
   - Gözlem defteri ve indirilebilir gözlem raporu (tahmin, gözlem, açıklama döngüsüyle)
   - Kiraz istasyonunda "Çiçekten meyveye" zaman kaydırıcısı
   - Vadi istasyonunda besin zinciri kurma etkileşimi
   - Tepe istasyonunda yükseklik–sıcaklık işaretçisi (1000 metrede soğuma hesabı)
   - Mobil düzenleme: sekmeli Polen kartı, küçültülebilir paneller, yumuşatılmış uzak dağlar
   - Öğretmen notları ve sunum modu. Öğrenme çıktıları, MEB Türkiye Yüzyılı Maarif Modeli Fen Bilimleri Dersi Öğretim Programı (2026) metnine göre eşleştirildi.
   - Fen animasyon serisinin karakteri Zerre'nin su döngüsü yolculuğu
3. **Öğrenci gözüyle kontrol:** "Öğrenci gözü ile bir daha bak; takip etmesi zor mu, eksik yönerge var mı? En başa nasıl kullanılacağını anlatan etkileşimli bir yönerge ekleyelim." Sonuç: işaretlenebilir görev listeleri, "sonraki noktaya geç" düğmesi, tamamlanan istasyon işaretleri ve sekiz adımlık etkileşimli tanıtım eklendi.
4. **Takım ibaresi:** "Bu uygulama FTC #24230 takımı tarafından geliştirilmiştir ibaresini uygun bir yere yazalım." Sonuç: ibare logoyla birlikte yükleme ekranına, başlığa, öğretmen notlarına, deftere ve gözlem raporuna eklendi.
