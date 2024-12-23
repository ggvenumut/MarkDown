# MarkDown
Markdown, metinlerinizi basit bir şekilde biçimlendirmenizi sağlayan hafif bir işaretleme dilidir. Özellikle yazılım projeleri, belgeler ve blog yazıları için popülerdir. Markdown, düz metni HTML'e veya başka bir zengin metin formatına dönüştürür.

#### MarkDown`un Avantajlari

- **Kolay Öğrenim** : Basit sözdizimi ile hızlıca öğrenilebilir.
- **Okunaklılık** : Biçimlendirilmemiş haliyle bile rahat okunur.
- **Çoklu Platform Desteği** : GitHub, Notion, Jupyter Notebook gibi birçok platform tarafından desteklenir.

## Markdown Sözdizimi

1. Başlıklar

Başlıklar `#` işareti ile belirtilir. Daha fazla `#` daha düşük seviye başlık anlamına gelir:

``` 
    # H1 Başlık
    ## H2 Başlık
    ### H3 Başlık
    #### H4 Başlık
    ##### H5 Başlık
    ###### H6 Başlık
```

2. Kalın ve İtalik Yazı

- **Kalın Yazı**: `**` veya `__`
 arasına alınır.
 
- *İtalik Yazı*: `*` veya `_` arasına alınır.

- ***Kalın ve İtalik***: `***` arasına kullanılır.

```
    **Kalın** veya __Kalın__
    *İtalik* veya _İtalik_
    ***Kalın ve İtalik***
```

3. Listeleme

- **Sırasız Liste**: `-` , `+` , veya `*` ile oluşturulur.
- **Sıralı Liste**: Sayılar ile yapılır.

```
    - Madde 1
    - Madde 2
        - Alt Madde

    1. Birinci
    2. İkinci
         1. Alt Liste

```

4. Bağlantılar

Bağlantılar köşeli ve normal parantezlerle yapılır:

[Google](https://www.google.com)

```
[Google](https://www.google.com) 
```
 

5. Görseller
Görseller için ünlem işareti eklenir:

![Alternatif Metin](https://picsum.photos/536/354)

```
![Alternatif Metin](https://picsum.photos/536/354)

```

6. Kod Blokları

- **Satır İçi Kod**: ` `` ` işareti arasına alınır.
- **Kod Blokları**: Üç adet ters tırnak kullanılır ve dil belirtilir.


````
    `inline code`

    ```python 
        def merhaba():
            print("Merhaba Dünya!")
    ```    
````

7. Alıntılar
Metinleri alıntılamak için `>` işareti kullanılır:

```
    > Bu bir alıntıdır.
```

- İç içe alıntılar (nested quotes):

```
    > Bu bir alıntıdır.
    >> Bu da ikinci bir alıntıdır.

```

8. Çizgiler

Yatay çizgi eklemek için üç veya daha fazla `-`, `*`, veya `_` kullanılır:

```
    ---
```

9. Tablo

Tablolar `|` ve `-` ile oluşturulur:

```
    | Başlık 1 | Başlık 2 |
    |----------|----------|
    | Veri 1   | Veri 2   |
    | Veri 3   | Veri 4   |

```

10. Görev Listesi

Kare kutular ile yapılır:

```
    - [x] Yapıldı
    - [ ] Yapılmadı
```

