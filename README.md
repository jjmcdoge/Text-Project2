# Text-Project2
Homework
function preload(){
  jfont=loadFont("Font/coolfont.ttf");
}
function setup() {
  // put setup code here
    createCanvas(innerWidth, innerHeight);
 background("red");
}   
function draw() {
   
    textSize(32);
    textFont(jfont);
    textAlign(CENTER);
    noLoop();
    textStyle("coolfont");
       text("Harrisburg University",0, 100,innerWidth);
    textSize(14);
    textStyle("Sigma-Italic")
    text("My name is Josh my hobbies include building computers, playing video games, and creating games. During my 4 years at HU I want to learn new skills from utilizing game engines and coding. I live in Maryland and my favorite places to go to are the harbor, ocean city,and DC.  ",0, 175,innerWidth);
}

