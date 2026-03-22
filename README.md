# 📺 Çoklu YouTube İzleyici

Birden fazla YouTube yayınını aynı anda tek ekranda izlemeye yarayan, sade ve hızlı bir araç.

## Özellikler

- **Çoklu yayın** — istediğin kadar YouTube videosu veya canlı yayın ekle
- **Akıllı grid** — pencere boyutuna göre kolon sayısı otomatik ayarlanır
- **Tek video tam ekran** — beğendiğin yayına ⛶ butonuyla odaklan, ESC ile geri dön
- **Sürükle & bırak** — videoların sırasını üstteki tutma kolundan sürükleyerek değiştir
- **Ses kontrolü** — bir videoya tıklayınca sadece o videonun sesi açılır, diğerleri mute kalır
- **Dışa / İçe aktar** — video listeni JSON dosyası olarak kaydet, istediğinde geri yükle
- **Otomatik kayıt** — açık videolar tarayıcı kapansa bile localStorage'da saklanır
- **Kontrol çubuğunu gizle** — `F` tuşuyla üst çubuğu gizle, tüm ekranı videolara ver

## Kullanım

### Video Eklemek
YouTube video linki veya ID'sini üst çubuğa yapıştır, `Ekle` butonuna tıkla ya da `Enter`'a bas.

```
https://www.youtube.com/watch?v=XXXXXXXXXXX
https://youtu.be/XXXXXXXXXXX
XXXXXXXXXXX  ← sadece ID de olur
```

### Klavye Kısayolları

| Tuş | İşlev |
|-----|-------|
| `F` | Kontrol çubuğunu gizle / göster |
| `ESC` | Tam ekran modundan çık |
| `Enter` | Video ekle (input odaklanmışken) |

### Dışa / İçe Aktarma

Video listenin kaybolmaması için **Dışa Aktar** butonuyla `.json` dosyası olarak sakla. Daha sonra **İçe Aktar** ile geri yükle.

## Kurulum

Sadece bir HTML dosyası, herhangi bir kurulum gerekmez.

**Yerel kullanım:**
```bash
# Python ile basit sunucu başlat
python -m http.server 8000
# Tarayıcıda aç: http://localhost:8000
```

**Ya da** `index.html` dosyasını direkt tarayıcıda aç.

## GitHub Pages

Bu repo GitHub Pages ile yayımlanmaktadır:  
🔗 **https://KULLANICI_ADIN.github.io/youtube-multi-viewer**

---

> Tarayıcı tabanlı bir araçtır, herhangi bir backend veya API anahtarı gerektirmez.
