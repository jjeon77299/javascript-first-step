<h1>1. 이중 반복문</h1>

<h3> 자바스크립트는 객체 기반의 스크립트 프로그래밍 언어이다. 이 언어는 웹 브라우저 내에서 주로 사용하며, <br>다른 응용 프로그램의 내장 객체에도 접근할 수 있는 기능을 가지고 있다.</h3><br>
<br>
var는 javascript의 변수을 선언 할 수 있는 문법이다. ex) var i = 0;

![image](https://user-images.githubusercontent.com/97486359/173486113-669497f9-5411-4a5f-8fe5-8df03e852bba.png) <br>
이중 반복문을 사용해 테이블을 만들수있다.<br>
![image](https://user-images.githubusercontent.com/97486359/173486138-0cea7c1e-4202-4e8b-9884-5979b2400171.png)

<h1>2. 가위바위보 게임</h1>

![image](https://user-images.githubusercontent.com/97486359/173514197-7dde8af6-2aa3-4b77-b183-daa022252a3f.png)

switch case 문을 이용해 문자을 숫자로 만들고 컴퓨터에서 난수를 발생한다. <br>그 후 if 문을 사용해 내가 입력한 숫자와 컴퓨터와 난수로 발생한 숫자가 <br>같은 경우에는 맞는다는 이미지를 출력을 하고 나머지 경우에는 다른 이미지를 출력한다.

![image](https://user-images.githubusercontent.com/97486359/173514256-9628b606-2c91-411d-afd7-892e17234fba.png)

<h1>3. 실시간 시계</h1>

script 파일 <br>

![image](https://user-images.githubusercontent.com/97486359/174727430-4e67a03f-df58-4d3a-9995-a777adfe8634.png)

time 파일<br>

![image](https://user-images.githubusercontent.com/97486359/174727530-0768dbc1-6270-483f-96db-1398141f3891.png)

<h4>결과화면</h4>

기본화면<br><br>
![image](https://user-images.githubusercontent.com/97486359/174732540-c333d32b-c09c-4616-8d6e-5875795475f2.png)
GO버튼 클릭<br><br>
![image](https://user-images.githubusercontent.com/97486359/174728110-da290e8c-8e56-4fbf-a253-69e195fc8a77.png)
![image](https://user-images.githubusercontent.com/97486359/174732811-484b51a3-27fd-42c5-9afb-091c046bfadb.png)


<h3>코드 설명</h3>

script파일에서 Date함수를 이용해 시, 분, 초을 각각의 변수에 저장해 하나로 합치고 time파일의 \<h1>방식으로 출력다.
그 후 만약 GO를 클릭했을 때 go.onclick 함수에 있는 setInterval를 사용해 1초에 한 번 현재의 시간을 가져오는 작업을 진행합니다.
또한 STOP을 클릭하면 stop.onclick안에 있는 clearInterval를 사용해 시계를 멈출 수 있습니다.
