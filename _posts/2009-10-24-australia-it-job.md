---
title: 호주 IT 직장 문화
layout: post
---
<div id="toc"><b><span style="font-size: large;">차례</span></b></br></div>
<img src="http://w12ard.github.io/wp-content/uploads/1/cfile6.uf.14474D0C4AE2CDE5488CD0.jpg" width="470" height="313" alt="" filename="cfile6.uf.14474D0C4AE2CDE5488CD0.jpg" filemime="" />
  
어느덧 지금의 호주 직장에 다니기 시작한지 3달을 다 채워가고 있다. 회사도 나도 Permanent 로 재계약하자는데 동의했고, Contractor 로 있었던 3달을 Probation 기간이었던 셈 치기로 했으니 이제야 맘놓고 좀 게을러질 수 있을 듯 하다. ㅎㅎㅎ 기념으로 그동안 느낀 한국 직장과의 차이점을 정리해봤다. 주의. 아직 온지 얼마 안돼 시야가 좁으니 감안하자. 

### 프로젝트 일정 관리 ###

관리자가 일방적으로 개발 일정을 정해주기 보다는 해당 모듈 담당 개발자에게 얼마나 걸릴지 물어본다. 자신만의 개발 일정 관리에 익숙치 않았던 나는 조엘 스폴스키의 <a title="[http://www.joelonsoftware.com/articles/fog0000000245.html]로 이동합니다." target="_blank" href="http://www.joelonsoftware.com/articles/fog0000000245.html">Painless Software Schedule</a> 부터 다시 읽어봐야 했다.

하지만 일정이란게 아무리 잘 짜더라도 어긋나기 쉽다. 때론 계산했던 것보다 더 많은 시간이 투자되어야 할 때도 있고, 개발자적 욕심?때문에 무리하다 일정을 늦추게 되는 수도 있다. 이 때 야근을 안하려면 원래 정한 일정을 늘려달라고 해야 한다. 그래서 결국 커뮤니케이션이 중요하다. 예를 들어 보겠다. 

프로젝트 진행중 원래 계산에는 없었던 schema validation 처리부를 개발할 필요가 생겼다. 선택할 수 있는 옵션은 대략 3가지였다. 각각의 장단점과 개발 시간을 산정해 보여줬다. 첫째 방법은 30분, 둘째 방법은 반나절, 셋째 방법은 2일이 걸린다. 물론 개발 기간이 길수록 넣을 수 있는 기능은 많아지고, 내 욕심?상 셋째 방법을 선택하고 싶다. 관리자는 내 설명을 듣고 이번 릴리즈엔 셋째 방법까진 필요없고 둘째 방법이면 충분하겠다고 얘기했고 나도 동의했다. 결국 난 반나절을 더 벌고, 해당 기능만큼만 구현해 넣었다.&nbsp; 

그래도 일을 하다보면 다른 일에 방해받아 원래 일 처리를 못하게 되는 수도 있다. 매 주 개발팀 회의때 각자 지난주 한일과 앞으로 한주간의 계획을 얘기하는데 이 때 다른 뭔가에 바빠 원래 일처리는 못했다고 얼굴에 철판깔고 변명하는 동료도 심심찮게 본다. 실은 한 명이 요즘 계속 그런다. 그럼 난 한마디 한다. 한국같으면 너같은건 벌써 짤렸어!(속으로)

### 업무 영역 ###

호주 떠나오기전 미국인 친구랑 한국에서 식당에 갔는데 여종업원을 도와 쟁반에서 같이 음식을 내려놓는 날 보더니 호주가선 그러지 말란다. 이유는 엄연히 그건 종업원이 할 일이기 때문이란다. 오히려 기분 나빠할수 있다나? 

당시엔 별로 와닿지 않았던 문화적 차이. 하지만 지금은 가장 크게 느끼는 차이라고 할 수 있는데 얘들은 업무 영역을 굉장히 중요시한다. 내가 하면 금방할 수 있는 것도 그 일 담당자가 따로 있다면 메일을 보내 해결해달라고 요청하는 게 순서다. 미리 양해를 구하고 해결하는 건 괜찮다. 나같으면 누가 내 대신 뭘 알아서 처리해주면 고마워 할텐데 얘들은 그렇지 않다. 설령 잘못된 게 눈에 보여도 직접 고쳐주는 일은 금물.

### 문서화 ###

한국에서 개발시 문서 작성은 그다지 많지 않았다. PT를 만든다던가 하는건 주로 전담자가 따로 있었다. PM이나 컨설턴트가 보통 했다. 여기선 아주 조그마한 변경 사항만 있어도 다 절차를 거쳐 반영하고 릴리즈 노트를 만들어 모든 기록을 남긴다. 할 땐 귀찮은데 일단 만들어 두면 유지 보수하기 쉽다. 그렇다고 필요도 없는데 형식적으로 만들어본 문서는 아직 없다. 

### 각각 분리된 환경 ###

사용하는 기술 특성상 한국에서도 주로 대기업 프로젝트를 많이 했지만 한 번도 여기처럼 철저하게 각각의 환경을 분리해 놓은 걸 본 적이 없다. 당장 내일이 시스템 오픈인데 밤샘하면서 새 기능 추가하고, 디버깅하고, 물론 운영 서버에 올리는 것도 직접 했다. 서버 어드민 권한은 물론이고, 도메인 어드민 그룹에도 들어가 있었다. 일을 그런 식으로 했으니 결과가 항상 좋았을리는 없지만 뭐 어쨌든 팀원 각자가 어마어마하게 많은 일을 처리하곤 했다. 이러니 한국의 개발자는 수퍼맨이 될 수 밖에 없다.

여기선 Development, Integration, Test, Staging, Production 환경이 구분되어 있다. 개발자가 건드릴 수 있는 영역은 오직 개발 환경뿐이다. 그러니 개발자가 운영 서버에 뭔가 직접 올린다는 건 상상할 수 없고, 아무리 작은 모듈이라도 배포 패키지와 릴리즈 노트를 만들어 다음 환경 담당자에게 전달한다. 그럼 그 담당자가 설치, 운영 테스트한 후 문제가 있으면 피드백 주고, 없으면 다음 환경 담당자에게 넘긴다. 이러니 운영 서버에 올리기 몇 일전에 새 기능을 추가해 넣는다던가 하는 일은 있을 수 없다. 왜냐하면 다시 테스트 해야 하거든. 새 기능은 다음 릴리즈로 미룬다. 결국 개발자의 부담이 적다. 업무 영역이 구별되어야 하는 이유가 슬슬 이해 된다. 

그렇다보니 뭔가 새로 만든걸 운영 환경에 적용하기 까지 시간이 오래 걸린다. 참고로 내가 처음 이 회사 와서 개발했던 어플리케이션은 3달이 다 되어가는 지금까지도 운영에 배포되지 않았다. 여전히 꼼꼼히 테스트하고, 피드백 받는 중이다. 

### 퇴근 시간 ###

한국에 있을 때 가장 짜증났던 건 야근 자체가 아니라, 야근을 하느냐 안하느냐가 마치 좋은 직업인 척도인양 비교 당하는 것이었다. 야근을 하든, 안하든 프로그래머란 직업 자체를 아주 자랑스럽게 생각하는 내겐 이게 항상 거슬렸다. 여기선 직업이 뭐든 업무 끝나면 집에 가는 게 당연하다. 촌스럽게 짤퇴근 한다고 자랑 하는 사람이 없어 좋다. ㅎㅎ 실제 5년차부터 야근은 거의 하지 않았던 내게 단지 &#8216;프로그래머라는 이유로&#8217; 퇴근은 몇 시에 하냐고 인사처럼 묻는 이들이 있었다. 마치 &#8216;밥은 먹고 다니냐?&#8217;는 말처럼 들렸다. 

가끔 좀 늦게까지 남아 하던 일 끝내고 싶은 적도 있는데 여기선 회사 주변 식당들도 5시면 다 문을 닫기 때문에 저녁을 굶어야 한다. 거기다 출퇴근 시간에 3-5분마다 다니는 집-회사 버스가 6시부터는 현저히 적어지다가 7시쯤 되면 3-40분씩 기다려야 하는 일이 벌어진다. 그냥 집에 가는 게 속편하다. 

### 연봉 및 세금 ###

한국있을 때 비해 표면적인 액수는 몇 배 많아졌는데 저축률은 그다지 높지 않다. 시드니의 렌트비는 장난이 아니다. 만약 돈을 많이 모으기 위해 오시려는 분이 있다면 사업을 하시라고 말씀드리고 싶다. 세금은 전에 올린 <a title="[http://ahkim.com/entry/%ED%98%B8%EC%A3%BC-%EA%B3%BC%EC%84%B8-%EA%B8%B0%EC%A4%80%ED%91%9C]로 이동합니다." target="_self" href="http://ahkim.com/entry/%ED%98%B8%EC%A3%BC-%EA%B3%BC%EC%84%B8-%EA%B8%B0%EC%A4%80%ED%91%9C">과세 기준표</a>대로 적용 받았다. 역시 직장인은 유리 지갑이다. 탈세란 걸 할 수가 없다. 

### 할아버지 개발자 ###

개발팀의 평균 연령대는 40대다. 이건 50대 할아버지 개발자들이 평균을 높이기 때문인데 한국에서 온지 얼마 안된 내가 보기엔 참 신기하다. 한국에서 이 정도 나이대 개발자를 보는 건 그닥 흔치 않다. 개발팀 회의 때 보면 풍경이 재미있다. IT 개발팀 관리자는 나랑 동갑인 30대 초반 여자다. 반면 개발팀원들 다수는 백발이 성성하다. ㅋㅋㅋ 

그러다보니 좀 심심하다. 어린 것들이 있어야 좀 수다도 떨고 재미있는 법인데 할아버지들이라 5시면 바로 일어서고, 술 마시잔 얘기도 없고&#8230; 매주 금요일 사무실 한켠에서 조그마한 맥주, 와인 파티가 벌어지는 데 비즈니스 부서 사람들이 주로 간다. 

### 인종 차별 ###

이건 호주뿐 아니라 어느 영어권 나라라 해도 마찬가지일 듯 싶은데 워낙 인도인들이 많이 진출해 놔서 요즘의 IT 부서는 백인이 오히려 마이너리티다. 내가 다니는 회사역시 마찬가지. 비즈니스 부서는 거의 백인이 대세긴 하지만 적어도 IT 부서에서 인종 차별이란 있을 수 없다. 워낙 다국적 출신들이 많아 아직까지 차별을 당했다고 느껴본 적은 없다. 이 점이 꽤 중요하다. 어느 조직이 됐든 쪽수가 많아야 한다. 한국인 개발자들이 얼른 좀 더 많이 이 곳에 진출해서 적어도 IT 부서에서만큼은 절대 한국인을 무시할 수 없다는 분위기가 만들어졌으면 좋겠다. 여기서 접하는 인도인들이 내겐 그렇게 다가온다.

### 데스크탑 관리자 권한 ###

직원들이 자기 PC의 관리자 권한이 없다. 특히 비즈니스 부서는 절대 용납되지 않고, IT 의 경우에도 DB 팀은 관리자 권한이 없다. 아참, 회사 내 OS는 XP SP3 을 아직 쓴다. 내 경우도 처음에 관리자 권한을 안주려고 해서 매니져에게 왜 관리자 권한이 필요한지 사유를 적어 보내고 승인을 받아 시스템 어드민의 Grant를 얻어내야 했다. 닷넷 개발자다보니 디버깅 등을 핑계로 간신히 얻어냈다. 다른 직원들은 그래서 뭔가 설치해야 할 프로그램이 생길 때마다 시스템 어드민에게 대신 설치해달라고 그래야 한다. 실은 이거 때문에 얼굴 붉힐뻔 했다. 얼마나 황당하던지&#8230;-_-

### 일괄 처리 ###

호주에 와서 가장 황당했던 게 은행 시스템의 배치 처리였다. 한국에선 돈을 송금하면 바로 처리가 되서 온라인으로 확인이 가능했는데 여기선 하루는 지나야 확인 가능하다. 왜 그럴까? 일괄 처리하기 때문이다(NAB 가 그나마 실시간에 가까운 듯 하다). 내가 다니는 회사의 경우 주 고객 대상은 펀드 매니져, 투자 은행, 투자자다. 당연히 실시간으로 모든 거래가 이루어 져야 할 것 같지만 그렇지 않다. 예를 들어 주말에 Order 가 떨어지면 월요일 직원이 나와 처리할 때까지 보류다. 한국적 사고로는 고객은 항상 떠받들어야 할 존재지만 여기선 그냥 비즈니스 파트너로 바라보는 경향이 강하다(물론 여기서도 말로는 항상 고객을 중요시한다. 립서비스 확실히 해준다). 그렇다보니 일하긴 좀 편하다. 

&#8212; 

대충 생각나는대로 정리해봤다. 앞서 얘기했지만 워낙 제한적인 경험을 토대로 한 글이라 이것이 호주 IT 직장 문화라고 일반화 시키기엔 무리가 있다. 거기다 금융 서비스 회사다보니 지켜야 하는 각종 regulation 이 너무나 많다. 정리한 내용들 중 상당수가 이런 회사 특성 때문일 수 있다. 보안, QA 팀, 각 환경 분리, 소프트웨어 라이센스 등은 년중 몇 번 있는 감사(Auditing) 대상이라 특별히 철저하게 지킨다. 여기 걸리면 비즈니스를 할 수 없기 때문이다. 

그냥 참고만 하자. ^^
