# markdown

Apa itu markdown?
markdown adalah cara untuk gaya teks di web. Anda mengontrol tampilan dokumen; Memformat kata-kata sebagai huruf tebal atau miring, menambahkan gambar, dan membuat daftar hanyalah beberapa hal yang dapat kita lakukan dengan penurunan harga. Sebagian besar, penurunan harga hanya teks biasa dengan beberapa karakter non-abjad yang dilempar ke dalam, seperti # atau *.

Anda bisa menggunakan Markdown sebagian besar tempat di sekitar GitHub:
* Gist
* Komentar di Issues dan Pull Request
* File dengan ekstensi .md atau .markdown
Untuk informasi lebih lanjut, lihat "Menulis di GitHub" di Help GitHub.

## Examples

It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)


# Panduan sintaks
Berikut adalah ikhtisar tentang sintaks penurunan harga yang dapat Anda gunakan di mana saja di GitHub.com atau di file teks Anda sendiri.

# Judul
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

Tekanan
 *  *Teks ini akan miring*
  
* _Ini juga akan menjadi italic_

*  **Teks ini akan dicetak tebal**
* _Ini juga akan berani_

_You ** bisa ** menggabungkan them_

# Daftar

Tidak dipesan
* Item 1
* Item 2
  * Item 2a
  * Item 2b

 Pesanan
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

Gambar
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

Link
http://github.com - automatic!
[GitHub](http://github.com)

Blockquotes

seperti kata Kanye West:

> Kita hidup di masa depan begitu
> masa kini adalah masa lalu kita.

Kode inline

Saya pikir Anda harus menggunakan
`<addr>` elemen di sini sebagai gantinya.

GitHub Flavored Markdown
GitHub.com menggunakan versi sintaks Markdown sendiri yang menyediakan seperangkat fitur tambahan yang berguna, yang banyak mempermudah kerja dengan konten di GitHub.com.

Perhatikan bahwa beberapa fitur GitHub Flavoured Markdown hanya tersedia dalam deskripsi dan komentar dari Isu dan Permintaan Tarik. Ini termasuk @mentions serta referensi tentang SHA-1 hash, Issues, and Pull Requests. Daftar Tugas juga tersedia dalam komentar Gist dan dalam file Gist Markdown.

Penyorotan sintaks
Berikut adalah contoh bagaimana Anda bisa menggunakan penyorotan sintaks dengan GitHub Flavored Markdown:
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
Anda juga bisa hanya indent kode Anda dengan empat spasi:
 function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    
Berikut adalah contoh kode Python tanpa penyorotan sintaksis:
def foo():
    if not bar:
        return True
        
Daftar tugas
- [x] @mentions, #refs, [links] (), ** format **, dan tag <del> </ del> didukung
- [x] daftar sintaks yang diperlukan (daftar yang tidak teratur atau yang dipesan)
- [x] ini adalah item yang lengkap
- [] ini adalah item yang tidak lengkap

Jika Anda menyertakan daftar tugas di komentar pertama suatu Issue, Anda akan mendapatkan indikator kemajuan praktis dalam daftar masalah Anda. Ini juga bekerja di Pull Requests!

## Tabel
Anda dapat membuat tabel dengan menyusun daftar kata dan membaginya dengan tanda hubung - (untuk baris pertama), dan kemudian memisahkan setiap kolom dengan pipa |.

Header Pertama | Header Kedua
------------ | -------------
Konten dari sel 1 | Konten dari sel 2
Konten di kolom pertama | Isi di kolom kedua

Referensi SHA

Setiap referensi ke hash SHA-1 komit akan diubah secara otomatis menjadi tautan ke komit pada GitHub.
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

Issue references within a repository

Any number that refers to an Issue or Pull Request will be automatically converted into a link.
#1
mojombo#1
mojombo/github-flavored-markdown#1

Nama pengguna @mentions
Mengetik simbol @, diikuti oleh nama pengguna, akan memberi tahu orang tersebut untuk datang dan melihat komentarnya. Ini disebut "@mention", karena Anda menyebutkan individu. Anda juga bisa @mention tim dalam sebuah organisasi.

## Tautan otomatis untuk URL
Setiap URL (seperti http://www.github.com/) akan otomatis dikonversi menjadi tautan yang dapat diklik.

## Dicoret
Setiap kata dibungkus dengan dua tildes (seperti ~~ this ~~) akan muncul dicoret.

## Emoji
GitHub mendukung emoji! : berkilau:: unta:: boom:
Untuk melihat daftar setiap gambar yang kami dukung, lihat lembar Cheat Emoji.
