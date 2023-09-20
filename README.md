# GeoID-API
Province, Regencies, Districts, and Villages API Data of Indonesia

## ENDPOINTS

#### 1. Mengambil Daftar Provinsi

```
GET https://raw.githubusercontent.com/vionaaindah/GeoID-API/main/provinces.json
```

Contoh Response

```
[
  {
    "id": "11",
    "name": "ACEH",
    "alt_name": "ACEH",
    "latitude": 4.36855,
    "longitude": 97.0253
  },
  {
    "id": "12",
    "name": "SUMATERA UTARA",
    "alt_name": "SUMATERA UTARA",
    "latitude": 2.19235,
    "longitude": 99.38122
  },
  ...
]
```

#### 2. Mengambil Daftar Kabupaten/Kota

```
GET https://raw.githubusercontent.com/vionaaindah/GeoID-API/main/regencies.json
```

Contoh Response

```
[
  {
    "id": "1101",
    "province_id": "11",
    "name": "KABUPATEN SIMEULUE",
    "alt_name": "KABUPATEN SIMEULUE",
    "latitude": 2.61667,
    "longitude": 96.08333
  },
  {
    "id": "1102",
    "province_id": "11",
    "name": "KABUPATEN ACEH SINGKIL",
    "alt_name": "KABUPATEN ACEH SINGKIL",
    "latitude": 2.41667,
    "longitude": 97.91667
  },
  ...
]
```

#### 3. Mengambil Daftar Kecamatan

```
GET https://raw.githubusercontent.com/vionaaindah/GeoID-API/main/districts.json
```

Contoh Response

```
[
  {
    "id": "1101010",
    "regency_id": "1101",
    "name": "TEUPAH SELATAN",
    "alt_name": "South Teupah, Simeulue Regency, Aceh, Indonesia",
    "latitude": 2.38603,
    "longitude": 96.42904
  },
  {
    "id": "1101020",
    "regency_id": "1101",
    "name": "SIMEULUE TIMUR",
    "alt_name": "East Simeulue, Simeulue Regency, Aceh, Indonesia",
    "latitude": 2.51438,
    "longitude": 96.31197
  },
  ...
]
```

#### 4. Mengambil Daftar Kelurahan/Desa

```
GET https://raw.githubusercontent.com/vionaaindah/GeoID-API/main/villages.json
```

Contoh Response

```
[
  {
    "id": "1101010001",
    "district_id": "1101010",
    "name": "LATIUNG",
    "latitude": null,
    "longitude": null
  },
  {
    "id": "1101010002",
    "district_id": "1101010",
    "name": "LABUHAN BAJAU",
    "latitude": null,
    "longitude": null
  }
  ...
]
```
