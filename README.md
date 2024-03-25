# 2024-1-Graphics-Team-4
24년 그래픽스 팀 과제-1 4조

##  저희 조는 팀 프로젝트인만큼, 캐릭터들의 주제를 하나로 통합하면 좋겠다고 생각하여서 동물원 컨셉으로 각자 동물 캐릭터를 하나씩 만들어 보았습니다. 

### 과제 소감문 입니다
### 조장 : 20210815 백대현
### 조원 
### 20210811 박신원
### 20210814 백경민
### 20210830 천예준
------------------------------------------------------------------------------
20210815 백대현

컴퓨터 그래픽스 첫 번째 팀 과제인 나만의 2D 캐릭터 만들기를 하면서 3주간 배웠던 내용들을 다시 복습할 수 있는 기회가 되어서 매우 좋았고, 간단한 2D 캐릭터를 만드는데에도 많은 노력이 필요하다는 것을 알게 되었고, 2학년이 되어 처음 하는 팀 과제인만큼 걱정도 되었지만, 다른 사람들과 함께 과제를 어떻게 수행할 지 의논하고, 각자 작성한 코드를 하나로 합치는 과정에서 약간의 오류가 발생했지만 그것을 찾아는 과정조차 좋은 경험이었다고 생각하고 있으며, 그래픽스 실력 향상에 많은 도움이 되었던 과제라고 생각하고, 앞으로 배우는 내용들도 잘 학습하여서 좋은 성적 받을 수 있도록 노력할 것입니다. 

20210811 박신원

나만의 캐릭터 만들기를 하며 2D캐릭터임에도 많은 양의 노력이 들어가 우리가 일상에서 접하는 다양한 3D,2D캐릭터들에 들어간 시간과 노력에 대해 느낄 수 있었습니다.
또 기능을 추가하며 제가 원하는 기능이 구현되었을 떄의 기쁨도 느낄 수 있었습니다. 그래픽스 과목을 통해 캐릭터 뿐 아니라 제가 원하는 상상의 것들을 구현할 수 있는 역량을 갖출 수 있도록 노력해야겠다는 생각을 가지게 되었습니다.

20210814 백경민

p5.js를 사용하여 캐릭터를 만들면서 창의적이고 흥미진진한 시각적 작업을 할 수 있었습니다
 캐릭터를 만들면서 코딩을 통해 시각적인 측면을 직접 제어하고 상호작용을 추가하는 것 또한  기능을 추가할때마다 재미있었습니다 하지만 생각대로 모든 것을 구현할 실력은 안되었습니다  그러므로 p5.js의 다양한 함수와 기능을 더 깊이 있게 이해하기 위해 더 노력하겠습니다.

20210830 천예준

-처음 생각만 했을 때는 간단할 것 같았던 과제였지만, 막상 접하면서 실제로 해보니 많은 시간과 정성을 들이게 되는 과제였던 것 같습니다. 제가 하고싶은 모양이 있어도 구현하기가 쉽지 않았기에 앞으로 남은 수업들을 들으면서 더 발전 할 수 있는 제가 되었으면 좋겠다고 생각이 들었습니다. 또한 하나하나 만들어갈 때 뿌듯함도 있었고, 모르는 정보들은 찾아보면서 잘 모르거나 햇갈렸던 용어나 기능들도 다시 한 번 복습 또는 에습할 수 있었던 기회였던 것 같아서 의미있고 공부에 도움이 된 시간이였던 것 같습니다.

------------------------------------------------------------------------------
### 과제 코드입니다
-------------------------------------------------------------------------------
       function setup() {
     createCanvas(1200, 1200);
   }
   
   function draw() {
     background(204,255,153);
     //----------------------------------------------------------------------------------------------------------------
       //  24년 컴퓨터 그래픽스 나만의 2D 캐릭터 만들기 과제 4조
       //
       //  저희 조는 팀 프로젝트인만큼, 캐릭터들의 주제를 하나로 통합하면 좋겠다고 생각하여서
       //  동물원 컨셉으로 각자 동물 캐릭터를 하나씩 만들어 보았습니다.
       //
       //  20210815 백대현 - 원숭이 
       //  키보드 화살표 키로 위치 이동 가능 
       //  R키 입력 시 : 빨간색으로 바뀜
       //  G키 입력 시 : 초록색으로 바뀜
       //  B키 입력 시 : 파랑색으로 바뀜
       //  N키 입력 시 : 원래색으로 바뀜
       //
       //  일정 구간 이상 벗어나지 못하도록 해 두었습니다.
       //  
       //
       //  20210811 박신원 - 거북이
       //  J키 입력 시 : 초기 상태로 되돌아감
       //
       //  20210814 백경민 - 토끼
       //  키보드 W,A,S,D키로 위치 이동 가능
       //
       //  20210830 천예준 - 반달가슴곰
       //
       //
       //
       //
       //
       //---------------------------------------------------------------------------------------------------------------
     
     /*--------------------------------------------------과제 소감----------------------------------------------------
   
   20210815 백대현
   컴퓨터 그래픽스 첫 번째 팀 과제인 나만의 2D 캐릭터 만들기를 하면서 3주간 배웠던 내용들을 다시 복습할 수 있는 기회가 되어서 매우 좋았고, 간단한 2D 캐릭터를 만드는데에도 많은 노력이 필요하다는 것을 알게 되었고, 2학년이 되어 처음 하는 팀 과제인만큼 걱정도 되었지만, 다른 사람들과 함께 과제를 어떻게 수행할 지 의논하고, 각자 작성한 코드를 하나로 합치는 과정에서 약간의 오류가 발생했지만 그것을 찾아는 과정조차 좋은 경험이었다고 생각하고 있으며, 그래픽스 실력 향상에 많은 도움이 되었던 과제라고 생각하고, 앞으로 배우는 내용들도 잘 학습하여서 좋은 성적 받을 수 있도록 노력할 것입니다. 
   
   20210811 박신원
   나만의 캐릭터 만들기를 하며 2D캐릭터임에도 많은 양의 노력이 들어가 우리가 일상에서 접하는 다양한 3D,2D캐릭터들에 들어간 시간과 노력에 대해 느낄 수 있었습니다.
   또 기능을 추가하며 제가 원하는 기능이 구현되었을 떄의 기쁨도 느낄 수 있었습니다. 그래픽스 과목을 통해 캐릭터 뿐 아니라 제가 원하는 상상의 것들을 구현할 수 있는 역량을 갖출 수 있도록 노력해야겠다는 생각을 가지게 되었습니다.
   
   20210814 백경민
   p5.js를 사용하여 캐릭터를 만들면서 창의적이고 흥미진진한 시각적 작업을 할 수 있었습니다
    캐릭터를 만들면서 코딩을 통해 시각적인 측면을 직접 제어하고 상호작용을 추가하는 것 또한  기능을 추가할때마다 재미있었습니다 하지만 생각대로 모든 것을 구현할 실력은 안되었습니다  그러므로 p5.js의 다양한 함수와 기능을 더 깊이 있게 이해하기 위해 더 노력하겠습니다.
   
   20210830 천예준
   -처음 생각만 했을 때는 간단할 것 같았던 과제였지만, 막상 접하면서 실제로 해보니 많은 시간과 정성을 들이게 되는 과제였던 것 같습니다. 제가 하고싶은 모양이 있어도 구현하기가 쉽지 않았기에 앞으로 남은 수업들을 들으면서 더 발전 할 수 있는 제가 되었으면 좋겠다고 생각이 들었습니다. 또한 하나하나 만들어갈 때 뿌듯함도 있었고, 모르는 정보들은 찾아보면서 잘 모르거나 햇갈렸던 용어나 기능들도 다시 한 번 복습 또는 에습할 수 있었던 기회였던 것 같아서 의미있고 공부에 도움이 된 시간이였던 것 같습니다.
     
     ----------------------------------------------------------------------------------------------------------------*/
     //20210815 백대현 - 원숭이
     push();
     translate(-300,-350);
     monkey();
     pop();
     
     //20210811 박신원 - 거북이
     push();
       translate(1000,400);
       scale(0.5);
       sb();
       waterA();
       waterB();
       turtle();
      pop();
     
     push();
     translate(0,100);
     cage();
     pop();
     
   
     push();//20210814 백경민 - 토끼
       translate(600,1200)
       scale(0.7)
       push();
       translate(-100,0);
       rotate(angle+10);
       carrot();
       pop();
   
       push();
       translate(100,-100);
       rotate(-angle);
       carrot();
       pop();
   
       push();
       if (keyIsDown(87)) {  // w 키
         y_rabbit -= moveSpeed;  // 위쪽으로 이동
       }
       if (keyIsDown(83)) {  // s 키
         y_rabbit += moveSpeed;  // 아래쪽으로 이동
       }
       if (keyIsDown(65)) {  // a 키
         x_rabbit -= moveSpeed;  // 왼쪽으로 이동
       }
       if (keyIsDown(68)) {  // d 키
         x_rabbit += moveSpeed;  // 오른쪽으로 이동
       }
       translate(x_rabbit,y_rabbit);
       scale(scaleSize); // 크기 조절
       rotate(angle);
       rabbit();
       pop();
   
       angle += 0.11;
       scaleSize = 1 + sin(angle) * 0.5;
     pop();
     
     push();//20210830 천예준 - 반달가슴곰
     translate(700,600)
     bear();
     pop();
     
      push();
     translate(0,700);
     cage();
     pop();
     
     push();
     stroke(155,155,155);
     strokeWeight(40)
     line(920,000,920,2000);
     pop();
     
     push();
     
     rectMode(CENTER);
     fill(204,255,255);
     rect(920,900,100,100);
     textSize(50);
     fill(0,0,0);
     text("4조",880,920);
     pop();
   }
   
   //------------------------------원숭이 코드 시작------------------------------------------------
   //20210815 백대현 - 원숭이
     let bananaR = 0;
     let monkeyX=0;
     let monkeyY=0;
     let monkeySize=1;
     let monkeyR = 0;
     let monkeyD = 1;
     let monkeyRed = 153;
     let monkeyBlue = 51;
     let monkeyGreen = 103;
   
   function monkey(){
     //20210815 컴퓨터공학과 백대현
     //---------------------------------------------------------------------------------------------
     //  
     //  *좌우로 몸을 흔들고 팔을 움직이면서 이동*
     //
     //          ↑
     //        ←↓→  : 화살표 키를 이용해 원숭이 위치 조작 가능
     //  
     //        r : 원숭이 색 빨강으로 변경
     //        g : 원숭이 색 초록으로 변경
     //        b : 원숭이 색 파랑으로 변경  
     //        n : 원숭이 색 갈색으로 변경
     //
     //---------------------------------------------------------------------------------------------
     
     push();
       
       monkeyR += monkeyD * 0.5; //원숭이 좌우로 몸 흔들기
     
           if(monkeyR >= 10 || monkeyR <= -10){
             monkeyD *= -1;
           }
     
     pop();
     
     push();
     rectMode(CENTER);
     bananaR=bananaR+0.03;
     translate(width/2,height/2);
     scale(0.6)
     
     
     
       push();
         translate(200,260);
         scale(2);
         
         rotate(bananaR)
         bananaR=bananaR+0.03;
   
         stroke(255,204,0);//바나나 1
         strokeWeight(15);
         line(0,0,10,10);
         line(0,0,0,-20);
         line(0,-20,10,-30);
         strokeWeight(5);
         line(10,-30,20,-40);
         line(10,-50,30,-30);
         stroke(0,0,0);
         strokeWeight(3);
         line(15,13,13,15);
       pop();
   
   
           if(key == "r"){ //원숭이 색 빨강으로 변경
             monkeyRed=255;
             monkeyGreen=0;
             monkeyBlue=0;
           }
           if(key == "g"){ //원숭이 색 초록으로 변경
             monkeyRed=0;
             monkeyGreen=255;
             monkeyBlue=0;
           }
           if(key == "b"){ //원숭이 색 파랑으로 변경
             monkeyRed=0;
             monkeyGreen=0;
             monkeyBlue=255;
           }
           if(key == "n"){ //원숭이 색 갈색으로 변경
             monkeyRed=153;
             monkeyGreen=103;
             monkeyBlue=51;
           }
           
     
       push();
         translate(-300,-100);
         scale(4)
         
         rotate(-bananaR/2)
         
         stroke(255,204,0);//바나나 2
         strokeWeight(15);
         line(0,0,10,10);
         line(0,0,0,-20);
         line(0,-20,10,-30);
         strokeWeight(5);
         line(10,-30,20,-40);
         line(10,-50,30,-30);
         stroke(0,0,0);
         strokeWeight(3);
         line(15,13,13,15);
       pop();
   
     //------------------------------------------------------------------원숭이 이동 
       if(keyIsDown(LEFT_ARROW)){ //원숭이 왼쪽으로 이동
         monkeyX-=10;
       }
       if(keyIsDown(RIGHT_ARROW)){ //원숭이 오른쪽으로 이동
         monkeyX+=10;
       }
       if(keyIsDown(UP_ARROW)){ //원숭이 위쪽으로 이동
         monkeyY-=10;
       }
       if(keyIsDown(DOWN_ARROW)){ //원숭이 아래쪽으로 이동
         monkeyY+=10;
       }
     
       if(monkeyX >= 350){ //원숭이 이동 제한
         monkeyX = 350;
         
       }
       if(monkeyX <= -350){
         monkeyX = -350;
       }
       if(monkeyY >= 200){
         monkeyY = 200;
       }
       if(monkeyY <= -350){
         monkeyY = -350;
       }
     
     
     scale(monkeySize)
     translate(0,-150);
     translate(monkeyX,monkeyY);
     //------------------------------------------------------------------
     
     push(); //원숭이 몸
     rotate(radians(monkeyR)); //원숭이 몸 좌우로 
     monkeySize = 1 + sin(monkeyR/4) * 0.2;  //원숭이 크기 조정
     
       push();
         noStroke();
         fill(monkeyRed,monkeyGreen,monkeyBlue);
         ellipse(0,0,300,250); //머리
         ellipse(150,0,100,100); //귀
         ellipse(-150,0,100,100);
   
         ellipse(0,200,200,250);//몸통
         rect(0,250,200,100);
         arc(0,300,200,100,0,PI);
         
         rect(60,350,80,200,40)//다리
         rect(-60,350,80,200,40)
       
     
           push();//왼팔
             rectMode(CORNER);
             translate(80,110)
             
             rotate(radians(monkeyR*2+45));
             rect(0,0,200,70,40)
           pop();
     
           push();//오른팔
             rectMode(CORNER);
             translate(-30,160);
             rotate(radians(monkeyR*2+135));
             rect(0,0,200,70,40)
     
           pop();
   
        pop();
   
       push();//머리2
         fill(255,204,153);
         noStroke();
         ellipse(0,38,261,170);
         ellipse(-67,0,165,193);
         ellipse(67,0,165,193);
   
         rect(0,220,180,200,70); //몸통 2
       pop();
   
       push(); //입
         noStroke();
         fill(255,0,0);
         arc(0,30,130,100,0,PI,3);
       pop();
   
       push(); //코
         noStroke();
         fill(monkeyRed,monkeyGreen,monkeyBlue);
         ellipse(0,0,20,20);
   
         ellipse(0,250,25,25); //배꼽
   
       pop();
   
       push(); //눈
         fill(0,0,0);
         ellipse(-80,-30,40,40);
         ellipse(80,-30,40,40);
         fill(255,255,255);
         ellipse(90,-35,15,15);
         ellipse(-70,-35,15,15);
   
         strokeWeight(3);
         line(-5,245,5,255);//배꼽 선
         line(5,245,-5,255);
       pop();
     pop();
     
     
     
   }
   //------------------------------원숭이 코드 끝------------------------------------------------
   
   //------------------------------거북이 코드 시작------------------------------------------------
   
   //20210811 박신원
   
   let armAngle = 0;
   let ttx1 = 0;
   
   function waterA() { // 물방울 회전
     let ty = 300 * cos(frameCount * 0.03) + 200;
     let tx = 300 * sin(frameCount * 0.03) + 200;
     fill(0,120,255);
     circle(tx+80,ty+100,50);
    
   }
   function waterB() {
     let tj = 300 * -cos(frameCount * 0.03) + 200;
     let tk = 300 * -sin(frameCount * 0.03) + 200;
     fill(0,120,255);
     circle(tk+80,tj+100,50);
    
   }
   function turtle(){
     let ttx = 50 * -sin(frameCount * 0.03) + 100;
     let tty = 50 * -cos(frameCount * 0.03) + 100;
     push();  // 목 그리기
     fill(0,155,0);
     ellipse(ttx+250,tty+200,150,250);
     fill(0,255,0);
     rect(ttx+230,tty+10,40,120,30);
     pop();
    
     push();  //얼굴 그리기
     fill(0,255,0);
     rect(ttx+230,tty+10,80,40,30);
     pop();
    
     push(); // 왼쪽 팔 그리기
     translate(ttx+205,tty+120);
     rotate(PI/4);
     fill(0,255,0);
     rect(0,0,40,130,30);
     pop();
    
     push(); // 오른쪽 팔 그리기
     translate(ttx+275,tty+120);
     rotate(armAngle);
     fill(0,255,0);
     rect(0,0,40,-130,30);
     armAngle = armAngle + 0.01;
     if (armAngle > HALF_PI) armAngle =0;
     pop();
    
     push();  // 몸통 그리기
     fill(0,255,0);
     rect(ttx+255,tty+270,40,120,30);
     fill(0,255,0);
     rect(ttx+205,tty+270,40,120,30);
     fill(100,155,0);
     ellipse(ttx+250,tty+200,130,220);
     pop();
    
     push();  // 몸 중앙 무늬
     strokeWeight(3);
     stroke(155,150);
     beginShape(LINES);
     vertex(ttx+305, tty+150);
     vertex(ttx+195, tty+150);
     vertex(ttx+313, tty+200);
     vertex(ttx+187, tty+200);
     vertex(ttx+305, tty+250);
     vertex(ttx+195, tty+250);
     vertex(ttx+250, tty+92);
     vertex(ttx+250, tty+310);
     vertex(ttx+285, tty+108);
     vertex(ttx+285, tty+290);
     vertex(ttx+215, tty+108);
     vertex(ttx+215, tty+290);
     endShape();
     pop();
    
     push();  // 눈, 입 만들기
     fill(0);
     circle(ttx+285,tty+20,5);
     fill(255,0,0);
     arc(ttx+300,tty+40,13,13, TWO_PI, HALF_PI)
     pop();
    
   }
   
   function sb() {
     scale(ttx1 = ttx1 + 0.005);
     if(ttx1 > 2) ttx1 = 0;
   }
   function keyPressed() { // j를 누르면 다시 출력
     if(key == 'j') ttx1 = 0;
   }
   //------------------------------거북이 코드 끝------------------------------------------------
   
   //------------------------------토끼 코드 시작------------------------------------------------
   //20210814 백경민
   
   let x = 0; //위치
   let angle = 0; // 회전
   let scaleSize = 1.0; // 크기
   let x_rabbit = 0; // 토끼 위치 x
   let y_rabbit = 0; // 토끼 위치 y
   let moveSpeed = 3; // 이동 속도
   
   function rabbit () {
     stroke(0);
     fill(255);
     ellipse(x-40, x+165, 50,25); //왼발
     
     stroke(0);
     fill(255);
     ellipse(x+40, x+165, 50,25); //오른발
     
     stroke(255);
     fill(255);
     ellipse(x, x+100, 120, 140); //몸통
     
     stroke(0);
     arc(x-40, x+90, 25, 80, 0, PI); //왼손
     arc(x+40, x+90, 25, 80, 0, PI); //오른손
     
     stroke(255);
     fill(255);
     ellipse(x-40, x-78, 36, 120); //왼쪽 귀
     stroke(240,126,135);
     fill(240,126,135);
     ellipse(x-40, x-78, 20, 100);
     
     stroke(255);
     fill(255);
     ellipse(x+40, x-78, 36, 120); //오른쪽 wadw귀
     stroke(240,126,135);
     fill(240,126,135);
     ellipse(x+40, x-78, 20, 100);
     
     stroke(255);
     fill(255);
     ellipse(x, x, 140, 100); //머리
     
     stroke(255);
     fill(0);
     ellipse(x-40, x, 14, 14); //왼쪽 눈
     ellipse(x+40, x, 14, 14); //오른쪽 눈
     
     stroke(0);
     fill(0);
     ellipse(x, x+12, 8, 4);
     
     stroke(240,126,135);
     fill(240,126,135);
     triangle(x-5, x+35, x, x+32, x+5, x+35); // 입
     
     
   }
   
   //당근
   function carrot () {
     stroke(255,255,255);
     fill(92,198,98);
     triangle(x,60,x+20,60,x+10,110);
   
     fill(255,130,72);
     triangle(x-20,100,x+40,100,x+10,200);
   }
   
   //------------------------------토끼 코드 끝------------------------------------------------
   
   
   //------------------------------반달가슴곰 코드 시작------------------------------------------------
   //20210830 천예준
   
   let i = 0;
   function bear (){
      translate(width / 2, height / 2);
     rotate(i);
     let x = sin(i);
     scale(x);
     translate(-400, -400);
     i += 0.01;
     fill(0,0,0);
     ellipse(320, 270, 80, 80);
     ellipse(480, 270, 80, 80);
     fill(192,192,192);
     ellipse(320, 270, 40, 40);
     ellipse(480, 270, 40, 40);
     fill(0,0,0);
     ellipse(400, 350, 240, 200);
     ellipse(400, 530, 265, 285);
     quad(325,600, 390,600, 390,700, 325,700);
     quad(410,600, 475,600, 475,700, 410,700);
     rect(310,670, 82, 40, 80);
     rect(408,670, 82, 40, 90);
     //quad(200,510, 350,390, 350,450, 230,550);
     rect(210, 440, 130, 60, 80);
     rect(455, 440, 130, 60, 80);
     fill(255,255,255);
     ellipse(360,320, 40, 60);
     ellipse(430,320, 40, 60);
     fill(0,0,0);
     ellipse(370,320, 20, 40);
     ellipse(440,320,20,40);
     fill(255,255,255);
     ellipse(400,460,140,100);
     fill(0,0,0);
     ellipse(400,435,140,100);
     fill(255,228,196);
     ellipse(398, 380, 60, 70);
     fill(0,0,0);
     ellipse(398,370,30,20);
     line(398,370,398,400);
     fill(255,255,255);
     ellipse(398,395, 20,15);
     ellipse(242,470, 25,35);
     ellipse(230,450, 10,10);
     ellipse(223,457, 10,10);
     ellipse(220,467, 10,10);
     ellipse(223,477, 10,10);
     ellipse(230,487, 10,10);
     ellipse(552,470, 25,35);
     ellipse(562,448, 10,10);
     ellipse(570,457, 10,10);
     ellipse(575,467, 10,10);
     ellipse(572,478, 10,10);
     ellipse(565,487, 10,10);
   }
   //------------------------------반달가슴곰 코드 끝------------------------------------------------
   
   function cage(){ // 철창 코드
     push();
     rectMode(CENTER);
     fill(155,155,155);
     noStroke();
     rect(900,800,1200,40);
     rect(400,850,40,130);
     rect(530,850,40,130);
     rect(660,850,40,130);
     rect(790,850,40,130);
     rect(920,850,40,130);
     rect(1050,850,40,130);
     rect(1180,850,40,130);
     rect(1310,850,40,130);
     rect(1430,850,40,130);
     pop();
   }
   //----------------------------------------------------------------------------------------------------------------
       //  24년 컴퓨터 그래픽스 나만의 2D 캐릭터 만들기 과제 4조
       //
       //  저희 조는 팀 프로젝트인만큼, 캐릭터들의 주제를 하나로 통합하면 좋겠다고 생각하여서
       //  동물원 컨셉으로 각자 동물 캐릭터를 하나씩 만들어 보았습니다.
       //
       //  20210815 백대현 - 원숭이 
       //  키보드 화살표 키로 위치 이동 가능 
       //  R키 입력 시 : 빨간색으로 바뀜
       //  G키 입력 시 : 초록색으로 바뀜
       //  B키 입력 시 : 파랑색으로 바뀜
       //  N키 입력 시 : 원래색으로 바뀜
       //
       //  일정 구간 이상 벗어나지 못하도록 해 두었습니다.
       //  
       //
       //  20210811 박신원 - 거북이
       //  J키 입력 시 : 초기 상태로 되돌아감
       //
       //  20210814 백경민 - 토끼
       //  키보드 W,A,S,D키로 위치 이동 가능
       //
       //  20210830 천예준 - 반달가슴곰
       //
       //
       //
       //
       //
       //---------------------------------------------------------------------------------------------------------------
