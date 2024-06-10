# Online-Ticari-Otomasyon

MATERYAL VE YÖNTEM


Kullandığım programlama dilleri : C# , Asp.NET , CSS , HTML 

Kullandığım Yazılım Mimarisi : Mvc , Katman yapısı 

Kullandığım veritabanı : MSSQL

MVC Katman yapısını kullanarak Models kısmında Sınıflarımı , View kısmında .cshtml 
uzantısı ile yani görünümlerimi oluşturdum ve Controller kısmında oluşturmam gereken 
sınıfların controllerlarını oluşturarak projemin katman yapısını oluşturmuş oldum.

Tasarım için gerekli olan bölümleri projeme klasör olarak ekledim 
(weblogin,webpanel,thumber,web,web2) ve bu kısımlar üzerinde değişiklikler yaparak 
projeme uygun hale getirdim.
 
Projem de bazı Sql terimlerini ve gerekli olan komutları kullanarak projemi daha verimli ve tekrarsız bir şekilde oluşturdum.
( Distinct() , Count() , Sum() , UPDATE , SELECT , DELETE , İNSERT )

![screenshot 1](Screenshots/katman1.png)

![screenshot 2](Screenshots/katman2.png)

![screenshot 3](Screenshots/katman3.png)

![screenshot 4](Screenshots/katman4.png)

![screenshot 5](Screenshots/katman5.png)

![screenshot 6](Screenshots/katman6.png)

![screenshot 7](Screenshots/katman7.png)

![screenshot 8](Screenshots/katman8.png)

Bu şekilde katman yapısını oluşturup işlemlerim için gerekli olan controller, view ve class yapılarını projede kullanarak projemi oluşturdum. 

Projemde dashboard oluşturarak personel hesabı için ; 

-	Kategoriler, 
-	Ürünler,
-	Ürün Listele,
-	Ürün Listele,
-	Ürün Listele,
-	Personeller, 
-	Personel Bilgileri,
-	Admin, 
-	Satışlar,
-	Faturalar,
-	Dinamik Faturalar,
-	Kargolar,
-	Pdf~Excel,
-	İstatistikler,
-	Grafikler,
-	Hızlı Bakış,
-	Galeri,
-	Ürün Detay,
-	Notlar
-	QR
Bölümlerini oluşturarak daha verimli, kullanışlı ve başarılı bir arayüz sağlayarak kullanım kolaylığı ile işlemleri daha rahat ve net bir şekilde kullanıma sundum. Verilere erişim kolaylaştı ve veriler arasında karmaşıklık olması önlenmiş oldu.

Cari hesabı için  ;
-	Profilim,
-	Siparişlerim,
-	Kargo Takibi,
-	Mesajlar

Bölümleri oluşturularak carilerin daha rahat bir şekilde işlem yapması için arayüzler   oluşturulmuştur.
  
Gerekli çalışmalar yapılarak  cari ve  personel girişleri için ayrı sayfalar oluşturularak kullanıcılar için işlem kolaylığı sağlanmıtır. Ve bu şekilde işlem karmaşıklığından kurtarılmıştır.

Veri kaybının olmaması için veriler, veritabanından silinmeyip durum değerinin true-false olarak değişimi sağlanmıştır.  Böylece sistemde tutarsızlık olmamıştır. Ve veri bütünlüğü korunmuştur. 

Bu projenin amacı; erişimi düzenli ve kolay bir şekilde sağlayarak işlemler arasında kolaylık sağlamaktır.
Online bir site geliştirerek ürünler, veriler, cariler, ve admin arasında iletişimi kolaylaştırarak, daha güvenli bir şekilde bilgiye erişilmesini sağlamaktadır.
Böylece işlemlerimiz karmaşıklıktan kurtularak pratikleşmiştir.

Kullandığım MVC yapısı ve C# Asp.NET aracılığı ile ve sağladığı yöntemlerle projemi gerçekleştirdim.

Projenin genel yapısını inceleyelim.

Projenin katman yapısı oluşturuldu

• Sınıflar oluşturuldu ve sınıflar arasındaki ilşki kuruldu.

• Dashboard ile tasarıma başlandı,ikonlar ayarlandı.

• Kategori sayfası oluşturuldu, sayfa tasarımı yapıldı, veri çekme,ekle,sil,güncelle yapıldı.

• Ürün sayfası oluşturuldu, sayfa tasarımı yapıldı, veri çekme,ekle,sil,güncelle yapıldı.

• Departman sayfası oluşturuldu, sayfa tasarımı yapıldı, veri çekme,ekle,sil,güncelle işlemleri yapıldı,detay kısmı oluşturuldu.

• Cari sayfası oluşturuldu, ekle,sil işemleri yapıldı ve yapılan satışlar listelendi.

• Personel sayfası oluşturuldu, sayfa tasarımı yapıldı, veri çekme,ekle,sil,güncelle işlemleri yapıldı.

• Personel detay sayfası oluşturuldu, sayfa tasarımı yapıldı, personel bilgileri çekildi,
personellerin bilgilerini güncelleyebiliyoruz ve personellerin yaptığı satış işlemine erişim
sağlandı.

• Ürün satış sayfası oluşturuldu yapılan satışların verisi çekildi,güncelleme işlemi yapıldı, yeni satış yapabilmek için bölüm oluşturuldu.

• Faturalar sayfası tasarlandı veriler çekildi.
-	Yeni fatura ekleme bölümü oluşturuldu.
-	Güncelleme işlemi yapıldı.
-	Detaylar sayfası oluşturuldu. Fatura detayları görüntüleniyor.
-	Yeni kalem giriişi yapılıyor.
-	Pop penceresi oluşturuldu.
-	Dinamik faturalara geçiş sağlandı.



• İstatistikler sayfası oluşturuldu, satış verilerinin tutulduğu bir sayfa tasarlandı genel veriler çekildi.

• Ürün görselleri eklendi ve bu şekilde inceleme işlemi yapılabiliyor.

• Ürün detay sayfası oluşturuldu ve tutulan ürünler daha net bir şekilde incelendi.

• Display Name kullanıldı.

• Login işlemleri için sayfa oluşturuldu. CARİ, PERSONEL girişi ve CARİ KAYIT için sayfalar oluşturuldu ve girişleri sağlandı.

• Notlar sayfası oluşturuldu ve gereken notlar tutulabiliyor ve tablolardaki bazı verilerin sayısı
çekildi.

• Hızlı Bakış sayfası oluşturuldu bu sayfada veritabanında tutulan tablolara ait veriler çekildi ve bu işlem sonucunda hızlıca inceleme işlemi yapabiliyoruz.

• Pdf ~Excel sayfası oluşturuldu ve bu kısımda yapılan satışların pdf ve excel gibi bir çok türde çıktısına erişebiliyoruz,kaydedebiliyoruz.

• Pop Up oluşturulup faturalarda kullanıldı.

• File Upload kullanılarak resimler de ekleme ve güncelleme yapıldı.

• Alert kullanımı eklendi.

• Ürün satış modülü eklendi ve numberdan seçilen adet sayısını fiyat ile çarpan fonksiyon
kullanılarak ürün satış işlemi gerçekleştirildi.

• Kargo modülü eklendi.

- Kargo Detay sınıfı oluşturuldu.
- Kargo Takip sınıfı ve migration oluşturuldu.
- Kargo Detay sayfası tasarlandı.
- Yeni kargo bilgisi girmek için sayfa tasarımı yapıldı.
- Random takip kodu oluşturuldu.
- Takip koduna göre ürün getirme işlemi yapıldı.

• QR Code işlemleri eklendi.

• İstatistikler bölümü oluşturuldu.
 
-	Toplam Cari,
-	Ürün Sayısı,
-	Personel Sayısı,
-	Kategori Sayısı,
-	Toplam Stok,
-	Marka Sayısı,
-	Kritik Seviye,
-	Max. Fiyatlı Ürün,
-	Min. Fiyatlı Ürün,
-	Max Marka,
-	Buzdolabı Sayısı,
-	Fırın Sayısı,
-	En Çok Satan Ürün,
-	Kasadaki Tutar,
-	Bugünkü Satışlar,
-	Bugünkü Kasa

Verilerinin tutulduğu bir bölüm oluşturuldu.

•  Dinamik Faturalar oluşturuldu.

-	Var olan faturalar listelendi.
-	Yeni fatura girişi için sayfa tasarımı yapıldı.
-	Yeni faturalar sisteme kaydedildi.
-	Faturaların kaydedilmesi çin gerekli bilgiler sistemden alındı.
-	Faturalardan login sayfasına dönüş yapılabildi.
-	Dinamik Faturalardan Faturalar sayfasına geçiş yapılabildi.

• Cari Profil sayfası oluşturuldu. 
  Profilim Sayfasında; 

-	Carinin kişisel bilgileri getirildi.
-	Yapılan toplam alışveriş sayısı getirildi.
-	Alışverişlerin toplam tutarı getirildi.
-	Alınan toplam ürün sayısı getirildi.
-	Kargo Takip Sayfasına erişim sağlanabildi.
-	Gelen Kutusundaki mesajlar listelendi.
-	Hakkımda kısmı oluşturuldu.
-	Hakkımda kısmında;
-	Hesap aktiflik durumu,
-	Şehir,
-	Şifre,
-	Duyurular    kısmı yer aldı.

• Cari Profilinde Mesajlar Bölümü oluşturuldu.

-	Gelen Kutusu oluşturuldu.
-	Giden Kutusu oluşturuldu.
-	Yeni mesaj oluşturma sayfası oluşturuldu.
-	Mesaj gönderme işlemi gerçekleştirildi.
-	Gelen ve gönderilen mesajların listelenmesi  sağlandı.

•  Cari Profilinde Kargo Takip Sayfası oluşturuldu.

-	Kargo takibi yapılması için gerekli veriler alındı.
-	Random oluşturulan kargo numarası ile arama işlemi yapıldı.
-	Getirilen kargo bilgilerinin detayları incelenebildi.

•  Cari Profilinde Siparişlerim Bölümü oluşturuldu.

-	Sipariş geçmişinde ürünün adı, fiyatı ve alışveriş tarihi yer alıyor.

•  Grafik Sayfası oluşturuldu.

-	Grafik ile Stok Durumu gösterildi.
• Error Page oluşturuldu.

-	Oluşturulan Error Page Sayfası ile herhangi bir hatalı işlem yapıldığında Error Page gelecek şekilde ayarlama yapıldı. 

•  Yetkilendirme işlemi yapıldı.

-	 Cariler kendi hesaplarının yer aldığı arayüze erişim sağlayabiliyorlar. Admin ise tüm işlemlerin gerçekleştiği Personel Sayfasına erişim sağlayabiliyor.







