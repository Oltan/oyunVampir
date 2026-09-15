# Köy — Oyun Kuralları

Bu belge, `index.html` içindeki mekaniklerle birebir aynıdır; uygulama içinden de
her ekranda "Oyun kuralları" butonuyla aynı metne ulaşılabilir.

## Roller

| Rol | Takım | Gece işi |
|---|---|---|
| Gulyabani | Kötü | Her gece bir dostu yer. Diğer gulyabanileri görür. |
| Dost | İyi | Gece aksiyonu yok. |
| Şifacı | İyi | Her gece bir kişiyi ölümden korur. |
| Bekçi | İyi | Seçtiği kişinin gulyabani olup olmadığını öğrenir. |
| Gözcü | İyi | Seçtiği kişiyi o gece kimlerin ziyaret ettiğini görür. |
| Uyurgezer | İyi | Seçtiği kişinin gece dışarı çıkıp çıkmadığını öğrenir. |
| Avcı | İyi | Gece birini vurur. **Masum vurursa vicdanı kendisini de öldürür.** |
| Koruma | İyi | Koruduğu kişiye saldırı olursa hedef kurtulur; **saldırgan ve Koruma'nın kendisi ölür.** |
| Tırsak | İyi | Dolaba saklanır: o gece ölmez ama hiçbir şey göremez. |
| Medyum | İyi | Ölülerle konuşur, gündüz aktarabilir. Gece aksiyonu yok. |
| Şakacı | Solo | Gece aksiyonu yok. **Gündüz asılırsa anında kazanır.** |
| Hayatta Kalan | Solo | Gece kendini koruyabilir. **Oyun sonuna kadar hayatta kalırsa, kazanan taraf her kimse ona da katılır.** |
| Seri Katil | Solo | Her gece tek başına birini öldürür. |

## Fazlar

1. **Gece** — Gece işi olan herkes kendi telefonundan hedefini seçer. İşi
   olmayanlar (Dost, Medyum, Şakacı) bekler.
2. **Sabah** — Moderatör "Sabahı getir"e basınca o gecenin bütün seçimleri
   birlikte çözülür (bkz. Gece Çözüm Sırası).
3. **Gündüz** — Herkes tartışır, sonra herkes telefonundan asılacak kişiye oy
   verir. Moderatör uygun gördüğü kişiyi asar.
4. Ölen/asılan kimse konuşmaz, mimik yapmaz; ekranını izlemeye devam edebilir.

## Gece Çözüm Sırası

1. Şifacı'nın koruduğu kişi o gece hiçbir saldırıdan ölmez.
2. Koruma'nın koruduğu kişiye saldırı olursa hedef kurtulur — ama saldırgan da,
   Koruma'nın kendisi de o gece ölür.
3. Tırsak ve Hayatta Kalan kendini sakladığında o gece ölmez ama hiçbir şey
   öğrenmez.
4. Avcı, gulyabani olmayan (masum) birini vurursa kurbanı ölür ve vicdan
   azabıyla Avcı da ölür.
5. Gulyabaniler o gece en çok oy aldıkları tek hedefte buluşup onu yer.

## Kazanma Şartları

- **Dostlar**: Bütün gulyabaniler ölünce kazanır.
- **Gulyabaniler**: Sayıları dostlara eşitlenince veya geçince kazanır.
- **Şakacı**: Gündüz asılırsa anında kazanır — başka hiçbir şart aranmaz.
- **Seri Katil**: Gulyabani ve Dost takımlarının hepsi bitince (yalnız Hayatta
  Kalan'la baş başa kalsa bile) kazanır.
- **Hayatta Kalan**: Oyunun sonuna kadar hayatta kalırsa, oyunu kim kazanırsa
  kazansın o da kazanmış sayılır (yukarıdaki şartlara ek olarak).

## Setler

- **İlk oyun**: Şifacı, Bekçi, Avcı, Gözcü, Uyurgezer + Dost + Gulyabani. Solo
  rol yok — en basit kurulum, ilk oyun için önerilir.
- **Geniş**: İlk oyun setine Tırsak, Koruma, Medyum, Şakacı, Hayatta Kalan
  eklenir.
- **Sert**: Geniş sete ek olarak ikinci bir Avcı ve Seri Katil eklenir.

## Moderatör (Host) Akışı

1. Lobide isimlerin gelmesini izle.
2. Set seç (İlk oyun / Geniş / Sert).
3. En az 5 kişi katılınca "Rolleri dağıt ve başlat"a bas.
4. Gece: kaç kişinin girdiğini izle, "Sabahı getir"e bas.
5. Gündüz: süreyi başlat, oyları izle, asılacak isme bas, "Gece olsun"a bas.
6. Ekranda kazanma mesajı çıkınca "Oyunu bitir ve rolleri aç"a bas.
