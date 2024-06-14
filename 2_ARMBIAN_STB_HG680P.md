
## ARMBIAN STB HG680P

Thanks to [NanangMrk](https://www.youtube.com/watch?v=hIpA51p09iY&ab_channel=NanangMrk) & to [ophub](https://github.com/ophub/amlogic-s9xxx-armbian)

## RND - EKI INDRADI - TESTED 2024-06-10 

## HARDWARE :
- STB HG680P
- ADAPTOR 12V 1A 
- MicroSD 8GB / 16GB / 32Gb
- SDcard/MicroSD reader USB

## SOFTWARE : 
- [Armbian_24.8.0_amlogic_s905_jammy_6.6.32_server_2024.06.01.img.gz](https://github.com/ophub/amlogic-s9xxx-armbian/release)
- [BalenaEtcher](https://etcher.balena.io/)
- [Terminal Emulator for Android_1.0.70_APKPure.apk](https://apkpure.com/terminal-emulator-for-android/jackpal.androidterm)


amlogic_s905 =  chipset
jammy = mirip ubuntu 22.04 LTS / debian 12


1. download software BalenaEtcher & Armbian_21.08.1_Amlogic-GXL_bullseye_current_5.10.60.img.xz

2. flash MicroSD BalenaEtcher dengan image dari Armbian_24.8.0_amlogic_s905_jammy_6.6.32_server_2024.06.01.img.gz

3. setelah selesai, pasangkan microsd pada stb, nyalakan stb pada android framework atv, download "android terminal emulator apkpure" Terminal Emulator for Android_1.0.70_APKPure.apk

4. install Terminal Emulator for Android_1.0.70_APKPure.apk

5. buka terminal su - (grant access)

6. (sudah masuk root) reboot update atau sudo reboot update , secara otomatis akan reboot kan membaca boot microsd armbian

7. masuk modem dapatkan IP  dari stb dengan nama "amlogic" atau "armbian" pada MODE menu DHCP LIST

8. ssh dan lakukan konfigurasi confiogurasi armbian (layaknya konfigurasi linux awal)


Armbian Image information
Default username: root
Default password: 1234


NOTE : no. 5 dan 6 hanya jika microsd tidak langsung terbaca


## EKI INDRADI

"TIME > KNOWLEDGE > MONEY". #2024_3_DIGIT_MOTIVATION

## Reference : 

:link: https://github.com/ophub/amlogic-s9xxx-armbian/release

:link: https://chat.openai.com

:link: https://www.youtube.com

:link: https://www.google.com

:link: https://www.youtube.com/watch?v=hIpA51p09iY&ab_channel=NanangMrk


