# integrado
Practico Evaluativo

## Ejemplo: En una clase ajenda y tenemos una clase contactos, una ajenda registra varios contactos

## Composición: es una relación donde la clase contenida depende de la clase contador.

## Ejemplo: Tenemos una clase de silla, un objeto silla y una vez compuesto por cuatro objetos del tipo patas. El tiempo de vida de la clase pata depende de la vida de la clase silla.

## polimorfismo: está presente en la herencia ya que es la sobrecarga / sobreescritura de un método o atributo es decir que si tenes un método que puede ser determinado como un atributo de tipo "vehículo" también puede recibir atributos que sean de clases hijas.

 Si tienes una clase pasiente, sabes que los pasientes toman medicamentos. puede crear dos clases con nombres de pasiete, puede llamar al método de toma de medicamentos en estas 2 clases aunque sepan qué comportan de manera diferente.

```js
clase paciente
{
  constructor (medicacion) {
  this.medicacion = medicacion;

}
medicamento () {
 volver ("tipo de medicamento")
}
}
module.exports = paciente;

const carlos = require ('./ carlos');
pr = carlos nuevo ("medicacion 1");
console.info (medicamento ());

const Lura = require ('./ Lura');
pr = nueva Lura ("medicacion 2");
console.info (medicamento ());

const pasiente = require ('./ pasiente');
clase carlos extiende paciente {
    constructor (medicacion) {
       super (medicacon1);
       this.tipo = tipo;

    }
    medicamento () {
        volver ("carlos medicacion 1")
    }

}
const pasiente = require ('./ pasiente');
clase Lura extiende paciente {
    constructor (medicacion) {
       super (medicacon2);
