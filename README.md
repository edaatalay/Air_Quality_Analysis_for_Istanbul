<h2 align="center"><span><strong>2022 İBB Sürdürülebilir Şehirler Hackathonu</strong></span></h2>

Bu proje, 19 Mayıs Atatürk’ü Anma Gençlik ve Spor Bayramı kapsamında; İstanbul Büyükşehir Belediyesi ve Microsoft Türkiye iş birliği ile, Coderspace organizasyonu ile gerçekleşen ‘Sürdürülebilir Şehirler Hackathon’u kapsamında oluşturduğumuz Hava Kalitesi İçin Yapay Ağaçlar projemizdir.

### Proje Adı
- Hava Kalitesi İçin Yapay Ağaçlar

### Takım Adı & Üyeleri
- Eda Atalay
- Beyza Nur Kebeli
- İpek Korkmaz

### Problem
- Hava kirliliğinin (Hava Kalitesi İndeksine göre) özellikle belirli nokta ve ilçelerde yüksek olması
- İstanbul’da ağaç dikilebilecek alanların azlığı 

### Çözüm ve Son Kullanıcı Deneyimi
- Aynı bir ağaç gibi hava temizleme kapasitesi sunan, az yer kaplayıp çok ağacın işlevini karşılayan yapay ağaçların tasarlanması.
- Hava kirliliğinin yüksek olduğu ve ağaç dikilemeyecek durumda olan şehir içi lokasyonlara (özellikle durak yakınları gibi araç ve insan trafiğinin fazla olduğu lokasyonlara) tasarlanacak olan yapay ağaçların konulması.
- Hava kirliliğinin yüksek olduğu yerlerde bu taşınabilir ağaçlarla birlikte hava temizliği sağlanması ve küresel ısınmanın sonucu olan yüksek sıcaklığın düşürülmesi.

### Hedef Kitle
- İstanbul'da yaşayan vatandaşlar 

### Prototip
- Bu teknolojiyi uygulayan Green City Solutions firmasının [CityTree](https://greencitysolutions.de/en/citytree/) projesi örnek alınarak Türk mühendisler tarafından kendi teknolojimiz üretilebilir.
- Bu yapay ağaçların konumlandırılması için en uygun ilçeleri hava kalitesi indeksi sonuçları ve nüfus yoğunluğu etmenlerini inceleyerek belirledik.

### Teknik Mimari / Teknoloji / Veri Kaynakları
- Veri Kaynakları 
  - [IBB Hava Kalitesi İstasyon Ölçüm Sonuçları Web Servisi](https://data.ibb.gov.tr/dataset/hava-kalitesi-istasyon-olcum-sonuclari-web-servisi)
  - [İBB Açık Veri Portalı Belediye Nüfus Veriseti](https://data.ibb.gov.tr/dataset/belediye-nufuslari-veri-seti)
- Teknoloji
  - Python
  - R
- Teknik Mimari
  - Python yazılım dilinde data düzenlemelerini gerçekleştirdik ve LSTM modeli üzerinde çalıştık. Bu LSTM modeli belirli bir zaman serisi datası girildiğinde gelecek hava kalitesini tahmin ediyor.
  - R yazılım dilini kullanarak bu dataların görselleştirmesini ve analizini gerçekleştirdik.

### Açıklamalar 
- Projenin şablonunu hava_kalitesi_icin_yapay_agaclar_template.pptx dosyasında bulabilirsiniz.
- Proje boyunca kullanılan datasetlerini data klasörü içerisinde bulabilirsiniz.
- Data temizliği & hazırlığı için hackathon_data_hazırlığı_1.ipynb dosyasını inceleyebilirsiniz.
- Data görselleştirme, analiz ve varılan sonuçlar için hackathon_data_gors_2.Rmd ve hackathon_data_gors_2.html dosyalarını inceleyebilirsiniz.
- LSTM tahmin modelini görüntülemek için hackathon_lstm_model_3.ipynb dosyasını inceleyebilirsiniz.
- Sunumu sunum.pptx dosyasından görüntüleyebilirsiniz.
- Belirtilen sıra ile incelemenizi tavsiye ediyoruz. Dosya isimlerinin sonundaki rakamlar inceleme sırasını belirtmek içindir. 



