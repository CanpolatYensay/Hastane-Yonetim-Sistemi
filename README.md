HASTANE YÖNETİM SİSTEMİ

Bir hastanenin temel süreçlerinin dijital ortamda yönetilmesini sağlayacak bir sistem. Projenin amacı hasta kayıtlarının, doktor ve klinik bilgilerinin, randevuların, ameliyatların, reçete ve ilaç süreçlerinin, laboratuvar sonuçlarının, yatak durumlarının, sigorta bilgilerinin ve faturalandırma işlemleri gibi süreçlerin doğru, hızlı ve güvenli bir şekilde yönetilmesi sağlamak.

Oluşturulabilecek Tablolar

Hasta: 
hasta_id / hasta_adi / hasta_soyadi / dogum_tarihi / telefon

Doktor: 
doktor_id / doktor_adi / doktor_soyadi / uzmanlik_id / klinik_id 

Klinik:
klinik_id / klinik_adi

Yatak:
yatak_id / klinik_id / yatak_durumu

Randevu:
randevu_id / hasta_id / doktor_id / randevu_tarihi / randevu_saati

Ameliyat:
ameliyat_id / hasta_id / doktor_id / ameliyat_tarihi / ameliyat_saati

Reçete:
recete_id / hasta_id / doktor_id / recete_tarihi

İlaç:
ilac_id / ilac_adi / stok_miktari / kritik_stok

Laboratuvar Sonucu:
sonuc_id / hasta_id / test_adi / test_sonucu / test_tarihi

Fatura:
fatura_id / hasta_id / fatura_tutari / odeme_durumu

Sigorta:
sigorta_id / hasta_id / sigorta_kurumu

