# Sifre-Olusturucu
🛡️ Kriptografik Olarak Güvenli Şifre Oluşturucu &amp; Güç Analizörü | Python 10 Gün 10 Proje (4. Gün)  Python secrets modülü kullanılarak geliştirilmiş, yüksek entropili ve brute-force saldırılarına dayanıklı şifre üretim aracı. Kullanıcı tercihlerine göre dinamik karakter havuzu yönetimi ve anlık şifre gücü analizi (🟢/🟡/🔴) özelliklerini içerir.

🛡️ Gelişmiş Şifre Oluşturucu (Professional Password Generator)
Bu proje, Python ile "10 Gün 10 Proje" serisinin 4. gün çalışmasıdır. Standart rastgelelik yöntemlerinin ötesine geçerek, siber güvenlik standartlarında (kriptografik olarak güvenli) şifreler üretmek amacıyla geliştirilmiştir.

🌟 Öne Çıkan Özellikler
•	Kriptografik Güvenlik: random kütüphanesi yerine, tahmin edilmesi imkansız veriler üreten secrets modülü kullanılmıştır.
•	Güç Analizörü: Şifrenin uzunluğuna göre anlık güvenlik durumu (🟢/🟡/🔴) raporlaması.
•	Dinamik Karakter Havuzu: Harf, rakam ve sembol setlerini ihtiyaca göre birleştiren esnek yapı.
•	Hata Yönetimi (Robustness): try-except blokları ile kullanıcı hatalarına karşı dayanıklı çalışma.

🛠️ Teknik Çözümler ve Kazanımlar
Bu projeyi geliştirirken aşağıdaki kritik siber güvenlik ve yazılım kavramları çözüme kavuşturulmuştur:
1.	Entropi Artırımı: Yüksek entropili (karmaşık) şifreler üreterek Brute-Force saldırılarına karşı direnç sağlandı.
2.	Saldırı Yüzeyi (Attack Surface) Yönetimi: Zayıf şifre kullanımından kaynaklanan güvenlik açıklarını minimize eden bir araç sunuldu.
3.	Hata Toleransı: ValueError yönetimi ile programın beklenmedik durumlarda çökmesi engellendi.
