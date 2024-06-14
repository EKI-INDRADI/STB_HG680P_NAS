
## ROOT STB HG680P

Thanks to [WonoByte Channel](https://www.youtube.com/watch?v=qzeUDvmQjpU&ab_channel=WonoByteChannel)

## RND - EKI INDRADI - TESTED 2024-06-10 

## HARDWARE :
- STB HG680P
- ADAPTOR 12V 1A 
- USB MALE TO USB MALE
- PC OS WINDOWS 10 64


## SOFTWARE: 
- [DRIVER (Amlogic_Driver atau WorldCup_Device)]((https://drive.google.com/drive/folders/1GuLrz4ICtlEJP68LmiHiHyB1lQJFxqt-?usp=drive_link))
- [Amlogic USB Burning Tool](https://drive.google.com/drive/folders/1GuLrz4ICtlEJP68LmiHiHyB1lQJFxqt-?usp=drive_link)
- [ATV FW HG680P.img](https://drive.google.com/drive/folders/1GuLrz4ICtlEJP68LmiHiHyB1lQJFxqt-?usp=drive_link)



## STEP

1. install driver Amlogic_Driver atau WorldCup_Device, jika tidak bisa instal dalam keadaan safe mode

JIKA ERROR
---sh
windows 10 -> update ->  recovery -> advanced  startup -> restart (JANGAN PAKE REMOTE DESKTOP) 
-> troubleshoot -> advanced options -> startup -> disable driver signature enforcement F7

disable security boot bios
---


2. Jalankan Amlogic USB burning Tool , import image -> "ATV FW HG680P.img" , uncheck Erase bootloader dan hanya checklist Erase flash (normal erase), kemudia START


3. pasangkan USB MALE TO USB MALE DARI PC KE STB, sesudah pasang USB ke PC lalu, pasangkan USB ke STB pastikan menekan tombol power bersaamaan saat memasang ke STB


4. jika sudah terdeteksi Device nya pada USB burning tool dan berhasil akan melakukan formatting dan tidak ada error, jika error ulangi step 3 dan gunakan  ADAPTOR 12V 1A, hingga 100% burning successfully


5. selanjutnya tinggal setup android tv (dengan framework ATV), lepas usb male to usb male, pasangkan pada monitor / TV  (HDMI) akan muncul tampilan dari framework ATV Exprience, jangan lupa disable auto-update apps agar tidak auto update (bikin berat)



## EKI INDRADI

"TIME > KNOWLEDGE > MONEY". #2024_3_DIGIT_MOTIVATION

## Reference : 

:link: https://www.youtube.com/watch?v=qzeUDvmQjpU&ab_channel=WonoByteChannel