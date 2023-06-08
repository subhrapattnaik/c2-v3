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
https://studio.code.org/projects/gamelab/fNykX4SJylrTRciOW5am_nzTUgmSnc1rwpJq2Pf3B3U/view


https://studio.code.org/projects/gamelab/WzAFOu77Tm1W2uWEzInmdunoay_OpT5CnwiTSAXBCuQ/view

https://studio.code.org/projects/gamelab/jEG88osgPCP7flNtn6GyaOy4aCOcjOwJwkKcNgA8EdM/edit

https://studio.code.org/projects/gamelab/pBWKXlECXXtiho66TCyIooFQ0zzWkBp92_TRj95_o2w/view

