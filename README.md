# Jarkom-Modul-4-IT02-2024

Kelompok IT02 :
| Nama | NRP |
| -------------------- | ---------- |
| Samuel Yuma Krismata | 5027221029 |
| Marselinus Krisnawan Riandika | 5027221056 |

## Daftar Isi

[Topologi](#topologi)</br>
[Rute](#rute)</br>
[CPT VLSM](#cpt-vlsm)</br>
[GNS3 CIDR](#gns3-cidr)</br>

## Topologi

![Topologi](https://github.com/samuelyuma/Jarkom-Modul-4-IT02-2024/assets/118542326/a5abf05d-1adf-4fdb-a057-296b5e7792e1)

## Rute

Prefix IP : **192.234**

| Nama Subnet | Rute                                                                                                | Jumlah IP | Netmask |
| ----------- | --------------------------------------------------------------------------------------------------- | --------- | ------- |
| A1          | ACEH > SW-Blangrakal > Berawang-Tampu > SW-Blangrakal > Enang-Enang > SW-Blangrakal > Starland      | 125       | /25     |
| A2          | ACEH > SW-Banda-Aceh > Sabang > SW-Banda-Aceh > Lambaro                                             | 15        | /27     |
| A3          | ACEH > SUMATERA-UTARA                                                                               | 2         | /30     |
| A4          | SUMATERA-UTARA > SW-Toba > Samosir > SW-Toba > Sibandang > SW-Toba > SUMATERA                       | 27        | /27     |
| A5          | SUMATERA > LAMPUNG                                                                                  | 2         | /30     |
| A6          | LAMPUNG > SW-Bandar-Lampung > Sebuku > SW-Bandar-Lampung > Sebesi                                   | 188       | /24     |
| A7          | SUMATERA > JAWA                                                                                     | 2         | /30     |
| A8          | JAWA > KALIMANTAN                                                                                   | 2         | /30     |
| A9          | KALIMANTAN > KALIMANTAN-UTARA                                                                       | 2         | /30     |
| A10         | KALIMANTAN-UTARA > SW-Tanjung-Selor > Selimau                                                       | 201       | /24     |
| A11         | KALIMANTAN-UTARA > KALIMANTAN-TIMUR                                                                 | 2         | /30     |
| A12         | KALIMANTAN-TIMUR > SW-Balikpapan > Bangkirai > SW-Balikpapan > Lamaru                               | 470       | /23     |
| A13         | KALIMANTAN-TIMUR > KALIMANTAN-SELATAN                                                               | 2         | /30     |
| A14         | KALIMANTAN-SELATAN > SW-Boenati > Angsana                                                           | 16        | /28     |
| A15         | KALIMANTAN-SELATAN > SW-Banjarmasin > Bajuin > SW-Banjarmasin > Takisung > SW-Banjarmasin > Batakan | 2045      | /21     |
| A16         | JAWA > SULAWESI                                                                                     | 2         | /30     |
| A17         | SULAWESI > SW-Sulsel > MAKASAR > SW-Sulsel > BELAWA                                                 | 3         | /29     |
| A18         | MAKASAR > SW-Limbung > Galesong > SW-Limbung > Topejawa-Takalar                                     | 3         | /29     |
| A19         | BELAWA > SW-Tempe > Madini > SW-Tempe > Baru                                                        | 61        | /26     |
| A20         | SULAWESI > SW-Gorontalo > PC-Gorontalo > SW-Gorontalo > PC-Marisa > SW-Gorontalo > MALUKU-UTARA     | 64        | /26     |
| A21         | MALUKU-UTARA > SW-Maluku > Tobelo > SW-Maluku > Morotai > SW-Maluku > Ternate                       | 1024      | /22     |
| Total       |                                                                                                     | 4258      | /19     |

## CPT VLSM

### Topologi

![Topologi](https://github.com/samuelyuma/Jarkom-Modul-4-IT02-2024/assets/118542326/a5abf05d-1adf-4fdb-a057-296b5e7792e1)

### Pembagian IP

| Subnet | Network ID     | Netmask         | Broadcast      | Range IP                        |
| ------ | -------------- | --------------- | -------------- | ------------------------------- |
| A1     | 192.234.20.0   | 255.255.255.128 | 192.23420.127  | 192.234.20.0 - 192.234.20.126   |
| A2     | 192.234.21.128 | 255.255.255.224 | 192.234.21.159 | 192.234.21.128 - 192.234.21.158 |
| A3     | 192.234.21.176 | 255.255.255.252 | 192.234.21.179 | 192.234.21.176 - 192.234.21.178 |
| A4     | 192.234.21.64  | 255.255.255.224 | 192.234.21.95  | 192.234.21.64 - 192.234.21.94   |
| A5     | 192.234.21.180 | 255.255.255.252 | 192.234.21.183 | 192.234.21.180 - 192.234.21.182 |
| A6     | 192.234.19.0   | 255.255.255.0   | 192.234.19.255 | 192.234.19.0 - 192.234.19.254   |
| A7     | 192.234.21.184 | 255.255.255.252 | 192.234.21.187 | 192.234.21.184 - 192.234.21.186 |
| A8     | 192.234.21.188 | 255.255.255.252 | 192.234.21.188 | 192.234.21.188 - 192.234.21.190 |
| A9     | 192.234.21.192 | 255.255.255.252 | 192.234.21.195 | 192.234.21.192 - 192.234.21.194 |
| A10    | 192.234.18.0   | 255.255.255.0   | 192.234.18.255 | 192.234.18.0 - 192.234.18.254   |
| A11    | 192.234.21.196 | 255.255.255.252 | 192.234.21.199 | 192.234.21.196 - 192.234.21.198 |
| A12    | 192.234.16.0   | 255.255.254.0   | 192.234.16.255 | 192.234.16.0 - 192.234.17.254   |
| A13    | 192.234.21.200 | 255.255.255.252 | 192.234.21.203 | 192.234.21.200 - 192.234.21.202 |
| A14    | 192.234.21.96  | 255.255.255.240 | 192.234.21.127 | 192.234.21.96 - 192.234.21.126  |
| A15    | 192.234.0.0    | 255.255.248.0   | 192.234.7.255  | 192.234.0.0 - 192.234.7.254     |
| A16    | 192.234.21.204 | 255.255.255.252 | 192.234.21.207 | 192.234.21.204 - 192.234.21.206 |
| A17    | 192.234.21.160 | 255.255.255.248 | 192.234.21.167 | 192.234.21.160 - 192.234.21.166 |
| A18    | 192.234.21.168 | 255.255.255.248 | 192.234.21.175 | 192.234.21.168 - 192.234.21.174 |
| A19    | 192.234.21.0   | 255.255.255.192 | 192.234.21.63  | 192.234.21.0 - 192.234.21.62    |
| A20    | 192.234.20.128 | 255.255.255.192 | 192.234.20.255 | 192.234.20.128 - 192.234.20.254 |
| A21    | 192.234.8.0    | 255.255.252.0   | 192.234.15.255 | 192.234.8.0 - 192.234.15.254    |

### Tree

![Tree](https://github.com/samuelyuma/Jarkom-Modul-4-IT02-2024/assets/118542326/5c2d307d-53e3-43e5-a7de-4e717840e16f)

## GNS3 CIDR

### Topologi

### Pembagian IP

### Tree
