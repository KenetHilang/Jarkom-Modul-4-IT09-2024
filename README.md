# Jarkom-Modul-4-IT09-2024

## Angggota

| Anggota | NRP  |
| ------- | --- |
| Michael Kenneth Salim | 5027231008 |
| Tio Axelino | 5027231065 |

## Topologi

**Gambar CPT_VLSM**
![image](https://github.com/user-attachments/assets/db925b56-91fe-4b07-82d5-cd36239b9900)

**Gambar GNS_CIDR**

## Routes

| Nama Subnet | Rute | Jumlah IP | Netmask |
|-------------|------|-----------|---------|
| A1          | Hololive > HoloEN > Holo-Myth > Holo-Promise > Holo-Council > SW4 > Kronii_Mumei > SW4 > Bae_Fauna | 62 | /26 |
| A2          | Hololive > HoloEN > Holo-Myth > Holo-Promise > Holo-Council > Holo-Promise > Router4 | 3 | /29 |
| A3          | Hololive > HoloEN > Holo-Myth > Holo-Promise > Router4 > Tys | 3 | /29 |
| A4          | Hololive > HoloEN > Holo-Myth > SW2 > Gura_Ame_Ina > SW2 > Kiara_Calli | 503 | /23 |
| A5          | Hololive > HoloEN > Holo-Myth | 2 | /30 |
| A6          | Hololive > HoloEN > Holo-Advent | 2 | /30 |
| A7          | Hololive > HoloEN > Holo-Advent > SW0 > FucaMoco > SW0 > Shiori_Nerissa > SW0 > Biboo | 28 | /27 |
| A8          | Hololive > HoloEN | 2 | /30 |
| A9          | Hololive > HoloID | 2 | /30 |
| A10         | Hololive > HoloID > AREA-15 | 2 | /30 |
| A11         | Hololive > HoloID > holoro | 2 | /30 |
| A12         | Hololive > HoloID > holoh3ro | 2 | /30 |
| A13         | Hololive > HoloID > AREA-15 > SW6 > Moona > SW6 > Risu > SW6 > Iofi | 661 | /22 |
| A14         | Hololive > HoloID > holoro > SW7 > Ollie > SW7 > Anya > SW7 > Reine | 34 | /26 |
| A15         | Hololive > HoloID > holoh3ro > SW8 > Zeta > SW8 > Kaela > SW8 > Kobo | 299 | /23 |
| A16         | Hololive > HoloJP | 2 | /30 |
| A17         | Hololive > HoloJP > SW1 > GEN:0 > SW1 > DEV_IS | 3 | /29 |
| A18         | Hololive > HoloJP > SW1 > DEV_IS > Re:GLO$$ > Ririka_raden > Re:GLO$$ > Ao > Re:GLO$$ > Hajime_Kanade | 14 | /28 |
| A19         | Hololive > HoloJP > SW1 > GEN:0 > SW3 > MiComet > SW3 > Sora_Rodo_AZKi > SW3 > GEN:1 | 2045 | /21 |
| A20         | Hololive > HoloJP > SW1 > GEN:0 > SW3 > GEN:1 > Member > FBK_Matsuri > Member > Aki_Hachama | 470 | /23 |
| A21         | Hololive > HoloJP > SW1 > GEN:0 > SW3 > GEN:1 > Member > GAMERS | 2 | /30 |
| A22         | Hololive > HoloJP > SW1 > GEN:0 > SW3 > GEN:1 > Member > GAMERS > SW13 > Korone > SW13 > Okayu > SW13 > Mio | 120 | /25 |
| **Total**   |       | **4263**  | **/19** |

## Pembagian IP VLSM

| Subnet | Network ID      | Netmask           | Broadcast      | Range IP                    |
|--------|------------------|-------------------|----------------|-----------------------------|
| A1     | 10.68.18.128    | 255.255.255.192   | 10.68.18.191   | 10.68.18.129 - 10.68.18.190 |
| A2     | 10.68.19.48     | 255.255.255.248   | 10.68.19.55    | 10.68.19.49 - 10.68.19.54   |
| A3     | 10.68.19.56     | 255.255.255.248   | 10.68.19.63    | 10.68.19.57 - 10.68.19.62   |
| A4     | 10.68.12.0      | 255.255.254.0     | 10.68.13.255   | 10.68.12.1 - 10.68.13.254   |
| A5     | 10.68.19.72     | 255.255.255.252   | 10.68.19.75    | 10.68.19.73 - 10.68.19.74   |
| A6     | 10.68.19.76     | 255.255.255.252   | 10.68.19.79    | 10.68.19.77 - 10.68.19.78   |
| A7     | 10.68.19.0      | 255.255.255.224   | 10.68.19.31    | 10.68.19.1 - 10.68.19.30    |
| A8     | 10.68.19.80     | 255.255.255.252   | 10.68.19.83    | 10.68.19.81 - 10.68.19.82   |
| A9     | 10.68.19.84     | 255.255.255.252   | 10.68.19.87    | 10.68.19.85 - 10.68.19.86   |
| A10    | 10.68.19.88     | 255.255.255.252   | 10.68.19.91    | 10.68.19.89 - 10.68.19.90   |
| A11    | 10.68.19.92     | 255.255.255.252   | 10.68.19.95    | 10.68.19.93 - 10.68.19.94   |
| A12    | 10.68.19.96     | 255.255.255.252   | 10.68.19.99    | 10.68.19.97 - 10.68.19.98   |
| A13    | 10.68.8.0       | 255.255.252.0     | 10.68.11.255   | 10.68.8.1 - 10.68.11.254    |
| A14    | 10.68.18.192    | 255.255.255.192   | 10.68.18.255   | 10.68.18.193 - 10.68.18.254 |
| A15    | 10.68.16.0      | 255.255.254.0     | 10.68.17.255   | 10.68.16.1 - 10.68.17.254   |
| A16    | 10.68.19.100    | 255.255.255.252   | 10.68.19.103   | 10.68.19.101 - 10.68.19.102 |
| A17    | 10.68.19.64     | 255.255.255.248   | 10.68.19.71    | 10.68.19.65 - 10.68.19.70   |
| A18    | 10.68.19.32     | 255.255.255.240   | 10.68.19.47    | 10.68.19.33 - 10.68.19.46   |
| A19    | 10.68.0.0       | 255.255.248.0     | 10.68.7.255    | 10.68.0.1 - 10.68.7.254     |
| A20    | 10.68.14.0      | 255.255.254.0     | 10.68.15.255   | 10.68.14.1 - 10.68.15.254   |
| A21    | 10.68.19.104    | 255.255.255.252   | 10.68.19.107   | 10.68.19.105 - 10.68.19.106 |
| A22    | 10.68.18.0      | 255.255.255.128   | 10.68.18.127   | 10.68.18.1 - 10.68.18.126   |

## Configuration

### A1
- **Network**: 10.68.18.128  
- **Subnet Mask**: 255.255.255.192  
- **Broadcast**: 10.68.18.191  
- **Range IP**: 10.68.18.129 - 10.68.18.190  
- **Router**: 10.68.18.190  
- **Kronii_Mumei (33 Hosts)**: 10.68.18.189  
- **Bae_Fauna (22 Hosts)**: 10.68.18.188  

### A2
- **Network**: 10.68.19.48  
- **Subnet Mask**: 255.255.255.248  
- **Broadcast**: 10.68.19.55  
- **Range IP**: 10.68.19.49 - 10.68.19.54  
- **Holo-Myth**: 10.68.19.54
- **Router4**: 10.68.19.53
- **Holo-Council**: 10.68.19.52

### A3
- **Network**: 10.68.19.56  
- **Subnet Mask**: 255.255.255.248  
- **Broadcast**: 10.68.19.63  
- **Range IP**: 10.68.19.57 - 10.68.19.62  
- **Router**: 10.68.19.62  
- **Tys (3 Hosts)**: 10.68.19.61  

### A4
- **Network**: 10.68.12.0  
- **Subnet Mask**: 255.255.254.0  
- **Broadcast**: 10.68.13.255  
- **Range IP**: 10.68.12.1 - 10.68.13.254  
- **Router**: 10.68.13.254  
- **Gura_Ame_Ina (309 Hosts)**: 10.68.13.253  
- **Kiara_Calli (193 Hosts)**: 10.68.13.252  

### A5
- **Network**: 10.68.19.72  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.75  
- **Range IP**: 10.68.19.73 - 10.68.19.74  
- **Holo-EN**: 10.68.19.74
- **Holo-Myth**: 10.68.19.73

### A6
- **Network**: 10.68.19.76  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.79  
- **Range IP**: 10.68.19.77 - 10.68.19.78  
- **Holo-EN**: 10.68.19.78
- **HoloAdvent**: 10.68.19.77

### A7
- **Network**: 10.68.19.0  
- **Subnet Mask**: 255.255.255.224  
- **Broadcast**: 10.68.19.31  
- **Range IP**: 10.68.19.1 - 10.68.19.30  
- **Router**: 10.68.19.30  
- **FucaMoco (5 Hosts)**: 10.68.19.29  
- **Shiori_Nerissa (12 Hosts)**: 10.68.19.28  
- **Biboo (10 Hosts)**: 10.68.19.27  

### A8
- **Network**: 10.68.19.80  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.83  
- **Range IP**: 10.68.19.81 - 10.68.19.82  
- **HoloLive**: 10.68.19.82
- **Holo-EN**: 10.68.19.81 

### A9
- **Network**: 10.68.19.84  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.87  
- **Range IP**: 10.68.19.85 - 10.68.19.86  
- **HoloLive**: 10.68.19.86
- **Holo-ID**: 10.68.19.85

### A10
- **Network**: 10.68.19.88  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.91  
- **Range IP**: 10.68.19.89 - 10.68.19.90  
- **Holo-ID**: 10.68.19.90
- **AREA 15**: 10.68.19.89

### A11
- **Network**: 10.68.19.92  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.95  
- **Range IP**: 10.68.19.93 - 10.68.19.94  
- **Holo-ID**: 10.68.19.94
- **holoro**: 10.68.19.93

### A12
- **Network**: 10.68.19.96  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.99  
- **Range IP**: 10.68.19.97 - 10.68.19.98  
- **Holo-ID**: 10.68.19.98
- **holoh3ro**: 10.68.19.97

### A13
- **Network**: 10.68.8.0  
- **Subnet Mask**: 255.255.252.0  
- **Broadcast**: 10.68.11.255  
- **Range IP**: 10.68.8.1 - 10.68.11.254  
- **Router**: 10.68.11.254  
- **Moona (204 Hosts)**: 10.68.11.253  
- **Risu (319 Hosts)**: 10.68.11.252  
- **Iofi (140 Hosts)**: 10.68.11.251  

### A14
- **Network**: 10.68.18.192  
- **Subnet Mask**: 255.255.255.192  
- **Broadcast**: 10.68.18.255  
- **Range IP**: 10.68.18.193 - 10.68.18.254  
- **Router**: 10.68.18.254  
- **Ollie (20 Hosts)**: 10.68.18.253  
- **Anya (3 Hosts)**: 10.68.18.252  
- **Reine (10 Hosts)**: 10.68.18.251  

### A15
- **Network**: 10.68.16.0  
- **Subnet Mask**: 255.255.254.0  
- **Broadcast**: 10.68.17.255  
- **Range IP**: 10.68.16.1 - 10.68.17.254  
- **Router**: 10.68.17.254  
- **Zeta (81 Hosts)**: 10.68.17.253  
- **Kaela (71 Hosts)**: 10.68.17.252  
- **Kobo (149 Hosts)**: 10.68.17.251

### A16
- **Network**: 10.68.19.100  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.103  
- **Range IP**: 10.68.19.101 - 10.68.19.102  
- **Hololive**: 10.68.19.102
- **Holo-JP**: 10.68.19.101

### A17
- **Network**: 10.68.19.64  
- **Subnet Mask**: 255.255.255.248  
- **Broadcast**: 10.68.19.71  
- **Range IP**: 10.68.19.65 - 10.68.19.70  
- **Holo-JP**: 10.68.19.70
- **DEV_IS**: 10.68.19.89
- **GEN:0**: 10.68.19.88

### A18
- **Network**: 10.68.19.32  
- **Subnet Mask**: 255.255.255.240  
- **Broadcast**: 10.68.19.47  
- **Range IP**: 10.68.19.33 - 10.68.19.46  
- **Router**: 10.68.19.46  
- **Ririka_Raden (7 Hosts)**: 10.68.19.45  
- **Ao (3 Hosts)**: 10.68.19.44  
- **Hajime_Kanade (3 Hosts)**: 10.68.19.43  

### A19
- **Network**: 10.68.0.0  
- **Subnet Mask**: 255.255.248.0  
- **Broadcast**: 10.68.7.255  
- **Range IP**: 10.68.0.1 - 10.68.7.254  
- **Router**: 10.68.7.254  
- **MiComet (1501 Hosts)**: 10.68.7.253  
- **Sora_Rodo_AZKi (542 Hosts)**: 10.68.7.252  
- **GEN:1**: 10.68.7.251  

### A20
- **Network**: 10.68.14.0  
- **Subnet Mask**: 255.255.254.0  
- **Broadcast**: 10.68.15.255  
- **Range IP**: 10.68.14.1 - 10.68.15.254  
- **Router**: 10.68.15.254  
- **FBK_Matsuri (234 Hosts)**: 10.68.15.253  
- **Aki_Hachama (235 Hosts)**: 10.68.15.252  

### A21
- **Network**: 10.68.19.104  
- **Subnet Mask**: 255.255.255.252  
- **Broadcast**: 10.68.19.107  
- **Range IP**: 10.68.19.105 - 10.68.19.106  
- **GEN:1**: 10.68.19.106
- **GAMERS**: 10.68.19.105

### A22
- **Network**: 10.68.18.0  
- **Subnet Mask**: 255.255.255.128  
- **Broadcast**: 10.68.18.127  
- **Range IP**: 10.68.18.1 - 10.68.18.126  
- **Router**: 10.68.18.126  
- **Korone (41 Hosts)**: 10.68.18.125  
- **Okayu (41 Hosts)**: 10.68.18.124  
- **Mio (38 Hosts)**: 10.68.18.123  
