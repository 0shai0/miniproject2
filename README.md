팀원 (총 4)<br/><br/>팀장 : 장성호<br/><br/>

팀원<br/><br/>이재빈, 이윤주, 명하영


Position<br/><br/>Front-End : 이재빈, 명하영, 장성호<br/><br/>Back-End : 이윤주


프로젝트에서 맡은 역할
메인 홈페이지 제작, 소개 페이지에서 서비스 소개 부분 제작, 게시판 제작


프로그램은 HTML, CSS, JS, SpringBoot

협업 툴 : GitHub


프로젝트 기간
12월 6일 ~ 12월 19일 (14)



프로젝트 목적

1. 회원가입, 로그인, 게시판, 구독 기능 구현
2. 로그인 페이지(회원가입 포함), 소개 페이지, 게시판 페이지,  내 정보 페이지, 관리자 페이지 구현


프로젝트 설명

 기술이 발전되어 자율 주행 자동차가 시장에 나왔다는 전제하에 어떤 서비스가 있으면 좋을까를 고민했습니다. 그 결과 여러번 구매를 하지 않고 계속해서 서비스를 누릴 수 있는 구독 서비스를 선택했습니다. 선택한 이유로는 택시 같은 교통 수단을 구매할 때마다 매번 결제했던 것이 불편했기 때문에 이를 없앤 서비스로 구독 서비스가 좋다 판단했습니다. 메인 홈페이지에서는 position: sticky와 background-attachment: fixed를 이용해 스크롤을 하면 화면이 자동으로 움직이는 것이 자율 주행 자동차를 떠올릴 수 있도록 구현했습니다. 소개 페이지에서 서비스 소개는 flex-wrap: wrap으로 서비스 설명에 대한 것을 한눈에 볼 수 있도록 설정 후 hover할 때 filter: invert(1)를 하는 것으로 해당 요소가 궁금할 시 더 자세히 볼 수 있도록 했습니다. 게시판은 제목이 적힌 div 클릭 시 내용이 담긴 div가 block으로 되는 기능을 구현했습니다.


어려웠던 점

역시 게시판이 가장 어려웠습니다. 제목이 있는 div를 클릭 시 아래에 none이었던 div가 block으로 바뀌는 것이 전부였지만 그 요소가 3개 이상 늘어났을 경우에 내용 div가 block이 되지 않는 버그, 원래 위치 그대로 있는 제목 div, 내용 div위치가 이상해지는 버그 등이 나타나 참 곤란했습니다. 때문에 div의 포지션이 absolute, relative였기 때문에 아래 새로 생기는 형제 요소가 움직이도록 조건을 걸었습니다. 그러나 전부 block 상태에서는 여러 버그가 일어났기에 내용 div가 block인 상태라면 다른 제목이 있는 div를 클릭 시 전에 block이 되었던 내용 div를 none으로 하고 새로 클릭한 요소의 내용 div block 상태로 하는 JS 코드를 작성했습니다.


배운점

 클래스명의 중복으로 CSS에서 문제가 생기고 팀원들이 만들었던 페이지를 합치니 하나의 홈페이지라는 느낌이 없었습니다. 때문에 일관성 지키기 위해 클래스명, 아이디명, 파일명 등에 대한 규칙을 자세하게 회의를 할 필요가 있는 것을 배웠습니다. 이번에 배운 것을 개인적인 프로젝트를 적용해보고 다음 팀 프로젝트 때 일관성 문제가 일어나지 않게 할 것입니다.

