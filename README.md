Proje Yazarı: Said Huzeyfe Özdemir

Projenin Adı: Kod-Asistan v0.1
Projenin Amacı: Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dijital asistan tasarlamak
Projenin Hedefleri: Bu asistanın ilerleyen zamanlarda hangi özellikleri kazanacağını (örneğin v1.0 Akıllı Menü, v2.0 Veri Saklama) maddeler hâlinde yazınız.
v0.1 — Temel Fonksiyonlar: Şifreli kullanıcı girişi, temel selamlama ve basit hesaplama işlemlerinin yürütülmesi.

v0.5 — Akıllı Hata Yönetimi: Hatalı deneme limitleri ve güvenlik eşik kontrollerinin sisteme entegre edilmesi.

v1.0 — Akıllı Menü ve Arayüz: Dinamik ve kullanıcı dostu etkileşimli menü yapısının sunulması.

v2.0 — Veri Saklama ve Profil Yönetimi: Kullanıcı tercihlerinin ve işlem geçmişinin güvenli veri tabanında saklanması.

Projenin Kapsamı
Proje kapsamı dâhilinde kullanıcı yetkilendirmesi ve sistem güvenliğini sağlamak üzere tasarlanan KRİTİK EŞİK denetim mekanizmasının metinsel sözde kod mantığı aşağıda tanımlanmıştır:

Sistem başlangıçta sabit bir sistem şifresi (örneğin "1234") ve kullanıcı giriş denemelerini takip eden bir hak sayacı (hak = 3) tanımlar. Algoritma kullanıcıdan şifre bilgisini girmesini ister. Girilen şifre sistem şifresi ile eşleşiyorsa ekrana "Giriş başarılı." iletisi yazdırılır ve akış doğrudan bitiş (DUR) adımına yönlendirilir. Şifrenin hatalı olması durumunda hak sayacı 1 azaltılır. Sayaç sıfırdan büyükse (kalan hak > 0) ekrana hatalı şifre uyarısı verilerek yeniden şifre isteme adımına dönülür. Deneme sayısı kritik eşiğe ulaşıp kalan hak 0'a düştüğünde ise sistem "Hakkınız bitti, erişim engellendi." uyarısını gösterir ve güvenlik amacıyla akışı bitirir (DUR).

Kaynakça
Ahilik kültürünün ustaya saygı, doğruluk ve dürüstlük ilkeleri gereğince, bu çalışmanın hazırlanmasında yararlanılan temel kaynaklar aşağıda kurumsal atıf formatına uygun şekilde listelenmiştir:

Milli Eğitim Bakanlığı (MEB)
Mesleki ve Teknik Eğitim Genel Müdürlüğü, Programlama Temelleri 9 Ders Kitabı, Bilişim Teknolojileri Alanı Yayınları, Ankara.
