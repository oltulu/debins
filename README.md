# Debins
Basit Tek Tıklamayla .kur Paketi Yükleyici (Aylinux için)


### You can `install` a .deb file:
![Image](https://raw.githubusercontent.com/eminfedar/debins/dev-unstable/debins2.png)

### You can `reinstall` or `remove` a package from a .deb file:
![Image](https://raw.githubusercontent.com/eminfedar/debins/dev-unstable/debins1.png)

### You can `upgrade` or `downgrade` a package from a .deb file:
![Image](https://raw.githubusercontent.com/eminfedar/debins/dev-unstable/debins3.png) ![Image](https://raw.githubusercontent.com/eminfedar/debins/dev-unstable/debins4.png)

## Derleme:

### Gerekler:

    Qt 5.9 (or >=)
    QtCreator (isteğe bağlı olarak, projeyi açıp düzenleme yaparak yeniden qtcreator'da oluşturabilirsiniz.)

### QtCreator olmadan derlemek için:
```
cd debins/ #path of the .pro file
mkdir build
cd build
qmake ../
make
```
