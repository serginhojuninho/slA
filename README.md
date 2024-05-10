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
