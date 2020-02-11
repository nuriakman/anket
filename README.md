# Anket Projesi
Anket hazırlama ve anket yapma projesidir

## Veritabanı Tabloları

### Anketler Tablosu
- anket_id
- Anket Adı
- Anket Giriş Metni
- Açılış Tarihi
- Kapanış Tarihi
- Anket Teşekkür Metni
- Durum (1: Aktif, 0: Pasif)

### Sorular Tablosu
- soru_id
- anket_id
- soru_kökü
- sıralama
- Durum (1: Aktif, 0: Pasif)
- resim_url
- cevap1
- cevap2
- cevap3
- cevap4

### Verilen Cevaplar Tablosu
- denek_id
- anket_id
- soru_id
- verilen_cevap

### Katılım Anahtarı Tablosu
- anket_id
- katılım_anahtarı
- kullanılma_zamani

# Ekranlar
- Anket Yönetimi
- Soru Yönetimi
- Anahtar Yönetimi
- Sonuç Raporları

