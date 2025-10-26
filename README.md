McMojave KDE Teması
===================

Bu, McMojave KDE'nın bir forkudur.
Yaptıklarım:
- Tema tamamen Türkçeleştirildi.

Kurulum
-------

1. Releases kısmına girip en son sürümü indirin.
2. İndirilen dosyayı SDDM tema klasörüne taşıyın:
   
```sh
sudo mv McMojave /usr/share/sddm/themes
```
3. SDDM konfigürasyon dosyasını düzenleyin:
   
```sh
sudo nano /etc/sddm.conf
```
Burada "Current=" satırını şu şekilde değiştirin:

```
Current=McMojave
```
4. SDDM'i yeniden başlatın:

```
sudo systemctl restart sddm
```

Lisans
------

GNU GPL v3

