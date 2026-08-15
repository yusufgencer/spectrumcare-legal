# SpectrumCare — hukuki sayfalar

SpectrumCare mobil uygulamasının gizlilik politikası ve kullanım koşulları.
GitHub Pages ile yayınlanır; uygulama kaynak kodu ayrı ve private bir repodadır.

## Yayın adresleri

| Sayfa | URL |
|---|---|
| Giriş | https://yusufgencer.github.io/spectrumcare-legal/ |
| Gizlilik Politikası (TR) | https://yusufgencer.github.io/spectrumcare-legal/gizlilik.html |
| Privacy Policy (EN) | https://yusufgencer.github.io/spectrumcare-legal/privacy.html |
| Kullanım Koşulları (TR) | https://yusufgencer.github.io/spectrumcare-legal/kosullar.html |
| Terms of Use (EN) | https://yusufgencer.github.io/spectrumcare-legal/terms.html |

Bu adresler hem App Store Connect / Play Console alanlarına, hem de uygulama
içine (onboarding rıza ekranı ve Ayarlar → Gizlilik) girilmelidir.

## Yayına almadan önce doldurulması gerekenler

Sayfalarda sarı `[köşeli parantez]` ile işaretli alanlar var; hepsi doldurulmalı:

- **İletişim e-postası** — zorunlu. KVKK/GDPR başvuruları ve Apple 5.1.1(i)
  gereği rıza geri çekme / silme talebi buradan gelir. Play'de bireysel
  hesaplarda zaten mağaza sayfasında halka açık gösterilir.
- **Veri sorumlusu adı / unvanı** — zorunlu (GDPR m.13, KVKK m.10).
  Posta adresi gerekmiyor: e-posta geçerli bir iletişim kanalı ve Play
  bireysel hesaplarda fiziksel adresi halka açık göstermiyor. Şirketleşince
  yeniden değerlendirilmeli.
- **Yürürlük tarihi** — mağaza reddi sebebi değil, ama rıza sürümlemesi için
  gerekli: kullanıcının hangi metne rıza verdiğini buradan bilirsiniz.

Kalan `todo` işaretlerini bulmak için:

```bash
grep -rn 'class="todo"' *.html
```

## Uyarı

Bu metinler, uygulamanın gerçek veri akışına göre hazırlanmış **taslaklardır**;
hukuki danışmanlık değildir. Sağlık verisi ve çocuk verisi işlendiği ve sesli
notlar yurt dışındaki bir yapay zekâ sağlayıcısına iletildiği için, yayına
almadan önce bir avukata gözden geçirtin.

## Güncelleme

Metni değiştirip `main` dalına push etmek yeterli; GitHub Pages birkaç dakika
içinde yayına alır. URL sabit kaldığı için mağazadaki linkleri değiştirmeniz
gerekmez. Önemli değişikliklerde sayfadaki sürüm ve yürürlük tarihini artırın.
