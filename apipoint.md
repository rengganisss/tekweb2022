# API POINTS



## ARTICLE
### Menampilkan seluruh article
```
GET: /article

response:
[
  {
    "ID"        : "",
    "gambar"    : "",
    "thumbnail" : "",
    "judul"     : "",
    "p1"        : "",
    "p2"        : "",
    "markdown"  : ""
  },
  {
    ...
  }
]
```
### Menampilkan article berdasarkan ```id```
```
GET: /article/[id]

response:
{
    "ID"        : "",
    "gambar"    : "",
    "thumbnail" : "",
    "judul"     : "",
    "p1"        : "",
    "p2"        : "",
    "markdown"  : ""
}
```
### Menambahkan article
```
POST: /article

data:
{
    "gambar": "",
    "thumbnail": "",
    "judul": "",
    "p1": "",
    "p2": "",
    "markdown": ""
}

response:
true    //if true
false   //if false
```
### Mengubah article
```
PUT: /article

data:
{
    "gambar": "",
    "thumbnail": "",
    "judul": "",
    "p1": "",
    "p2": "",
    "markdown": ""
}

response:
true    //if true
false   //if false
```
### Menghapus article
```
DELETE: /article

response:
true    //if true
false   //if false
```

# DATABASE DESIGN
![Design Database](https://raw.githubusercontent.com/rengganisss/tekweb2022/main/assets/design.png)
