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

| Nama Subnet | Rute                                                                                                                                                          | Jumlah IP | Netmask |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------- |
| A1          | JAWA > SUMATERA > SW-Toba > SUMATERA-UTARA >SW-Blangrakal > Berawang-Tampu > SW-Blangrakal > Enang-Enang > SW-Blangrakal > Starland                           | 125       | /25     |
| A2          | JAWA > SUMATERA > SW-Toba > SUMATERA-UTARA > SW-Banda-Aceh > Sabang > SW-Banda-Aceh > Lambaro                                                                 | 15        | /27     |
| A3          | JAWA > SUMATERA > SW-Toba > SUMATERA-UTARA > ACEH                                                                                                             | 2         | /30     |
| A4          | JAWA > SUMATERA > SW-Toba > Samosir > SW-Toba > Sibandang > SW-Toba > SUMATERA-UTARA                                                                          | 27        | /27     |
| A5          | JAWA > SUMATERA > LAMPUNG                                                                                                                                     | 2         | /30     |
| A6          | JAWA > SUMATERA > LAMPUNG > SW-Bandar-Lampung > Sebuku > SW-Bandar-Lampung > Sebesi                                                                           | 188       | /24     |
| A7          | JAWA > SUMATERA                                                                                                                                               | 2         | /30     |
| A8          | JAWA > KALIMANTAN                                                                                                                                             | 2         | /30     |
| A9          | JAWA > KALIMANTAN > KALIMANTAN-UTARA                                                                                                                          | 2         | /30     |
| A10         | JAWA > KALIMANTAN > KALIMANTAN-UTARA > SW-Tanjung-Selor > Selimau                                                                                             | 201       | /24     |
| A11         | JAWA > KALIMANTAN > KALIMANTAN-UTARA > KALIMANTAN-TIMUR                                                                                                       | 2         | /30     |
| A12         | JAWA > KALIMANTAN > KALIMANTAN-UTARA > KALIMANTAN-TIMUR > SW-Balikpapan > Bangkirai > SW-Balikpapan > Lamaru                                                  | 470       | /23     |
| A13         | JAWA > KALIMANTAN > KALIMANTAN-UTARA > KALIMANTAN-TIMUR > KALIMANTAN-SELATAN                                                                                  | 2         | /30     |
| A14         | JAWA > KALIMANTAN > KALIMANTAN-UTARA > KALIMANTAN-TIMUR > KALIMANTAN-SELATAN > SW-Boenati > Angsana                                                           | 16        | /28     |
| A15         | JAWA > KALIMANTAN > KALIMANTAN-UTARA > KALIMANTAN-TIMUR > KALIMANTAN-SELATAN > SW-Banjarmasin > Bajuin > SW-Banjarmasin > Takisung > SW-Banjarmasin > Batakan | 2045      | /21     |
| A16         | JAWA > SULAWESI                                                                                                                                               | 2         | /30     |
| A17         | JAWA > SULAWESI > SW-Sulsel > MAKASAR > SW-Sulsel > BELAWA                                                                                                    | 3         | /29     |
| A18         | JAWA > SULAWESI > SW-Sulsel > MAKASAR > SW-Limbung > Galesong > SW-Limbung > Topejawa-Takalar                                                                 | 3         | /29     |
| A19         | JAWA > SULAWESI > SW-Sulsel > BELAWA > SW-Tempe > Madini > SW-Tempe > Baru                                                                                    | 61        | /26     |
| A20         | JAWA > SULAWESI > SW-Gorontalo > PC-Gorontalo > SW-Gorontalo > PC-Marisa > SW-Gorontalo > MALUKU-UTARA                                                        | 64        | /26     |
| A21         | JAWA > SULAWESI > SW-Gorontalo > MALUKU-UTARA > SW-Maluku > Tobelo > SW-Maluku > Morotai > SW-Maluku > Ternate                                                | 1024      | /22     |
| Total       |                                                                                                                                                               | 4258      | /19     |

## CPT VLSM

### Topologi

### Pembagian IP

| Subnet | Network ID     | Netmask         | Broadcast      | Range IP                        |
| ------ | -------------- | --------------- | -------------- | ------------------------------- |
| A1     | 192.234.20.0   | 255.255.255.128 | 192.23420.127  | 192.234.20.1 - 192.234.20.126   |
| A2     | 192.234.21.128 | 255.255.255.224 | 192.234.21.159 | 192.234.21.129 - 192.234.21.158 |
| A3     | 192.234.21.176 | 255.255.255.252 | 192.234.21.179 | 192.234.21.177 - 192.234.21.178 |
| A4     | 192.234.21.64  | 255.255.255.224 | 192.234.21.95  | 192.234.21.65 - 192.234.21.94   |
| A5     | 192.234.21.180 | 255.255.255.252 | 192.234.21.183 | 192.234.21.181 - 192.234.21.182 |
| A6     | 192.234.19.0   | 255.255.255.0   | 192.234.19.255 | 192.234.19.1 - 192.234.19.254   |
| A7     | 192.234.21.184 | 255.255.255.252 | 192.234.21.187 | 192.234.21.185 - 192.234.21.186 |
| A8     | 192.234.21.188 | 255.255.255.252 | 192.234.21.188 | 192.234.21.189 - 192.234.21.190 |
| A9     | 192.234.21.192 | 255.255.255.252 | 192.234.21.195 | 192.234.21.193 - 192.234.21.194 |
| A10    | 192.234.18.0   | 255.255.255.0   | 192.234.18.255 | 192.234.18.1 - 192.234.18.254   |
| A11    | 192.234.21.196 | 255.255.255.252 | 192.234.21.199 | 192.234.21.197 - 192.234.21.198 |
| A12    | 192.234.16.0   | 255.255.254.0   | 192.234.16.255 | 192.234.16.1 - 192.234.17.254   |
| A13    | 192.234.21.200 | 255.255.255.252 | 192.234.21.203 | 192.234.21.201 - 192.234.21.202 |
| A14    | 192.234.21.96  | 255.255.255.240 | 192.234.21.127 | 192.234.21.97 - 192.234.21.126  |
| A15    | 192.234.0.0    | 255.255.248.0   | 192.234.7.255  | 192.234.0.1 - 192.234.7.254     |
| A16    | 192.234.21.204 | 255.255.255.252 | 192.234.21.207 | 192.234.21.205 - 192.234.21.206 |
| A17    | 192.234.21.160 | 255.255.255.248 | 192.234.21.167 | 192.234.21.161 - 192.234.21.166 |
| A18    | 192.234.21.168 | 255.255.255.248 | 192.234.21.175 | 192.234.21.169 - 192.234.21.174 |
| A19    | 192.234.21.0   | 255.255.255.192 | 192.234.21.63  | 192.234.21.1 - 192.234.21.62    |
| A20    | 192.234.20.128 | 255.255.255.192 | 192.234.20.255 | 192.234.20.129 - 192.234.20.254 |
| A21    | 192.234.8.0    | 255.255.252.0   | 192.234.15.255 | 192.234.8.1 - 192.234.15.254    |

### Tree

![Tree](https://github.com/samuelyuma/Jarkom-Modul-4-IT02-2024/assets/118542326/46d8a3c8-ce12-4c20-8e26-c4743c884e7f)

### Konfigurasi

#### JAWA (Router)

```
Fast Ethernet0/0 (A7)
- IPv4 Address : 192.234.21.185
- Subnet Mask : 255.255.255.252

Fast Ethernet0/1 (A8)
- IPv4 Address : 192.234.21.189
- Subnet Mask : 255.255.255.252

Fast Ethernet1/0 (A16)
- IPv4 Address : 192.234.21.205
- Subnet Mask : 255.255.255.252
```

#### SUMATERA (Router)

```
Fast Ethernet0/0 (A4)
- IPv4 Address : 192.234.21.65
- Subnet Mask : 255.255.255.224

Fast Ethernet0/1 (A5)
- IPv4 Address : 192.234.21.181
- Subnet Mask : 255.255.255.252

Fast Ethernet1/0 (A7) -
- IPv4 Address : 192.234.21.186
- Subnet Mask : 255.255.255.252
```

#### Samosir (PC)

```
Fast Ethernet0/0 (A4)
- IPv4 Address : 192.234.21.66
- Gateway : 192.234.21.65
- Subnet Mask : 255.255.255.224
```

#### Sibandang (PC)

```
Fast Ethernet0/0 (A4)
- IPv4 Address : 192.234.21.67
- Gateway : 192.234.21.65
- Subnet Mask : 255.255.255.224
```

#### SUMATERA-UTARA (Router)

```
Fast Ethernet0/0 (A3)
- IPv4 Address : 192.234.21.177
- Subnet Mask : 255.255.255.252

Fast Ethernet0/1 (A4) -
- IPv4 Address : 192.234.21.94
- Subnet Mask : 255.255.255.224
```

#### ACEH (Router)

```
Fast Ethernet0/0 (A1)
- IPv4 Address : 192.234.20.1
- Subnet Mask : 255.255.255.128

Fast Ethernet0/1 (A2)
- IPv4 Address : 192.234.21.129
- Subnet Mask : 255.255.255.224

Fast Ethernet1/0 (A3) -
- IPv4 Address : 192.234.21.178
- Subnet Mask : 255.255.255.252
```

#### Berawang Tampu (PC)

```
Fast Ethernet0/0 (A1)
- IPv4 Address : 192.234.20.2
- Gateway : 192.234.20.1
- Subnet Mask : 255.255.248.128
```

#### Enang-Enang (PC)

```
Fast Ethernet0/0 (A1)
- IPv4 Address : 192.234.20.3
- Gateway : 192.234.20.1
- Subnet Mask : 255.255.248.128
```

#### Starland (PC)

```
Fast Ethernet0/0 (A1)
- IPv4 Address : 192.234.20.4
- Gateway : 192.234.20.1
- Subnet Mask : 255.255.248.128
```

#### Sabang (PC)

```
Fast Ethernet0/0 (A2)
- IPv4 Address : 192.234.21.130
- Gateway : 192.234.21.129
- Subnet Mask : 255.255.248.224
```

#### Lambaro (PC)

```
Fast Ethernet0/0 (A2)
- IPv4 Address : 192.234.21.131
- Gateway : 192.234.21.129
- Subnet Mask : 255.255.248.224
```

#### LAMPUNG (Router)

```
Fast Ethernet0/0 (A6)
- IPv4 Address : 192.234.19.2
- Subnet Mask : 255.255.255.0

Fast Ethernet0/1 (A5) -
- IPv4 Address : 192.234.21.182
- Subnet Mask : 255.255.255.252
```

#### Sebuku (PC)

```
Fast Ethernet0/0 (A6)
- IPv4 Address : 192.234.19.3
- Gateway : 192.234.19.2
- Subnet Mask : 255.255.255.0
```

#### Sebesi (Server)

```
Fast Ethernet0/0 (A6)
- IPv4 Address : 192.234.19.4
- Gateway : 192.234.19.2
- Subnet Mask : 255.255.255.0
```

#### KALIMANTAN (Router)

```
Fast Ethernet0/0 (A9)
- IPv4 Address : 192.234.21.193
- Subnet Mask : 255.255.255.252

Fast Ethernet0/1 (A8) -
- IPv4 Address : 192.234.21.190
- Subnet Mask : 255.255.255.252
```

#### KALIMANTAN-UTARA (Router)

```
Fast Ethernet0/0 (A10)
- IPv4 Address : 192.234.18.1
- Subnet Mask : 255.255.255.0

Fast Ethernet0/1 (A11)
- IPv4 Address : 192.234.21.197
- Subnet Mask : 255.255.255.252

Fast Ethernet1/0 (A9) -
- IPv4 Address : 192.234.21.194
- Subnet Mask : 255.255.255.252
```

#### Selimau (PC)

```
Fast Ethernet0/0 (A10)
- IPv4 Address : 192.234.18.2
- Gateway : 192.234.18.1
- Subnet Mask : 255.255.255.0
```

#### KALIMANTAN-TIMUR (Router)

```
Fast Ethernet0/0 (A12)
- IPv4 Address : 192.234.16.1
- Subnet Mask : 255.255.254.0

Fast Ethernet0/1 (A13)
- IPv4 Address : 192.234.21.201
- Subnet Mask : 255.255.255.252

Fast Ethernet1/0 (A11) -
- IPv4 Address : 192.234.21.198
- Subnet Mask : 255.255.255.252
```

#### Bangkirai (Server)

```
Fast Ethernet0/0 (A12)
- IPv4 Address : 192.234.16.2
- Gateway : 192.234.16.1
- Subnet Mask : 255.255.254.0
```

#### Lamaru (PC)

```
Fast Ethernet0/0 (A12)
- IPv4 Address : 192.234.16.3
- Gateway : 192.234.16.1
- Subnet Mask : 255.255.254.0
```

#### KALIMANTAN-SELATAN (Router)

```
Fast Ethernet0/0 (A14)
- IPv4 Address : 192.234.21.97
- Subnet Mask : 255.255.255.224

Fast Ethernet0/1 (A15)
- IPv4 Address : 192.234.0.1
- Subnet Mask : 255.255.248.0

Fast Ethernet1/0 (A13) -
- IPv4 Address : 192.234.21.202
- Subnet Mask : 255.255.255.252
```

#### Angsana (PC)

```
Fast Ethernet0/0 (A14)
- IPv4 Address : 192.234.21.98
- Gateway : 192.234.21.97
- Subnet Mask : 255.255.255.224
```

#### Bajuin (PC)

```
Fast Ethernet0/0 (A15)
- IPv4 Address : 192.234.0.2
- Gateway : 192.234.0.1
- Subnet Mask : 255.255.248.0
```

#### Takisung (PC)

```
Fast Ethernet0/0 (A15)
- IPv4 Address : 192.234.0.3
- Gateway : 192.234.0.1
- Subnet Mask : 255.255.248.0
```

#### Batakan (PC)

```
Fast Ethernet0/0 (A15)
- IPv4 Address : 192.234.0.4
- Gateway : 192.234.0.1
- Subnet Mask : 255.255.248.0
```

#### SULAWESI (Router)

```
Fast Ethernet0/0 (A17)
- IPv4 Address : 192.234.21.161
- Subnet Mask : 255.255.255.248

Fast Ethernet0/1 (A20)
- IPv4 Address : 192.234.20.129
- Subnet Mask : 255.255.255.128

Fast Ethernet1/0 (A16) -
- IPv4 Address : 192.234.21.206
- Subnet Mask : 255.255.255.252
```

#### PC-Gorontalo

```
Fast Ethernet0/0 (A20)
- IPv4 Address : 192.234.20.130
- Gateway : 192.234.20.129
- Subnet Mask : 255.255.255.128
```

#### PC-Marisa

```
Fast Ethernet0/0 (A20)
- IPv4 Address : 192.234.20.131
- Gateway : 192.234.20.129
- Subnet Mask : 255.255.255.128
```

#### BELAWA (Router)

```
Fast Ethernet0/0 (A19)
- IPv4 Address : 192.234.21.1
- Subnet Mask : 255.255.255.192

Fast Ethernet1/0 (A17) -
- IPv4 Address : 192.234.21.166
- Subnet Mask : 255.255.255.248
```

#### Madini (PC)

```
Fast Ethernet0/0 (A19)
- IPv4 Address : 192.234.21.2
- Gateway : 192.234.21.1
- Subnet Mask : 255.255.255.192
```

#### Baru (PC)

```
Fast Ethernet0/0 (A19)
- IPv4 Address : 192.234.21.3
- Gateway : 192.234.21.1
- Subnet Mask : 255.255.255.192
```

#### MAKASAR (Router)

```
Fast Ethernet0/0 (A18)
- IPv4 Address : 192.234.21.169
- Subnet Mask : 255.255.255.248

Fast Ethernet1/0 (A17) -
- IPv4 Address : 192.234.21.166
- Subnet Mask : 255.255.255.248
```

#### Galesong (Server)

```
Fast Ethernet0/0 (A18)
- IPv4 Address : 192.234.21.170
- Gateway : 192.234.21.169
- Subnet Mask : 255.255.255.248
```

#### Topejawa-Takalar (Server)

```
Fast Ethernet0/0 (A18)
- IPv4 Address : 192.234.21.171
- Gateway : 192.234.21.169
- Subnet Mask : 255.255.255.248
```

#### MALUKU-UTARA (Router)

```
Fast Ethernet0/0 (A21)
- IPv4 Address : 192.234.8.1
- Subnet Mask : 255.255.248.0

Fast Ethernet1/0 (A20) -
- IPv4 Address : 192.234.20.254
- Subnet Mask : 255.255.255.128
```

#### Tobelo (PC)

```
Fast Ethernet0/0 (A)
- IPv4 Address : 192.234.8.2
- Gateway : 192.234.8.1
- Subnet Mask : 255.255.248.0
```

#### Morotai (Server)

```
Fast Ethernet0/0 (A)
- IPv4 Address : 192.234.8.3
- Gateway : 192.234.8.1
- Subnet Mask : 255.255.248.0
```

#### Ternate (PC)

```
Fast Ethernet0/0 (A)
- IPv4 Address : 192.234.8.4
- Gateway : 192.234.8.1
- Subnet Mask : 255.255.248.0
```

## GNS3 CIDR

### Topologi

### Pembagian IP

### Tree
