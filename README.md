<h1 align="center">Blackjack</h1>

<p align="center">
  Coin ve bahis sistemli, klasik kurallarla oynanan bir Android Blackjack oyunu.<br>
  İlk Kotlin projelerimden biri.
</p>

<p align="center">
  <a href="https://osmnnuri.github.io"><b>Ekran görüntüleri için siteme göz at</b></a>
</p>

---

## Proje hakkında

Klasik Blackjack (21) kurallarını uygulayan bir Android oyunu. Oyuncu
coin'leriyle bahis yapar, kart çeker ya da durur; ardından krupiye kendi elini
oynar ve kazanan belirlenir.

## Özellikler

| | |
|---|---|
| **Coin sistemi** | İlk girişte 100 coin; bakiye cihazda saklanır, oyunlar arasında korunur |
| **Günlük bonus** | Her gün ilk girişte +20 coin |
| **Bahis** | Masaya oturmadan bahis seçilir; kazanınca bahsin 2 katı, beraberlikte bahis iade |
| **Kart çek / dur** | İki butonla oynanır; elin toplamı anlık gösterilir |
| **Krupiye kuralı** | Krupiye 17'ye ulaşana kadar kart çeker |
| **Blackjack ve batma** | İlk elde 21 doğrudan krupiyeye geçer; 21'i geçen kaybeder |
| **Kart değerleri** | As 11, J / Q / K 10, diğerleri kendi değeri |

Uygulama bilinçli olarak sade: animasyon ya da özel tasarım içermez, oyun
mantığına ve durum yönetimine odaklanır.

## Nasıl çalışıyor?

```
Ana ekran (bakiye + günlük bonus)
        │  bahis seç
        ▼
Masa ──► Kart çek ──► 21'i geçti mi? ──► Kaybettin
  │
  └──► Dur ──► Krupiye 17'ye kadar çeker ──► Puanlar karşılaştırılır ──► Kazanç / iade
```

## Kullanılan teknolojiler

| Katman | Teknoloji |
|---|---|
| Dil | Kotlin |
| Arayüz | Activity, ViewBinding |
| Yerel veri | SharedPreferences (bakiye ve son giriş tarihi) |
| Geliştirme ortamı | Android Studio |

## Neden yaptım?

Kotlin'in temellerini, ekranlar arası veri aktarımını ve bir oyun döngüsünü
kurmayı öğrenmek için.

## Kaynak kod

Kaynak kod özel bir depoda tutuluyor; inceleme için talep üzerine paylaşılabilir.

## İletişim

**osmnnuri** · [Web sitesi](https://osmnnuri.github.io) · [GitHub](https://github.com/osmnnuri) · osmannuriyasar57@gmail.com
