# Java-ödev1
1. Ödev
Teslim Tarihi

Ödev İçeriği
Yazacağınız Eclipse projesi Java dilinde ve konsol uygulaması olmalıdır. Program açıldığında 
kullanıcıdan github depo linkini (Repository Url) isteyecektir. Daha sonra bu git deposunu klonlayıp 
içinde *.java uzantılı tüm dosyaları getirecektir. Bu dosyalardan içinde sadece sınıf olanları
ayıklayacak ve bu sınıfları aşağıdaki analize tabi tutacaktır.
- Javadoc olarak yorum satır sayısı
- Diğer yorumlar satır sayısı
- Kod satır sayısı (tüm yorum ve boşluk satırları hariç)
- LOC (Line of Code) (Bir dosyadaki her şey dahil satır sayısı)
- Fonksiyon Sayısı (Sınıfın içinde bulunan tüm fonksiyonların toplam sayısı)
- Yorum Sapma Yüzdesi (Yazılması gereken yorum satır sayısı yüzdelik olarak ne kadar sapmış)
Yukarıdakileri her sınıf için ayrı ayrı tespit edecektir. Program aşağıdaki gibi ekrana çıktı verecektir.
Sınıf: A.java
Javadoc Satır Sayısı: 25
Yorum Satır Sayısı: 20
Kod Satır Sayısı: 95
LOC: 145
Fonksiyon Sayısı: 10
Yorum Sapma Yüzdesi: % 26.32
-----------------------------------------
Sınıf: B.java
Javadoc Satır Sayısı: 35
Yorum Satır Sayısı: 40
Kod Satır Sayısı: 200
LOC: 300
Fonksiyon Sayısı: 10
Yorum Sapma Yüzdesi: % 0
-----------------------------------------
Sınıf: C.java
Javadoc Satır Sayısı: 0
Yorum Satır Sayısı: 0
Kod Satır Sayısı: 260
LOC: 275
Fonksiyon Sayısı: 8
Yorum Sapma Yüzdesi: % -100
YG=[(Javadoc_Satır_Sayısı + Diğer_yorumlar_satır_sayısı)*0.8]/Fonksiyon_Sayisi
YH= (Kod_satir_sayisi/Fonksiyon_Sayisi)*0.3
Yorum Sapma Yüzdesinin Hesabı: [(100*YG)/YH]-100
Ödevde kullanılacak yöntem serbest olmakla birlikte düzenli ifadeler (regex) konusuna
https://youtu.be/HggrScOQouc bakmanız faydalı olacaktır.
Farklı sayıda fonksiyon ve yorumları okuyabilecek şekilde program yazılmalıdır.
Yazılacak proje mutlaka Eclipse ortamında açılabilen ve derlenebilen proje olmalıdır.
Önemli Not: Raporunuz detaylı olmalı ve kendi cümleleriniz olmalıdır (Örnek rapor SABİS’e 
yüklenmiştir). Kopya ödevler sıfır olarak değerlendirilecektir. SABİS şifreniz sizin 
sorumluluğunuz altındadır eğer arkadaşınız sizden habersiz ödevinizi alırsa bundan sizde 
sorumlu tutulur ve sıfır alırsınız.
ÖDEV BİREYSELDİR
Teslim Formatı
Ödevi Eclipse proje dosyaları ve bütün diğer dosyaların bulunduğu klasörü .zip’li bir şekilde SABİS
üzerinden gönderiniz. Klasörünüzün adı mutlaka öğrenci numaranız (b121210080 gibi) olmalıdır.
Yukarıda belirtilen teslim tarihinden sonra gönderilen ödev kesinlikle kabul edilmeyecektir.
Rapor pdf formatında olmalıdır. Raporu ayrıca çıktı olarak getirmenize gerek yoktur. Raporunuzda 
kısaca sizden istenilen, öğrendikleriniz, ödevde yaptıklarınız, eksik bıraktığınız yerler, zorlandığınız 
kısımlar anlatılabilir. Ödev raporu kapak hariç en az 1 sayfa en çok 3 sayfa olabilir.
Yazmış olduğunuz bütün kaynak kodların en başında aşağıdaki bilgiler bulunmalıdır. Bilgileri 
kendinize göre güncelleyiniz.
/**
*
* @author Yazar adı ve mail
* @since Programın yazıldığı tarih
* <p>
* Sınıf ile ilgili açıklama
* </p>
*/
