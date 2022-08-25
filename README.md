void setup()
{
  size(500,500);
  background(180,229,255);
}

void draw()
{
  noStroke();
  
  //sun
  fill(252,255,82);
  ellipse(480,0,170,170);
  
  //water
  fill(5,163,245);
  rect(0,225,500,275);
  
  //lilypad
  fill(23,157,6);
  ellipse(250,330,350,250);
  fill(5,163,245);
  triangle(130,430,190,380,155,440);
  
  //body
  fill(119,206,129);
  ellipse(250,280,270,250);
  ellipse(180,175,90,100);
  ellipse(320,175,90,100);
  
  //eyes
  fill(0,0,0);
  ellipse(180,180,40,50);
  ellipse(320,180,40,50);
  fill(255,255,255);
  ellipse(175,170,10,10);
  ellipse(315,170,10,10);
  
  //mouth
  noFill();
  stroke(10); //how do i make it thicker
  arc(250,220,40,20,PI/8,7*PI/8);
  
  //cheeks
  noStroke();
  fill(247,227,245);
  ellipse(168,250,45,45);
  ellipse(332,250,45,45);
  
  //belly
  fill(183,232,189);
  ellipse(250,340,180,120);
}
