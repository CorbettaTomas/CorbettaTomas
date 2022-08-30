import "./styles.css";

let n = prompt("coloque el numero...");

while (Number(n) === 0) {
  n = prompt('coloque el numero...')
}
if (Number(n) % 2 === 0) {
  console.log("El numero es par");
} else {
  console.log("El numero es impar");
}
