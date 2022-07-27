# API POINTS



## ARTIKEL
### Menampilkan seluruh artikel
```
GET: /artikel

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
### Menampilkan artikel berdasarkan ```id```
```
GET: /artikel/[id]

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
### Menambahkan artikel
```
POST: /artikel

data:
{
    "gambar"    : "",
    "thumbnail" : "",
    "judul"     : "",
    "p1"        : "",
    "p2"        : "",
    "markdown"  : ""
}

response:
true    //if true
false   //if false
```
### Mengubah artikel
```
PUT: /artikel

data:
{
    "gambar"    : "",
    "thumbnail" : "",
    "judul"     : "",
    "p1"        : "",
    "p2"        : "",
    "markdown"  : ""
}

response:
true    //if true
false   //if false
```
### Menghapus artikel
```
DELETE: /artikel

response:
true    //if true
false   //if false
```

# DATABASE DESIGN
![Design Database](https://raw.githubusercontent.com/rengganisss/tekweb2022/main/assets/design.png)
