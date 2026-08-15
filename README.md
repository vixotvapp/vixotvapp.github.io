# Vixo TV — İndirme Sayfası

Bu depo, [vixotvapp.github.io](https://vixotvapp.github.io) adresinde yayınlanan
Vixo TV indirme sayfasının kaynağıdır (GitHub Pages).

## Yeni bir sürüm yayınlamak için

1. Yeni APK'yı `downloads/VixoTV.apk` üzerine kopyalayıp değiştirin.
2. `index.html` içindeki sürüm numarasını ve dosya boyutunu (`v1.0.0 · 59 MB`) güncelleyin.
3. Windows build'i hazır olduğunda `downloads/` altına ekleyip `index.html`
   içindeki Windows butonunu (`btn-disabled` sınıfını kaldırıp `href`'i
   `downloads/VixoTV.exe` yapın) etkinleştirin.
4. Değişiklikleri commit'leyip `main` dalına push'layın — GitHub Pages
   birkaç dakika içinde otomatik olarak yeniden yayınlar.
