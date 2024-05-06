<-- JAVA Ovveriding Nedir ? -->

Java Overriding ,programımızda kullandığımız kalıtım sayesinde üst sınıftan ,alt sınıfa geçecek metotların o sınıf
yapısına uygun bir şekilde tekrardan gövdesinin değiştirilmesine ve kod satırının yeniden şekillendirilmesinde rol alır.
Örneğin bir araç firmasında araç tanıtım bröşürlerinin genel yapısı (motor hacimleri,kullandığı enerji,boyası vs.)
sabitken araca göre teknik özellikleri değişir.Bu değişme ovveriding sayeseinde daha kolay yapılır.

JAVA Overriding Kullanım Kuralları:

* Üst sınıflar içerisinde yer alan private metotlar override işlemine tabi tutulmaz. Aksi taktirde hata alınır.
* Override ettiğimiz bir metodun erişim belirleyicisinin seviyesini düşüremeyiz fakat yükseltebiliriz.
* Üst sınıftan miras aldığımız bir metodun dönüş tipini veya parametrelerini değiştiremeyiz.
* Static ve Final olarak tanımlı metotları override edemeyiz.
* Üst sınıfımızdaki ve alt sınıfımızda bulunan override edeceğimiz metot isimleri aynı olmalıdır.
* Constructor (Yapıcı/Kurucu) metotlar override edilemez.


---> Kullanım Avantajları: Temiz sade anlaşılır kod satırları oluşturmamıza ve Bir sınıfın hangi yapıda duruş sergileyecğini
,metotların işlevlerinin nasıl uygulanacağını tanımamıza imkan sağlar.

Bilgi: Annotation kavramı kodumuzun içeriğinin derleyici tarafından rahatlıkla okunabilmesini ve bu işlemin nasıl bir yapıda olduğunu anlaması için kullandığımız bir kavramdır. 
