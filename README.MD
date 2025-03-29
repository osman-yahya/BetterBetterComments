# VS Code Modified Comment Color Tags Guide

Bu doküman, belirli renk etiketlerinin (tags) kullanımını ve temsil ettikleri renkleri açıklar.

#### Gereksinimler ve kurulum : VSCode 'Better Comments' eklentisi (Aaron Bond)
#### Ardından Repo'daki json dosyasındaki listeyi, Eklenti Sayfası > Ayarlar > settings.json ile düzenle ile açılan json dosyasında "better-comments.tags": parametresinin bulunduğu kısma yapıştırın.
---

## 1. Default Etiketler

| Tag  | Renk Kodu | Açıklama |
|------|----------|----------|
| `!`  | `#FF2D00` (Kırmızı) | Uyarı veya hata belirteci |
| `?`  | `#3498DB` (Mavi) | Soru veya bilgi belirteci |
| `//` | `#474747` (Gri - İtalik) | Yorum satırlarını gösterir |
| `%`  | `#FF8C00` (Turuncu) | Özel vurgular için kullanılır |
| `*`  | `#98C379` (Yeşil) | Önemli notlar için kullanılır |

## 2. Tekil Renk Etiketleri

| Tag  | Renk Kodu | Açıklama |
|------|----------|----------|
| `1r` | `#FF2D00` (Kırmızı) | Kırmızı vurgulu metin |
| `1g` | `#98C379` (Yeşil) | Yeşil vurgulu metin |
| `1b` | `#3498DB` (Mavi) | Mavi vurgulu metin |

## 3. Çift Renk Etiketleri

| Tag  | Renk Kodu | Açıklama |
|------|----------|----------|
| `2rg` | `#DAA520` (Altın Sarısı) | Kırmızı ve yeşil karışımı |
| `2gr` | `#DAA520` (Altın Sarısı) | Yeşil ve kırmızı karışımı |
| `2rb` | `#FF1493` (Pembe) | Kırmızı ve mavi karışımı |
| `2br` | `#FF1493` (Pembe) | Mavi ve kırmızı karışımı |
| `2gb` | `#00CED1` (Turkuaz) | Yeşil ve mavi karışımı |
| `2bg` | `#00CED1` (Turkuaz) | Mavi ve yeşil karışımı |

## 4. Arka Plan Renk Etiketleri

| Tag  | Metin Rengi | Arka Plan Rengi | Açıklama |
|------|------------|----------------|----------|
| `2sr` | `#FFFFFF` (Beyaz) | `#FF2D00` (Kırmızı) | Kırmızı arka plan üzerine beyaz metin |
| `2sg` | `#FFFFFF` (Beyaz) | `#98C379` (Yeşil) | Yeşil arka plan üzerine beyaz metin |
| `2sb` | `#FFFFFF` (Beyaz) | `#3498DB` (Mavi) | Mavi arka plan üzerine beyaz metin |

## 5. Üçlü Renk Etiketleri (Arka Plan Renkli)

| Tag  | Metin Rengi | Arka Plan Rengi | Açıklama |
|------|------------|----------------|----------|
| `3srg` | `#FFFFFF` (Beyaz) | `#DAA520` (Altın Sarısı) | Altın sarısı arka plan üzerine beyaz metin |
| `3sgr` | `#FFFFFF` (Beyaz) | `#DAA520` (Altın Sarısı) | Altın sarısı arka plan üzerine beyaz metin |
| `3srb` | `#FFFFFF` (Beyaz) | `#FF1493` (Pembe) | Pembe arka plan üzerine beyaz metin |
| `3sbr` | `#FFFFFF` (Beyaz) | `#FF1493` (Pembe) | Pembe arka plan üzerine beyaz metin |
| `3sgb` | `#FFFFFF` (Beyaz) | `#00CED1` (Turkuaz) | Turkuaz arka plan üzerine beyaz metin |
| `3sbg` | `#FFFFFF` (Beyaz) | `#00CED1` (Turkuaz) | Turkuaz arka plan üzerine beyaz metin |

Bu renk etiketlerini, metinlerinizi renklendirmek ve kategorize etmek için kullanabilirsiniz.

