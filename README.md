# Personel İzin

Telefondan kullanılan izin seçme sayfası. Veriler Supabase'de, sayfa GitHub Pages'te.

- `index.html` sayfanın kendisi (tek dosya)
- `manifest.webmanifest`, `sw.js`, `icon-*.png` ana ekrana eklenebilir uygulama için
- `.github/workflows/keepalive.yml` haftada iki kez veritabanını uyandık tutar

Güncelleme: `index.html` dosyasını değiştirip kaydetmek yeterli, bir dakika içinde yayına girer.

Sürüm: başlığın yanındaki etiket. Her güncellemede `index.html` içindeki `SURUM` ile `version.json` içindeki `"v"` değerini birlikte artırın (ör. 1.0 → 1.1). Eski sürümle açık kalan telefonlarda etiket "Yeni sürüm" olur; dokununca sayfa güncel hâliyle yenilenir.
