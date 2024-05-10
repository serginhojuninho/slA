function setup() {
  createCanvas(800, 800);
  background('purple');
}

function draw() {

  stroke('red');
  fill('black');

 // console.log(mouseIsPressed);
  
  if(mouseIsPressed) {
  rect(mouseX,mouseY,35,35);
  }
  



}








let cor;
  let posicaoHorizontal; // x
  let posicaoVertical; // y

  function setup (){
    
    createCanvas(400, 400);
    background(color(100, 0, 0));
    cor = color(random(0, 255), random(0, 255), random(0, 255));
    posicaoHorizontal = 200;
    posicaoVertical = 200;
  }

  function draw() {
    
    fill(cor);
    circle(posicaoHorizontal, posicaoVertical, 50);
    
    if(mouseX < posicaoHorizontal) {
    posicaoHorizontal = posicaoHorizontal -1;  
    }
    
    if(mouseY > posicaoHorizontal) 
  }
