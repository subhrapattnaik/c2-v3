# c2-v3
var sprite2 = createSprite(200, 200, 20, 20);
sprite2.setAnimation("helicopter_1");

sprite.velocityY = -2;
sprite.velocityX = 1;

function draw() {
  rotateSprite(sprite2);
 // rotateSprite(sprite);
 
  ball.bounceOff(edges);
  
  drawSprites();
}
\
------------------------------------
\
//user defined function
\
//call this function inside draw() and outside draw()

\
function rotateSprite(sprite) {
  sprite.rotation = sprite.rotation +10;
  //sprite.rotation +=10;
}

----------------------

