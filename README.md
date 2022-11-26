# Jarkom-Modul-4-ITB02-2022

Anggota kelompok:

1. Asima Prima Y. Tampubolon 5027201009
2. Cherylene Trevina 5027201033
3. Fatih Rian Hibatul Hakim 5027201066

## Daftar Isi

* [Soal](#soal)
* [Jumlah Kebutuhan IP](#jumlah-kebutuhan-ip)
* [VLSM](#vlsm)
* [CIDR](#cidr)
* [Setting Cisco](#setting-cisco)
* [Kendala](#kendala)

## Soal

![Soal](images/soal.png)

Pembuatan Subnetting & Pohon VLSM dan CIDR serta Config Cisco Packet Tracer & GNS3

## Jumlah Kebutuhan IP

![VLSM](images/VLSM.png)

Berikut adalah jumlah kebutuhan IP yang diperlukan dalam topologi yang telah dibuat

![jumlah IP](images/jumlah%20IP.png)

Berikut adalah jumlah prefix yang diperlukan

| Mask | Jumlah |
| --- | --- |
| /22 | 1 |
| /23 | 2 |
| /24 | 2 |
| /25 | 3 |
| /26 | 1 |
| /30 | 9 |
| Total | 18 |

Jumlah host total: `2618` dengan netmask: `/20`

## VLSM

## CIDR

Berikut adalah langkah langkah yang dilakukan dalam mengkombinasikan subnet untuk CIDR:

1. ![CIDR Step 1](images/CIDR%20Step%201.png)
2. ![CIDR Step 2](images/CIDR%20Step%202.png)
3. ![CIDR Step 3](images/CIDR%20Step%203.png)
4. ![CIDR Step 4](images/CIDR%20Step%204.png)
5. ![CIDR Step 5](images/CIDR%20Step%205.png)
6. ![CIDR Step 6](images/CIDR%20Step%206.png)
7. ![CIDR Step 7](images/CIDR%20Step%207.png)
8. ![CIDR Step 8](images/CIDR%20Step%208.png)

Berikut adalah tabel kesimpulan untuk kombinasi-kombinasi CIDR yang telah dilakukan.

![Kombinasi CIDR](images/Kombinasi%20CIDR.png)

Oleh karena itu, pohon CIDR dimulai dengan netmask `/16`. Sehingga pohon yang digunakan untuk subnet CIDR adalah:

![Pohon CIDR](images/Pohon%20CIDR.png)

Setelah pohon tersebut sudah diselesaikan, dibuat tabel subnetting CIDR, yaitu:

![Subnet CIDR](images/Subnet%20CIDR.png)

## Setting Cisco

## Kendala

Kesulitan dalam menconfig dalam GNS3