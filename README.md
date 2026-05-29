# Adam Asmaca Oyunu
Bu proje, Java programlama dersi kapsamında geliştirilmiş bir "Adam Asmaca" (Hangman) kelime tahmin oyunudur. JFrame, JMenuBar ve JTabbedPane kullanılarak NetBeans ortamında hazırlanmıştır.

## Özellikler
Bu ödevde Java Swing kullanarak klasik bir adam asmaca oyunu tasarladım. Uygulamaya ilk açılışta sifre.txt dosyası yoksa yeni bir şifre belirleniyor, varsa girilen şifre kontrol ediliyor. 
Üç kez yanlış girilirse program kapanıyor. Bu şifre daha sonra oyun içindeki eski skorları veya log kayıtlarını temizlemek istediğimizde tekrar karşımıza çıkıyor.

Oyun başladığında `kelimeler.txt` dosyasından rastgele bir kelime seçiliyor. Kelimenin harf sayısı kadar dinamik JLabel oluşturuluyor ve başlangıçta hepsi * olarak görünüyor. İster tek harf 
ister kelimenin tamamını tahmin ederek bulmaya çalışıyoruz. Yanlış tahminlerde ekrandaki adam asmaca resmi adım adım güncelleniyor (toplam 11 aşama). Oyun süresince çalışan bir sayaç sayesinde
geçen süreyi saniye olarak görebiliyoruz.

✨ **Ekstra Özellik:** Projeye ek olarak, kullanıcı deneyimini artırmak amacıyla oyuna bir takip alanı eklenmiştir. Yanlış denenen harfler ekranda dinamik olarak *"Hatalı denemeler:
A, B, C"* şeklinde listelenmektedir.

Oyun bittiğinde kazanıp kazanmadığımız, süremiz ve oynadığımız tarih oyunlar.txt dosyasına kaydediliyor. Böylece Eski Skorlar sekmesinden geçmiş oyunlara JTable ile bakılabiliyor. Giriş yapı-
lan zamanlar, şifre denemeleri ve diğer önemli olaylar ise Loglar sekmesinde tablo halinde görüntülenebiliyor. Üst menüden oyuna başlama, yeniden başlatma ve çıkış işlemleri yapılabiliyor.

<img width="256" height="146" alt="image" src="https://github.com/user-attachments/assets/06f3df7e-1d9e-440a-a66b-f7ddde4a40cb" />

<img width="874" height="507" alt="image" src="https://github.com/user-attachments/assets/4d5c93e4-227d-4b91-93b6-d0e47284bb89" />

<img width="873" height="512" alt="image" src="https://github.com/user-attachments/assets/2d6c44be-fcb6-4eb0-80db-92d521c5a94d" />

<img width="873" height="509" alt="image" src="https://github.com/user-attachments/assets/548e3ece-6b46-4962-bf16-b886f6fe5332" />

<img width="871" height="512" alt="image" src="https://github.com/user-attachments/assets/1ef14936-b878-4a03-a277-0074b0c1ffa6" />

<img width="877" height="512" alt="image" src="https://github.com/user-attachments/assets/82fa2e6f-2820-49a2-b362-bec8efb42dde" />


