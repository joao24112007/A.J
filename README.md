 nome: str = "Maria"
idade: int = 16
altura: float = 1.65
ativo: bool = True

let nome = "Maria"; // string
let idade = 16; // number (inteiro)
let altura = 1.65; // number (decimal)
let ativo = true; // boolean

a + b # soma
a - b # subtrao
a * b # multiplicao
a / b # diviso
# Operadores lgicos:
a and b
not a
a or b

a + b // soma
a - b // subtrao
a * b // multiplicao
a / b // diviso
// Operadores lgicos:
a && b
!a
a || b

if idade >= 18:
print("Maior de idade")
elif idade >= 16:
print("Pode votar")
else:
print("Menor de idade")

if (idade >= 18) {
console.log("Maior de idade");
} else if (idade >= 16) {
console.log("Pode votar");
} else {
console.log("Menor de idade");
}

let dia = 2;
switch (dia) {
case 1:
console.log("Domingo");
break;
case 2:
console.log("Segunda");
break;
default:
console.log("Outro dia");
}

# for
for i in range(5):
print(i)
# while
contador = 0
while contador < 5:
print(contador)
contador += 1

// for
for (let i = 0; i < 5; i++) {
console.log(i);
}
// while
let contador = 0;
while (contador < 5) {
console.log(contador);
contador++;
}
// do while
let x = 0;
do {
console.log(x);
x++;
} while (x < 5);
