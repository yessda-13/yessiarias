function saludar() {
    let nombre = prompt("¿Cuál es tu nombre?");
    if (nombre) {
        alert("Hola " + nombre + ", suerte en tu examen!");
    }
}


function calcularCuadrado() {
    let numero = parseFloat(prompt("Ingresa un número:"));
    if (!isNaN(numero)) {
        let resultado = numero * numero;
        alert("El cuadrado de " + numero + " es: " + resultado);
    } else {
        alert("Por favor, ingresa un número válido.");
    }
}
