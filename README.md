# Jarkom-Modul-4-IT13-2023

|       Nama      | NRP        | 
| -----------     | :---------: 
| Della Setyowati | 5027211044 | 
| Wisnu Adjie Saka| 5027211051 | 

## Daftar Isi
- [Topologi](#topologi)
- [VLSM](#vlsm)

- [CIDR](#cidr)


## <a name="topologi"></a> Topologi
CPT
![untitled](https://cdn.discordapp.com/attachments/901344920361656355/1181078865486020608/image.png?ex=657fc068&is=656d4b68&hm=549e809164cf0e09b2b6a7b3e94af4382c42194cbe9180e284cbcf2097153e04&)

GNS3
![WhatsApp Image 2023-12-05 at 19 05 50_37610504](https://github.com/Delsea12/Jarkom-Modul-4-IT13-2023/assets/113821220/131a7892-c8a5-4bd7-9613-847223a139b4)


## <a name="vlsm"></a> VLSM
- TREE
Berikut merupakan hasil pemecahan ```subnet``` besar yang akan dibentuk menjadi jaringan yang lebih kecil
![untitled](https://cdn.discordapp.com/attachments/901344920361656355/1181495899294273606/image.png?ex=658144cd&is=656ecfcd&hm=9096b37f1ca9a091c6d05b27032d6db0b7df558a6c3cb66e90eee3573925de7e&)

![untitled](https://cdn.discordapp.com/attachments/901344920361656355/1181495370472226946/vlsm.drawio.png?ex=6581444f&is=656ecf4f&hm=3c29c3186f0c967e4da6b6829c33ac9bf5ab43c415df29a1aa28038bc69c15bf&)

- Pembagian IP
Berikut merupakan pembagian ```IP```  yang telah kami peroleh dari hasil pemecahan tadi menjadi jaringan yang lebih kecil


![untitled](https://cdn.discordapp.com/attachments/901344920361656355/1181084365166489631/image.png?ex=657fc588&is=656d5088&hm=042c48912c613d1c3253e0b220514868dba0368636a31f64b2489b4770ed875d&)

- Subnetting dan Routing
    1. Mengatur ```IP``` untuk setiap interface yang ada di setiap device sesuai dengan pembagian subnet pada pohon ```VLSM```
    2. Untuk mengatur ```ÌP``` bisa di lihat pada <a href='https://github.com/arsitektur-jaringan-komputer/Modul-Jarkom/tree/master/Modul-4#2-subnetting'>Modul 4</a> [Modul 4](https://github.com/arsitektur-jaringan-komputer/Modul-Jarkom/tree/master/Modul-4#2-subnetting)

- Testing
Beriku hasil testing kami

![untitled](https://cdn.discordapp.com/attachments/901344920361656355/1181496485943189534/image.png?ex=65814559&is=656ed059&hm=c30f23fa7b921d1aad4a8a2577e9844483c1bee8de705ca288eb5d172d6a147f&)






## <a name="cidr"></a> CIDR

- Peruteean pada jaringan, melakukan subnetting lalu pencatatan kebutuhan IP dan rute jaringan.

![image](https://github.com/Delsea12/Jarkom-Modul-4-IT13-2023/assets/113821220/b7c77c16-27df-412f-b7a8-e95ef0ccde47)


![image](https://github.com/Delsea12/Jarkom-Modul-4-IT13-2023/assets/113821220/1ff43125-6a50-40fe-94af-45bae1523181)


- Penggabungan dari subnet sampai menjadi satu subnet besar

![image](https://github.com/Delsea12/Jarkom-Modul-4-IT13-2023/assets/113821220/121e65f2-5c8c-4773-9a38-8dd058b736a3)

![image](https://github.com/Delsea12/Jarkom-Modul-4-IT13-2023/assets/113821220/bf729aeb-3ad0-4b2e-8715-a9cb7467617f)


- Tree dari hasil penggabungan untuk mencari IP masing-masing subnet

![image](https://github.com/Delsea12/Jarkom-Modul-4-IT13-2023/assets/113821220/54e17cb3-fa1f-4077-b833-4b20d1837552)


- Pembagian IP untuk masing-masing subnet (disini saya mengurutkan berdasarkan besar size yang dibutuhkan)

![image](https://github.com/Delsea12/Jarkom-Modul-4-IT13-2023/assets/113821220/6b64a0f3-1a54-45da-9342-cf40eb984f90)


- Kendala CIDR, masih belum bisa melakukan routing, belum bisa ping satu sama lain.
