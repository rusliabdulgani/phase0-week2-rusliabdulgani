
<h1>Mengenal Penggunaan Function</h1>
<h3>Tugas 1</h3>

```/*
Buatlah kode disini
*/

function shutOut(){
  return("Hallo function!");
}
console.log(shutOut());
```

<h3>Tugas 2</h3>

```/*
Buatlah kode fungsi di bawah ini
*/
function calculateMultiply(num1,num2){
  return (num1 * num2);
}
var num1 = 5;
var num2 = 6;

var hasilPerkalian = calculateMultiply(num1,num2);
console.log(hasilPerkalian); // Menampilkan angka 30
```

<h3>Tugas 3</h3>

```/*
 BUATLAH KODE FUNCTION DISINI
*/
function processSentence(a, b, c, d){
  return ("Nama saya " +a+ ", umur saya " +b+ " tahun, alamat saya di " +c+ ", dan saya punya hobby yaitu " +d);
}
var name = "Agus";
var age = 30;
var address = "Jln. Malioboro, Yogjakarta";
var hobby = "gaming";

var fullSentence = processSentence(name,age,address,hobby);

console.log(fullSentence); // Menampilkan "Nama saya Agus, umur saya 30 tahun, alamat saya di Jln. Malioboro, Yogjakarta, dan saya punya hobby yaitu gaming!"
```