# camelStellarVPN
스텔라리스 멀티 가속을 위한 VPN서버


이론: https://gall.dcinside.com/stellaris/78670

실험결과: https://gall.dcinside.com/stellaris/79909

위 내용에 따라 멀티플레이 가속을 위한 VPN서버를 운영합니다.

VPN적용이 확인된 게임:
 - 스텔라리스 (대폭 개선됨)
 - 유로파 유니버셜리스 4 (대폭 개선됨)
 - 하츠 오브 아이언 4

해당 VPN은 일반적으로 개인에게 서비스되는 VPN과 달리 인터넷 연결을 VPN을 통하여 라우팅 하지 않고(IP변경 기능이 없고)  
접속한 사용자 간에 가상 네트워크를 형성해 주는 역할만 합니다.  
보안상 문제가 없으니 안심하고 사용하셔도 좋습니다.  



<h3>vpn계정요청방법: </h3>

※비밀번호는 아이디와 다르게 설정할 것, 영문 숫자 포함 6글자 이상으로 할 것.

- 이메일 사용

dja12123@naver.com 으로 사용할 ID와 PW 작성하여 보내기.



- 디스코드 사용

1. 디스코드 camelCase#6543 친구 추가

2. VPN에서 사용할 아이디와 비밀번호를 결정한 다음 camelCase에게 계정 요청

양식:

안녕하세요 VPN계정 신청합니다.

ID: id

PW: pw


<h3>vpn접속방법:</h3>


1. openvpn 다운로드

https://openvpn.net/community-downloads/
접속후

![Cap 2021-04-17 00-59-27-177](https://user-images.githubusercontent.com/20336315/115051831-34468380-9f18-11eb-8a84-949ad20b7991.png)

클라이언트 프로그램 다운로드 후 설치(설치중 권한요청 창이 뜨면 허용 누를것)


2. openvpn설정파일 임포트 하기

![Cap 2021-04-17 01-05-04-249](https://user-images.githubusercontent.com/20336315/115052579-12013580-9f19-11eb-92f2-8d0e0d59605e.png)

파일 다운로드 후 camelStellarVPN.ovpn파일을 압축풀기

![Cap 2021-04-17 01-02-03-025](https://user-images.githubusercontent.com/20336315/115052542-04e44680-9f19-11eb-9ead-b6c605983bf9.png)

다운로드 받은 파일을 불러온 후 연결

![Cap 2021-04-29 17-31-26-116](https://user-images.githubusercontent.com/20336315/116523242-fdf20680-a910-11eb-9ccb-ae1277c7488b.png)

이후, 계정입력 창이 뜨면 지급받은 계정 입력

![Cap 2021-04-29 17-31-37-969](https://user-images.githubusercontent.com/20336315/116523285-09ddc880-a911-11eb-8903-dec0e83bc784.png)

![Cap 2021-04-29 17-32-01-579](https://user-images.githubusercontent.com/20336315/116523300-0e09e600-a911-11eb-95af-bd03267ae2b6.png)

녹색 불 확인


<h3>주의사항: </h3>

 - 방에 있는 모든 사람이 VPN을 적용해야 효과를 볼 수 있으므로 멀티 인원을 모집 할 때 VPN사용을 공지 하는것을 추천.
 - VPN을 먼저 실행하고 게임을 실행해야 VPN이 적용됨.


<h3>변경내역</h3>

 - 21-04-22 보안조치: Paradox사 멀티플레이에 사용되는 포트 이외에 다른 포트 차단.

