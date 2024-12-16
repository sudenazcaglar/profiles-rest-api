# Profiles REST API

API arayüzüne [buradan](http://www.sudenazcaglar.com/api) ulaşabilirsiniz.

# BACKEND REST API | Python, Django REST Framework, Django, AWS
## Kullanıcı Profilleri ve İçerik Yönetimi

### Profiles API Oluşturulması
- Kullanıcı profillerini **oluşturma**, **güncelleme**, **silme**, **görüntüleme** ve **listeleme** işlemlerini gerçekleştirecek bir API tasarlandı.
- Profillerin **arama** ve **filtrelenebilmesi** için gerekli özellikler eklendi.

### Login API Oluşturulması
- Profiles API'ye giriş yapmak için bir **Login API** oluşturuldu.
- **Token tabanlı kimlik doğrulama** ile yalnızca kimliği doğrulanmış kullanıcıların API içeriğine erişebilmesi sağlandı.

### Profile Feed API Oluşturulması
- Kullanıcıların durum güncellemelerini **oluşturması**, **görüntülemesi**, **güncellemesi** ve **silmesi** için bir **Profile Feed API** geliştirildi.
- Kimliği doğrulanan kullanıcıların **yalnızca kendi verilerini güncelleyebilmesi** için özelleştirilmiş izin sınıfları oluşturuldu.

---

## Geliştirme Ortamı ve Deployment
- Projede **versiyon kontrolü** Git ile sağlandı.
- Sanal çalışma ortamı **Vagrant** ve **VirtualBox** kullanılarak oluşturuldu.
- Deployment aşamasında, **AWS** ile uygulama sunucusu yapılandırıldı ve web üzerinde yayınlandı.

---

## API Bağlantıları
- Profiles API'ye erişmek için [buradan](http://www.sudenazcaglar.com/api/profile/).
- Login API'ye erişmek için [buradan](http://www.sudenazcaglar.com/api/login/).
- Profile Feed API'ye erişmek için [buradan](http://www.sudenazcaglar.com/api/feed/).

---

## Teknolojiler
- **Python**
- **Django**
- **Django REST Framework**
- **AWS**
- **Vagrant**
- **VirtualBox**

---

## Lisans
Bu proje MIT Lisansı altında sunulmuştur.
