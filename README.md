const peso = 75;
const altura = 1.65;
const imc = Number((peso / (altura * altura)).toFixed(2));

switch (true) {
  case imc < 17:
    console.log("muito abaixo do peso");
    break;

  case imc >= 17 && imc <= 18.4:
    console.log("abaixo do peso");
    break;

  case imc >= 18.5 && imc <= 24.5:
    console.log("peso normal");
    break;

  case imc >= 25 && imc <= 29.9:
    console.log("acima do peso");
    break;

  case imc >= 29 && imc <= 35:
    console.log("obesidade grau 1");
    break;

  case imc >= 35 && imc <= 50:
    console.log("obesidaed grau 2");
    break;
}
