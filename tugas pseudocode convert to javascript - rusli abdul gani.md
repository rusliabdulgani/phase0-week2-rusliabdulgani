<h1>Mengubah Pseudocode Menjadi Javascript </h1>
***
<h3>Tugas 1</h3>
***

```var nama;
var angkaPembilang, angkaPenyebut;

nama = prompt('Nama: ');
angkaPembilang = prompt ('Pembilang: ');
angkaPenyebut = prompt ('Penyebut: ');
hasilBagi = angkaPembilang/angkaPenyebut;
console.log('Hallo '+nama+', '+angkaPembilang+ ' dibagi ' +angkaPenyebut+ ' adalah sama dengan ' +hasilBagi);
```
<h3>Tugas 2</h3>
***

```var alasSegitiga, tinggiSegitiga, luasSegitiga;

alasSegitiga = prompt('Masukkan nilai alas segitiga: ');
tinggiSegitiga = prompt('Masukkan nilai tinggi segitiga: ');
luasSegitiga = alasSegitiga * tinggiSegitiga / 2;
console.log('Luas Segitiga: ' +luasSegitiga);
```
<h3>Tugas 3</h3>
***

```var tahun = 1988;
if (tahun%4===0){
  if (tahun%100!==0){
  console.log(tahun+' Adalah tahun kabisat');
}else if(tahun%400===0){
  console.log(tahun+' Adalah tahun kabisat');
}else{
  console.log(tahun+ ' Adalah bukan tahun kabisat');
}
}
  else{
    console.log(tahun+ ' Adalah bukan tahun kabisat');
  }
```