# Java-

public static void main(string[] args){
Scanner sc = new Scanner(System.in
;
boolean run = true;

int speed = o;



system.out.println("-----------------");
system.out.println("1. 중속 || 2. 감속 || 3. 중지");
system.out.println("-----------------");
system.out.println("선택: ");

while(run){
  String strNum = sc.nextLine();

  if(strNum.equals("1")) {
    speed++;
    system.out.println("현제속도"+ speed);
    }else if(strNum.equals("2")){
      speed--;
      system.out.println("현제 속도"+ speed);
    }
    else if(strNum.equals("3")){
    run = false;
    system.out.println("자동차를 중지 시킵니다");
  }else{
     system.out.println("잘못된 값을 입력하셨스니다.");
  system.outprintln("프로그램을 종료합니다.");
  }
