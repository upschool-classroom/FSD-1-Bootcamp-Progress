# Ödev 2

Bu ödevimizde PaswordGenerator uygulamamızdaki kullanıcı deneyimini iyileştirmek için uygulamamıza bir tane **undo (geri alma)** özelliği eklememiz gerekiyor. 
1. Kullanıcılar uygulama başladıktan sonra oluşturdukları tüm şifreleri undo butonunu kullanılarak, ilk şifreye kadar geriye alınabilmelidirler. Örn: Sayfa ilk açıldığında oluşturulan ilk şifre “m0x21k” ise, kullanıcı 20 tane daha şifre oluşturduktan sonra “undo” butonunu kullanarak “m0x21k” şifresine kadar geriye gidebilmelidir.
2. Eğer geri alma işlemi yapabilmek adına geri alınabilecek bir şifre bulunmuyor ise, (mesela ilk şifreyi oluşturduğumuz kısımdayız veya ilk şifreye kadar her şeyi geri aldık.) o zaman “undo” butonu gri renkte ve tıklanamaz (deaktif) olmalıdır.
3. Undo (geri alma) mekanizması ilk kez böyle bir challange ile karşılaştığınızda kafa karıştırıcı olabilir. Bu yüzden ödevimizdeki işlemlerimiz için “Memento Pattern” adlı tasarım desenine göz atarak fikir edinmenizi öneririm.


*Ödev ile ilgili fikir edinebilmek adına  https://dotnet.gg adresinde uygulamalı örneği ile değerlendirebilirsiniz*

**Ödev Teslim Tarihi : 7 Mart Salı 20.00**
