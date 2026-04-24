# sesion-06
Clase 17.04
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}
//Pregunta dentro del parentesis 
//if es condicional 
// || permite hacer dos preguntas 
//si framecount es menor a 1000 pinta el fondo rojo 

//Si frameCount vale menos de 1000 o presiono el boton izquierdo hace el fondo rojo 
if(frameCount < 1000 || 
    (mouseIsPressed && mouseButton == "left")) {
  background(255,0,0);
   console.log(mouseButton);
 
  
}
//else if = En otro caso 

// Cuando se presione el boton derecho del mouse el fondo cambie a azul 
if (mouseIsPressed && mouseButton == "right")
{
  background(0,0,255);
}

