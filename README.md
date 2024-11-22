# aygaz bootcamp steam data project
Projenin Amacı

Merhaba! Bu proje, stajyer bir data analisti olarak çalışmaya başladığım yeni start-up oyun firmasında, Steam veri setlerini analiz ederek çıkarmayı planladığımız yeni oyun için bir yol haritası oluşturmayı amaçlayan bir senaryo üzerine kuruldu. Ben biyoloğum ve sadece raw datalarımı analiz ediyordum, bilmediğim bir sektörde kendimi zorlamak istedim. Senaryodaki amacım, firmanın mevcut oyun piyasasında daha bilinçli ve stratejik kararlar almasını sağlamak. Bu nedenle, oyun türlerinden geliştirici ve yayıncı analizlerine, oyuncu tercihlerini etkileyen unsurlardan gelir tahminlerine kadar pek çok farklı analiz gerçekleştirdim.

Kullanılan Veri
Bu proje, Steam platformuna ait geniş bir kaggle veri setine dayanıyor. Verilerde oyun isimleri, türleri, yayıncı ve geliştirici bilgileri, fiyat, sahiplik (owners), platform uyumluluğu, pozitif ve negatif oy sayıları gibi özellikler bulunuyor. Özetle, oyunların piyasadaki performansını analiz edebilmek için gerekli her türlü bilgi elimizdeydi.

Yapılan Çalışmalar ve Analizler
1. Veri Temizleme ve Ön İşleme
Verilerde eksik ve tutarsız bilgileri tespit ederek doldurdum.
owners sütununu düzenleyerek temiz bir owners_cleaned sütunu oluşturdum.
Türleri (genres) ayrıştırarak daha detaylı analiz yapabilmek için her oyunun birden fazla türe sahip olabileceği şekilde ayarladım.
2. Yayıncı ve Geliştirici Analizi
Hangi geliştirici ve yayıncıların piyasada daha etkili olduğunu analiz ettim.
Bu firmaların en çok hangi türlerde başarılı olduklarını inceledim.
3. Oyun Türlerine Göre Dağılım
Steam’de en çok kullanılan türleri buldum ve bu türlerin yıllara göre nasıl değiştiğini bir grafikle görselleştirdim. Bu, oyuncu tercihlerindeki değişimleri anlamamı sağladı.
4. Pozitif ve Negatif Oy Analizi
Oyunların pozitif ve negatif oy oranlarını inceledim ve bunların türlere göre nasıl değiştiğini analiz ettim.
Ayrıca, pozitif ve negatif oyların fiyat ve sahiplik (owners) ile olan ilişkisini ölçerek, oyuncuların memnuniyetini etkileyen unsurları belirlemeye çalıştım.
5. Ücretli vs. Ücretsiz Oyunlar
Ücretli ve ücretsiz aksiyon oyunlarını karşılaştırarak bu iki modelin sahiplik ve gelir üzerindeki etkisini analiz ettim.
Fiyatın, oyun sahiplik oranı üzerindeki etkisini inceleyerek firmanın fiyatlandırma stratejisine katkıda bulunmayı hedefledim.
6. Radar Chart ile Tür Karşılaştırması
Revenue, Ownership, Positive Feedback ve Platform Support metriklerini kullanarak türleri radar chart ile görselleştirdim.
Bu grafik, hangi türlerin hangi metriklerde daha güçlü olduğunu hızlıca anlamamı sağladı.
7. Gelir Tahmini
Verilerden yola çıkarak çıkarmayı planladığımız oyun için bir gelir tahmini yaptım. Fiyat ve sahiplik oranlarını kullanarak, oyunun ilk yılda yaklaşık olarak ne kadar gelir getirebileceğini hesapladım.
Çıkarımlar ve Öneriler
Oyun Türü:

Action ve Indie türleri, pozitif geri bildirim oranları ve sahiplik sayılarına göre öne çıkıyor.
Yeni oyun bu türlerden biri olmalı ya da bunların unsurlarını içermeli.
Fiyatlandırma:

Ücretsiz oyunlar, sahiplik sayısını artırırken gelir açısından sınırlı kalabiliyor. Ücretli bir modelde düşük bir fiyatla yüksek sahiplik oranına ulaşabiliriz.
Platform Uyumluluğu:

Windows uyumluluğu bir zorunluluk. Mac ve Linux için uyumluluk opsiyonel olarak düşünülebilir. 
Pazarlama ve Yayınlama:

Büyük yayıncıların tür bazlı stratejileri incelenerek, oyunun doğru kategorilerde konumlandırılması sağlanmalı.
Proje ile Öğrendiklerim
Bu proje sayesinde:

Ham verileri analiz etmek ve işlenebilir bilgiye dönüştürmek,
Farklı görselleştirme teknikleri ile sonuçları anlamlı kılmak,
Verilerden çıkarımlar yaparak stratejik önerilerde bulunmak konularında kendimi geliştirdim.
Kullanılan Araçlar ve Kütüphaneler
Python: Veri işleme ve analiz için.
Pandas: Veri temizleme ve manipülasyon.
Matplotlib & Seaborn: Veri görselleştirme.
Scipy: İstatistiksel analizler.
Sonraki Adımlar
Detaylı Kullanıcı Analizi: Kullanıcıların oyun içi davranışlarını analiz ederek sadakatlerini anlamak.
Mikroişlemler: Gelir artırmak için oyun içi satın alma stratejilerini test etmek.
Global Analiz: Bölgelere göre oyun satış ve sahiplik oranlarını incelemek.
Kendi senaryomdaki sonucumda da piyasaya çıkartılacak oyun için yeni kurulmuş bir oyun firması için sektör tanıtımı, hangi oyun türünde piyasaya çıkmalıyız ve ortalama ücretli oyun fiyatından oyunumuzu platformlara sokarsak yıl içindeki beklenen kazanç gibi estimated kodları yazmaya çalıştım.






