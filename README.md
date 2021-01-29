# Pakur
Basit Tek Tıklamayla .kur Paketi Yükleyici (Aylinux için)


### Aylinux .kur dosyasını sisteme kurma:
![Image](https://github.com/oltulu/debins/raw/master/paketkur.png)

### Aylinux .kur dosyasını sisteme yeniden kurma veya sistemden kaldırma:
![Image](https://raw.githubusercontent.com/eminfedar/debins/dev-unstable/debins1.png)

### Aylinux .kur dosyasını güncelleme veya sürüm düşürme:
![Image](https://raw.githubusercontent.com/eminfedar/debins/dev-unstable/debins3.png) ![Image](https://raw.githubusercontent.com/eminfedar/debins/dev-unstable/debins4.png)

## Derleme:

### Gerekler:

    qt5-base 5.9 (veya >=)
    qt5-graphicaleffects
    QtCreator (isteğe bağlı olarak, projeyi açıp düzenleme yaparak yeniden qtcreator'da oluşturabilirsiniz.)

### QtCreator olmadan derlemek için:
```
cd pakur/ # .pro dosyasının yolu
mkdir build
cd build
qmake ../
make
```
