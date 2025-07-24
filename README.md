# Netflix_Series_Analaysis
 In this project, I performed various analyses using the 'Netflix Movies and TV Shows' dataset from Kaggle.

**Netflix Filmleri ve TV Şovları Veri Analizi 🎬📺**
Bu projede, Kaggle'dan temin edilen "Netflix Movies and TV Shows" veri setini kullanarak kapsamlı bir analiz gerçekleştirdim. Veri setini doğrudan indirmek yerine, bir kaggle.json dosyası aracılığıyla hızlı ve verimli bir şekilde erişim sağladım.⚡

**Proje Amacı:** Bu proje, Netflix içeriklerinin dağılımını, popülerlik eğilimlerini ve önemli özelliklerini görselleştirerek veri odaklı içgörüler sunmayı hedeflemektedir.

**Uygulanan Analiz Adımları ve Çözülen Sorunlar:**

**1-)Veri Temizliği ve Ön İşleme:**

Veri setindeki Null değerlerin tespiti ve ilgili sütunlardan temizlenmesi gerçekleştirildi.

Orijinal veri setinin bütünlüğünü korumak amacıyla bir çalışma kopyası oluşturuldu.

**2-)İçerik Türü Dağılımı Analizi:**

Netflix platformundaki "Film" ve "TV Şovu" içeriklerinin sayısal dağılımı bir çubuk grafik (Bar Chart) ile görselleştirilerek içerik portföyünün genel yapısı belirlendi.

**3-)Yaş Kategorisi (Rating) Analizi:**

İçeriklerin yaş derecelendirme oranları (Rating) yine bir çubuk grafik (Bar Chart) ile analiz edildi. Bu sayede, kullanıcıların yaş kategorilerine uygun içeriklerin dağılımı net bir şekilde ortaya kondu.

Ayrıca, farklı yaş kategorilerine göre "Film" ve "TV Şovu" dağılımları da benzer bir çubuk grafik ile incelendi.

**4-)Tür Dağılımı ve Derecelendirme Oranları Görselleştirmesi:**

Dizi/film türlerinin dağılımı bir pasta grafiği (Pie Chart) ile daha belirgin hale getirildi.

Benzer şekilde, yaş derecelendirmelerinin (Rating) genel dağılımı da bir pasta grafiği aracılığıyla görselleştirildi.

**5-)Oyuncu Analizi (Word Cloud):**

WordCloud kütüphanesi kullanılarak, veri setinde en fazla yer alan oyuncuların isimleri belirgin bir görselle (Word Cloud) analiz edildi. Bu, popüler oyuncu eğilimlerini hızlıca görmeyi sağladı.

**Kullanılan Araçlar ve Kütüphaneler:**

Bu projenin geliştirilmesinde Python programlama dili ve aşağıdaki kütüphanelerden faydalanılmıştır:

**Pandas:** Veri manipülasyonu ve analizi için.

**NumPy:** Sayısal işlemler için (Pandas bağımlılığı).

**Seaborn:** Estetik ve bilgilendirici istatistiksel grafikler oluşturmak için.

**Matplotlib:** Grafikler üzerinde detaylı özelleştirmeler yapmak için.

**WordCloud:** Metin verilerinden kelime bulutu görselleri oluşturmak için.
