# Happy-Rainbow-Carrot-Robot-and-Pac-Man
HAPPY HAPPY HAPPY RAINBOW RAINBOW RAINBOW CARROT CARROT CARROT ROBOT ROBOT ROBOT AND AND AND PAC PAC PAC MAN MAN MAN
void setup() {
  size(666, 666);
  background(255, 0, 217);
}
  
void draw() {
//red:
fill(255, 0, 0);
//decorations:
square(66, 66, 66);
//orange:
fill(255, 140, 0);
square(166, 66, 66);
//yellow:
fill(255, 247, 0);
square(266, 66, 66);
//green:
fill(0, 255, 4);
square(366, 66, 66);
//Turquoise:
fill(0, 255, 225);
square(466, 66, 66);
//blue:
fill(0, 64, 255);
square(566, 66, 66);
//face:
fill(255, 140, 0);
triangle( 100, 200, 300, 200, 200, 600);
//hair:
line( 400, 250, 200, 200);
line( 400, 200, 200, 200);
line( 400, 300, 200, 200);
line( 400, 350, 200, 200);
line( 400, 100, 200, 200);
line( 400, 150, 200, 200);
line( 50, 150, 200, 200);
line( 50, 200, 200, 200);
line( 50, 450, 200, 200);
line( 50, 400, 200, 200);
line( 50, 300, 200, 200);
line( 50, 10, 200, 200);
line( 50, 150, 200, 200);
line( -150, 350, 200, 200);
line( -150, 250, 200, 200);
//eyes:
fill( 255, 255, 255);
circle( 150, 350, 70);
circle( 200, 350, 70);
fill( 1, 1, 1);
circle( 130, 350, 25);
circle( 180, 350, 25);
//eyebrows:
fill(33, 32, 32);
rect( 100, 300, 150, 15);
//mouth:
circle( 200, 450, 55);
  strokeWeight(15);
fill(255, 247, 0);
  arc(400, 450, 100, 150,
  radians(90),
  radians(360));
  if (mousePressed) {
    square( 666, 666, 666);
  }
}
  
