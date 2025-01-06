# diary-app-m4l1-solution

## 📚 Proje Kurulumu ve Veritabanı Yapılandırması

Projenizi doğru bir şekilde kurmak ve veritabanını oluşturmak için aşağıdaki adımları takip edin:

```bash
# Python ortamına geçmek için terminale yazmanz gereken komut:
python

# Ana dosyadan gerekli modülleri içe aktarın
from main import app, db

# Uygulama bağlamını aktifleştirin
app.app_context().push()

# Veritabanı dosyasını oluşturun
db.create_all()
