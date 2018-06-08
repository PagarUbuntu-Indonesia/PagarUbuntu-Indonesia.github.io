---
judul: "Markdown"
penulis: lappet
layout: post
---

Markdown merupakan salah satu format penulisan konten untuk website.
Dengan markdown, penulisan konten website dengan lebih dimudahkan dibandingkan dengan penulisan kode html.


## Contoh

### Teks
---

##### Markdown:

```markdown
Contoh penulisan konten web dengan markdown.
Teks dapat ditulis  **cetak tebaal**, *cetak miring* dan __*miring dan tebal*__.

Teks ~~dicoret~~.

Contoh link: [link PUI!](https://PagarUbuntu-Indonesia.github.io)
```

##### Hasil:

Contoh penulisan konten web dengan markdown.
Teks dapat ditulis  **cetak tebal**, *cetak miring* dan __*miring dan tebal*__.

Teks ~~dicoret~~.

Contoh link: [link PUI!](https://PagarUbuntu-Indonesia.github.io)


### Daftar

##### Markdown:

```markdown
Daftar dengan angka:

1. Saty
2. Dua
3. Tiga


Daftar dengan poin:

* Satu
* Dua
* Tiga

Daftar bertingkat:

1. Satu
   - Satu-A
     * Satu-A-1
     * Satu-A-2
   - Satu-B
2. Dua
3. Tiga

Daftar tugas:

- [x] Satu
- [ ] Dua
- [x] Tiga
```

##### Hasil

Daftar dengan angka:

1. Saty
2. Dua
3. Tiga


Daftar dengan poin:

* Satu
* Dua
* Tiga

Daftar bertingkat:

1. Satu
   - Satu-A
     * Satu-A-1
     * Satu-A-2
   - Satu-B
2. Dua
3. Tiga

Daftar tugas:

- [x] Satu
- [ ] Dua
- [x] Tiga


### Gambar

##### Markdown:

Sintaks: `[Teks altenatif](<url gambar>)`

```markdown
![Contoh Gambar](/ok.png)
```

##### Hasil

![Contoh Gambar](/ok.png)


### Kepala (Header)

#### Markdown:

```markdown
# H1

## H2

### H3

#### H4

##### H5

###### H6
```

#### Hasil

# H1

## H2

### H3

#### H4

##### H5

###### H6


### Kutipan

#### Markdown:

```markdown
> Contoh Kutipan
  Wew! Ada teks _miring_ dan __tebal__
> - Anon
```

#### Hasil

> Contoh Kutipan. 
  wew! Ada teks _miring_ dan __tebal__
> - Anon


### Kode

#### Markdown:

`` `if (true) { return not false; }` ``

````markdown
```cpp
if (true) {
    return not false;
}
```
````

#### Hasil

`if (true) { return not false; }`

```cpp
if (true) {
    return not false;
}
```


### Tabel

#### Markdown:

```markdown
Kepala 1 | Kepala 2 (rata tengah) | Kepala 3 (rata kanan)
---------|:----------------------:|--------------------:|
Baris 1, kolom 1 | Baris 1, kolom 2 | Baris 1, kolom 3
Baris 2, kolom 1 | Baris 2, kolom 2 | Baris 2, kolom 3
```

#### Hasil

Kepala 1 (rata kiri) | Kepala 2 (rata tengah) | Kepala 3 (rata kanan)
---------------------|:----------------------:|-----------------------:|
Baris 1, kolom 1 | Baris 1, kolom 2 | Baris 1, kolom 3
Baris 2, kolom 1 | Baris 2, kolom 2 | Baris 2, kolom 3


## Selengkapnya

* [Sintaks Markdown](https://daringfireball.net/projects/markdown/syntax)
* [Masteing Markdown @ github.com](https://guides.github.com/features/mastering-markdown/)