# sqlhomework7
film tablosunda bulunan filmlerin derecelendirme değerlerine göre gruplandırınız.
film tablosunda bulunan filmler replace_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replace_cost değeri ve karşılık gelen filmi koymayı sıralayalım.
müşteri tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını mı?
şehir tablosunda bulunan şehir manzarası country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısını barındıran
country_id bilgisini ve şehir vermeyi paylaşınız.

Filmden derecelendirme SEÇİN _
Derecelendirmeye Göre GRUP ;

Değiştirme_maliyetini SEÇİN , ADET OLARAK COUNT ( * ) Filmden
GROUP TARAFINDAN değiştirme_maliyeti
SAHİP ( SAYI ( * ) > 50 );

store_id SEÇİN , COUNT ( * ) AS ADET Müşteriden
GRUP BY store_id;

Country_id , COUNT ( * ) ADET OLARAK Şehirden SEÇİN
GRUP TARAFINDAN country_id
SİPARİŞ ADEDİNE GÖRE TANIM
SINIR  1 ;
Altbilgi
© 2022 GitHub, In
