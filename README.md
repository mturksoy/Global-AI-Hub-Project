# Global-AI-Hub-Project

Tas Kagit Makas Oyunu - Muhammet Turksoy

Bu proje, Python dilinde geliştirilen basit bir "Taş, Kağıt, Makas" oyunudur. Kullanıcı, bilgisayara karşı oynayarak oyunun galibi olmayı hedefler. Oyun, klasik "Taş, Kağıt, Makas" kuralları üzerine kurulmuştur ve birkaç turdan oluşur. Proje, Python programlama dilinin temellerini öğrenmek ve uygulamak amacıyla geliştirilmiştir.

## Projenin Amacı

Bu projenin amacı, Python programlama dilini kullanarak basit bir oyun geliştirmek, kullanıcı girişi almak ve rastgele bilgisayar seçimleri yaparak oyun akışını yönetmektir. Oyun, kullanıcıya programlama mantığını anlamada yardımcı olacak şekilde tasarlanmıştır.

## Kullanılan Teknolojiler ve Kütüphaneler

Proje boyunca aşağıdaki Python kütüphaneleri ve araçları kullanılmıştır:

- **Python Standart Kütüphaneleri:** Oyun mantığı, kullanıcı girişi ve program akışı Python dilinin temel fonksiyonları ile sağlanmıştır.
- **random:** Bilgisayarın rastgele seçimler yapabilmesi için Python'un `random` kütüphanesi kullanılmıştır.

## Proje Detayları

- **Sınıf Adı:** `tas_kagit_makas_MUHAMMET_TURKSOY`

### Oyun Mantığı
- Oyun, oyuncu ve bilgisayar arasında geçer.
- Her iki taraf da "Taş", "Kağıt" veya "Makas" seçeneklerinden birini seçer.
- Taş, Makas'a karşı kazanır; Kağıt, Taş'a karşı kazanır; Makas, Kağıt'a karşı kazanır.
- İlk 2 skoru elde eden taraf oyunu kazanır.
- Oyuncu istediği zaman oyunu sonlandırabilir.
- Oyunun sonunda, tekrar oynama seçeneği sunulur, ancak bilgisayarın da bu konuda bir seçim hakkı vardır.

### Metodlar
- `__init__`: Oyunun başlangıç durumunu ve oyuncu adını ayarlar.
- `hosgeldinMesaji`: Oyunun kurallarını ve giriş mesajını oyuncuya iletir.
- `oyun`: Oyun akışını yönetir, kullanıcı ve bilgisayar seçimlerini alır, kazananı belirler.
- `skorTablosu`: Oyun ve tur skorlarını ekrana yazdırır.
- `ingilizceKaraktereCevir`: Kullanıcı tarafından girilen metindeki Türkçe karakterleri İngilizce karakterlere dönüştürür.
- `kazananiBelirle`: Oyuncu ve bilgisayar seçimlerine göre tur kazananını belirler.
- `devam_mi_tamam_mi`: Oyunun bitiminde oyuncuya ve bilgisayara tekrar oynama isteği sorar.
