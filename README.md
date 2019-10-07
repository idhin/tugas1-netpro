# tugas1-netpro
1301188571 | Khulafaur Rasyidin

## Nomor 1
![Soal-1](https://user-images.githubusercontent.com/29471376/66278507-e937c300-e8d3-11e9-8037-f7e63bce1643.png)
Diagram di atas merupakan proses dari TCP three-way handshake, di mana dimulai dari belum terdapat koneksi hingga melewati beberapa states sampai koneksi dibuat. Dengan menggunakan tiga jenis pesan yang sebagai penentu transisi antar state, yaitu:

1. SYN: merupakan synchronize message, digunakan untuk memulai dan membuat koneksi
2. ACK: merupakan acknowledgment message, sebagai penanda bahwa menerima pesan SYN atau FIN
3. FIN: merupakan finish message, sebagai penanda bahwa server ingin memutuskan koneksi

## Nomor 2
#### Program For Loop
![image](https://user-images.githubusercontent.com/29471376/66278534-3ae04d80-e8d4-11e9-8c2a-c425a845593d.png)

- program for melakukan loop sesuai dengan keadaan yang ditentukan dengan nilai awalan i = 1
- for pertama mencetak nilai i, selama i <= 3. Didapat hasil 1 2 3
- for ke dua mencetak nilai j selama j <= 9, dengan awalan j = 7. Didapat hasil 7 8 9
- for ke tiga merupakan loop forever dengan mencetak string “loop” , namun terdapat break sehingga loop hanya dilakukan sekali saja. Didapat hasil berupa string “loop”
- for ke empat mencetak nilai n dengan awalan n = 0, selama n <= 5 dengan kondisi jika n mod 2 = 0 maka nilai n tidak akan dicetak, melainkan mencetak angka ganjil. Didapat hasil 1 3 5

#### Program If Else
![image](https://user-images.githubusercontent.com/29471376/66278561-91e62280-e8d4-11e9-9b6a-ec283d4aec23.png)
- program if/else melakukan pengecekan dari suatu kondisi jika memuhi maka melakukan aksi dari kondisi tersebut
- kondisi pertama, jika 7 mod 2 = 0, maka mencetak string “7 is even”, jika bukan maka mencetak string “7 is odd”. Didapat hasil 7 is odd
- kondisi ke dua, jika 8 mod 2 = 0, maka mencetak string “8 is divisible by 4”, jika bukan maka lanjut ke kondisi ke tiga. Didapat hasil 8 is divisible by 4
- kondisi ke tiga memiliki awalan nilai num = 9 dengan kondisi, jika num < 0 maka cetak “9 is negative”, jika num < 10 maka cetak “9 has 1 digit”, jika tidak keduanya maka cetak “9 has multiple digits”. Didapat hasil 9 has 1 digit
