 Şarkı Uygulaması - README

Bu uygulama, kullanıcıların çeşitli müzik türleri arasında seçim yaparak şarkıları dinlemelerine, favorilerine eklemelerine, son çalınan şarkıyı görüntülemelerine ve favori şarkılarını listelemelerine olanak tanır. Uygulama, Python'un `tkinter` kütüphanesi ile oluşturulmuş bir grafiksel kullanıcı arayüzü (GUI) sağlar ve şarkıları çalmak için `pygame` kütüphanesini kullanır.

 Özellikler

- Şarkı Çalma: Seçilen şarkıyı çalma.
- Duraklatma ve Devam Ettirme: Şarkıyı duraklatma ve devam ettirme.
- Favorilere Ekleme: Seçilen şarkıyı favorilere ekleyip listeleme.
- Son Çalınan Şarkıyı Gösterme: En son çalınan şarkıyı gösterme.
- Favori Şarkılar: Favori şarkıları listeleme.

Gereksinimler

- Python 3.x  
- pygame kütüphanesi (ses dosyalarını çalmak için)
- tkinter kütüphanesi (GUI oluşturmak için)

Kurulum

1. Python 3.x yüklü değilse, [Python'un resmi sitesinden](https://www.python.org/) Python'u indirin ve kurun.
2. `pygame` kütüphanesini yüklemek için terminal veya komut satırında aşağıdaki komutu çalıştırın:

   ```
   pip install pygame
   ```
   
Kullanım

1. Şarkı Türünü Seçin: Sol tarafta bulunan liste kutusundan bir müzik türü seçin.
2. Şarkıyı Çal: Seçilen türün altındaki şarkılardan birini seçin ve "Oynat" butonuna tıklayın.
3. Şarkıyı Duraklatın: Çalan şarkıyı duraklatmak için "Duraklat" butonuna tıklayın, devam ettirmek için "Devam Et" butonuna basın.
4. Favorilere Ekle: Şarkıyı favorilerinize eklemek için "Favorilere Ekle" butonuna tıklayın.
5. Son Çalınan Şarkıyı Görüntüleyin: En son çalınan şarkıyı görmek için "Son Çalınan" butonuna basın.
6. Favori Şarkılar: Favorilerinizi görüntülemek için "Favoriler" butonuna tıklayın.

Dosya Yapısı

- Şarkı dosyaları: MP3 formatındaki şarkı dosyaları (örneğin: `pop_shape_of_you.mp3`, `rock_bohemian_rhapsody.mp3`) uygulamanın çalışması için gereklidir. Bu dosyaların doğru dizinlere yerleştirildiğinden emin olun.
  
  ```
  .
  ├── app.py          # Uygulama dosyası
  ├── pop_shape_of_you.mp3
  ├── rock_bohemian_rhapsody.mp3
  ├── turkce_fikrimin_ince_gulu.mp3
  ├── ... (diğer şarkı dosyaları)
  ```

Notlar

- Şarkılar, farklı türlere ayrılmıştır: Pop, Rock, Türkçe, Türkçe Rap ve Podcast.
- Favoriler, şarkı türlerine göre tutulur ve şarkılar sadece favorilere eklenip çıkarılabilir, uygulama kapatıldığında favoriler kaybolur.
- Şarkı dosyalarının yolu, `songs` sözlüğündeki `path` anahtarı ile belirtilmiştir. Şarkı dosyalarının doğru şekilde yerleştirildiğinden emin olun.

Katkıda Bulunma

Eğer bu projeye katkıda bulunmak isterseniz, aşağıdaki adımları takip edebilirsiniz:

1. Projeyi forkladığınızdan emin olun.
2. Yaptığınız değişiklikleri açıklayan bir açıklama ile pull request gönderin.
3. Yaptığınız katkı için teşekkür ederiz!

Lisans

Bu proje, MIT Lisansı altında lisanslanmıştır. Ayrıntılar için LICENSE dosyasına bakabilirsiniz.

Bu README, şarkı uygulamanızın temel özelliklerini ve kullanımını açıklamak için hazırlanmıştır.
