# AddressBook_Sunum
AddressBook_SUNUM
Merhaba, Address Book projesi İstanbul - Beşiktaş Wissen Akademi'de kursiyerlik yaptığım süreçte yazdık.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız adres kaydı yapmaktır. Ayrıca gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)
Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor.
Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34
Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .
![Ekran görüntüsü 2023-02-28 131348](https://user-images.githubusercontent.com/118689173/221942361-db685f4c-0c0d-4fd0-ac74-4ab84d86c9b1.png)
![Ekran görüntüsü 2023-02-28 131312](https://user-images.githubusercontent.com/118689173/221942380-9f762144-14b6-450e-a51a-d16c677e92c8.png)
![Ekran görüntüsü 2023-02-28 131416](https://user-images.githubusercontent.com/118689173/221942421-75c5998c-470e-4c18-a850-b66a66e60584.png)
![Adsız](https://user-images.githubusercontent.com/118689173/221942481-509d828f-4096-4132-9063-4123155672b0.png)
![Adsız1](https://user-images.githubusercontent.com/118689173/221942505-037e7f11-864b-469b-ae2e-34f1724bd211.png)
<img width="949" alt="219572540-abd005fc-65f3-4be0-b576-0d21f0902b80" src="https://user-images.githubusercontent.com/118689173/221942569-bbd7d067-4268-4a29-9b5e-712395d29c55.png">
![Ekran görüntüsü 2023-02-28 210724](https://user-images.githubusercontent.com/118689173/221942594-06ac4dd9-55a4-40ee-aa47-f0b05f2f8ff3.png)
![Ekran görüntüsü 2023-02-28 210813](https://user-images.githubusercontent.com/118689173/221942602-25b397f4-78e0-4dc9-a2db-a8f2d8dfce47.png)
