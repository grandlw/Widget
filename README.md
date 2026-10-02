# Grandl Rank Widget
Kişisel Android widget projesi. Sabit profil: grandl#wave (TR).

## Derleme
1. Android Studio'da bu klasörü aç.
2. Gradle sync tamamlanınca Run veya Build > Build APK(s).
3. Telefonda uygulamayı bir kez aç ve `Şimdi yenile`ye bas.
4. Ana ekran > Widget'lar > Grandl Rank widget'ını ekle.

## Veri
OP.GG profil sayfası HTML'inden Solo/Duo rank+LP, W/L+WR ve Flex rank+LP okunur.
WorkManager yaklaşık her 24 saatte ağ varken yeniler. Android zamanlamayı pil optimizasyonuna göre erteleyebilir.

Not: Bu resmi OP.GG API'si değildir. OP.GG HTML yapısını değiştirirse RankRepository.kt içindeki ayrıştırıcı güncellenmelidir.
