# shadows-of-nobu
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(color(random(255), random(255), random(255)))
    frameRate(6)
  fill("black");
  textSize(40);
  textAlign(CENTER, CENTER)
  
  let maximo = width;
  let minimo = 0;
  let palavra = "mikroaaltouuni";
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
  
//  if(mouseX < 50){
//    let palavra = "m";
//    text(palavra, 200, 200);
//  } else {
//    let palavra = "mikroaaltouuni";
//    text(palavra, 200, 200);
//  }
}
