# homework-1-senolkara

* Proje incelendiğinde yapının üç katmanlı mimari üzerine inşa edilmeye çalışıldığı anlaşılabilir.
* İş katmanı ile alakalı kodlamalar Business package içerisinde bulunmaktadır. Service ve Service'ler ile alakalı Interface'lerimiz yine bu package içerisindedir.
* İsimlendirmeleri, eğer Interface eklenecekse isimlendirmenin başına I harfi, eğer bir Service eklenecekse isimlendirmenin sonuna Service eklenerek formatlandırılmaya çalışılmıştır.
* Veri Erişim katmanı ile alakalı kodlamalar DataAccess package içerisinde bulunmaktadır. Repository'lerimiz bu package içerisinde bulunmaktadır.
* İsimlendirmeleri, eğer Interface eklenecekse isimlendirmenin başına I harfi, eğer bir Repository eklenecekse isimlendirmenin sonuna Repository eklenerek formatlandırılmaya çalışılmıştır.
* Burada diğer bir isimlendirme çeşidi olarak isimlendirmenin sonuna _Dal_ eki getirilerek yapılmıştır. Daha çok _Dao_ eki ile bu isimlendirme yapılır fakat farklı bir format olarak _Dal_ eki kullanılmıştır.
* Entity'lerimiz Entities package içerisinde bulunmaktadır. 
* Son olarak Rest isteklerimize karşılık verecek _Controller_ classımız RestAPI package içerisindedir.
* Proje detaylıca incelendiğinde diğer ayrıntılar da göze çarpacaktır.  
