### 기능 요구사항
v. 참여자 (Participants / Participant 클래스)
- [x] 참여자 이름 최대 5글자 유효성 검사 
- [x] 빈 공백, Null 불가
- [x] 참여자 객체는 이름에 논리적 동등성을 부여한다 equals hascode 적용
- [x] 참가자 2명 미만에 대한 유효성 검사 

v. 사다리 이동 경로(LineGenerator / RandomLineGenerator 클래스)
- [x] 사다리 이동 경로 생성방식은 Random
- [x] 이동경로 사이즈는 참여자수 - 1
- [x] 랜덤 생성 방식의 전체조건 규칙 : true가 연속적으로 이어지면 안된다
 
v. 사다리(Ladder 클래스) 
- [x] 사다리 넓이의 크기는 참여자 수와 동일 
- [x] 사다리 높이는 2 이상이어야한다. 

v. 입력 view
- [x] 사다리 게임의 보상을 입력받는다 
- [x] 사람 이름은 쉼표(,)를 기준으로 구분
- [x] 참여자 이름 최대 5글자 유효성 검사
- [x] 사다리 높이 입력을 받는다 

v. 출력 view
- [x] 참가자 이름은 공백포함 5글자로 표시되어야하며, 참가자간 한칸 공백기준으로 출력된다

v. 위치
- [x] 위치는 x좌표, y좌표로 나타낼 수 있다.
- [x] 좌표값은 0보다 작을 수 없다. 
- [x] 사다리 행간 이동은 절대값 1만 가능하며, 행간이 이동이 없을 수도 있다(0)

v. 사다리 보상 및 결과
- [x] 사다리 보상은 참가자 수와 1:1 매칭관계가 되어야한다