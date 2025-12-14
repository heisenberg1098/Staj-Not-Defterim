======================================================
📚 STAJ DEFTERİ TAKİP UYGULAMASI (Notebook Tracker)
======================================================

Merhaba! Ben Muhammed Enes Yalçın.

Bu uygulamayı, staj defterime veya herhangi bir öğrenme sürecimde not alacağım uzun metinleri daha düzenli bir şekilde takip edebilmek için hazırladım. Amacım basit: Yazdığım her maddeyi işaretleyerek kafamın karışmasını engellemek ve nerede kaldığımı kolayca görebilmek.

**Artık hangi metni yazdım, hangisi kaldı diye düşünmenize gerek kalmayacak!**

---

### 🚀 Nasıl Kullanılır? (Çok Basit!)

Bu uygulama tamamen tarayıcı tabanlıdır ve herhangi bir kuruluma (ne Node.js'e, ne de başka bir şeye!) ihtiyaç duymaz.

1.  **Uygulamayı Açın:** `index.html` dosyasını çift tıklayarak web tarayıcınızda (Chrome, Firefox, Edge vb.) açın.
2.  **Notu Deftere Yazın:** Ekranda gördüğünüz metni (başlığı ve içeriği) defterinize yazmaya başlayın.
3.  **İşaretleyin:** Yazma işiniz bittiğinde, aşağıdaki büyük yeşil düğmeye tıklayın:
    > **[✅ Deftere Yazdım, Sonrakine Geç]**
4.  **Otomatik İlerleme:** Tıkladığınız anda:
    * Mevcut metin "✅ Yazıldı" olarak işaretlenir.
    * Durumunuz tarayıcınızın hafızasına (Local Storage) kaydedilir.
    * Uygulama otomatik olarak bir sonraki metne geçer.
5.  **Geri Dönüş:** İhtiyaç duyarsanız, alt kısımdaki **"Önceki Metin"** ve **"Sonraki Metin"** oklarını kullanarak serbestçe gezinebilirsiniz. (Ancak ben, sırayla ilerlemenizi tavsiye ederim!)

---

### 📋 Temel Özellikler

* **Kolay Takip:** Her metnin yazılıp yazılmadığı anlık olarak gösterilir.
* **Otomatik Kayıt:** Yazdığınız metinlerin durumu (tik atılıp atılmadığı) tarayıcınızda saklanır. Uygulamayı kapatsanız bile, tekrar açtığınızda kaldığınız yerden devam edersiniz.
* **İlerleme Çubuğu:** Projenizin tamamlanma yüzdesini gösteren şık bir ilerleme çubuğu bulunur.
* **Duyarlı Tasarım (Responsive):** Bootstrap kullanıldığı için telefonunuzda ve tabletinizde rahatça okuyabilir ve kullanabilirsiniz.

---

### 🛠️ Geliştiriciler ve Yapı

Bu proje HTML, CSS ve JavaScript kullanılarak yapılmıştır.

* **Bootstrap 5:** Tasarımın şık, modern ve duyarlı olması için kullandım.
* **Local Storage:** Yazdığınız metinlerin durumunu kaydetmek için bu özelliği kullandım.
* **Metinler:** Tüm notlarım `script.js` dosyasının içindeki `METIN_LISTESI` adlı JavaScript dizisinde (Array) yer alıyor. İleride kendi notlarınızı eklemek isterseniz, bu diziyi düzenlemeniz yeterlidir.

Umarım bu küçük uygulama, ders/staj takibinizi kolaylaştırır!

**İyi çalışmalar!**

Muhammed Enes Yalçın
======================================================
