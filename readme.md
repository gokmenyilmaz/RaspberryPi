
RaspberryPi kurulum işlemleri ve uygulamaları


````
imager_1.6.2.exe ile usb disk oluştur.
ssh  (boş dosya olarak kalacak-uzantı yok)
wpa_supplicant.conf
dosyalarını oluştur.

conf dosyasını editle
----------------------------------------
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
country=TR
update_config=1

network={
 ssid="FiberHGW_TPCXXX_5GHz"
 psk="*****"
}
-------------------------------------

Powershell
ssh pi@192.1681.7 (modemden bul)

UserName : pi
Password  : raspberry

C:\Users\Gokmen1977>ssh pi@192.168.1.7
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @

C:\\Users\\Gokmen1977/.ssh  klasörünü sil

linux : passwd  komutu ile parola değiştir

````
