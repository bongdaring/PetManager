**반려동물 관리 어플 (팀프로젝트)**

**제 1 장 설계과제 개요**

**제 1 절 과제 목표**

최근에 반려동물을 키우는 가정이 늘어나고 있으며, 현재 반려동물을 키우는
가정이 국내 전체 가계의 29.7%에 달하는 수준이다. 반려동물과 함께
오랫동안 살아가기 위해서 사람들이 많은 주의를 기울여야 한다. 반려동물과
함께 하는 데에 점검해야 할 요소들을 정리하고 해야 할 일을 수행해야 한다.
사람들은 반려동물에게 피해가 가지 않도록 큰 노력을 기울이지만 미처
기억하지 못하는 것들이 있을 수 있다. 우리는 이러한 어려움을 해결하기
위해 반려동물에게 필요한 요소들을 정리하고 하나의 애플리케이션에
통합하여 제공하려고 한다. 이러한 요소들뿐만 아니라 다양한 종과 생활
방식을 가진 반려동물들에게 모두 적용할 수 있도록 하여 사용자에게
편리함을 제공하는 것을 목표로 한다.

**제 2 절 과제 내용**

**1. 과제 필요성**

우리가 반려동물과 함께 살아가기 위해서는 많은 시간과 관심을 쏟아야 한다.
반려동물들은 사람이 챙겨주지 않으면 스스로 할 수가 없고 사람에게 표현도
할 수 없기 때문에 사람이 꼼꼼하게 관리해주는 것이 필요하다. 사람이
본인의 스케줄을 관리하기 위해서 스케줄러를 작성하거나 관리 어플을
사용하는 것처럼 반려동물도 이러한 것을 사용할 수 있다면 많은 일정을
관리하기 편할 것이다. 강아지를 산책을 시킨 지 얼마나 지났는지 혹은
먹여야 할 약이 있는지나 약을 먹였는지 등 다양한 일들을 관리하기 위해
기록을 사용하면 편리하게 관리할 수 있다. 이러한 기록을 지원하기 위해서
반려 동물 일정 관리 어플을 개발하기로 했다.

**2. 현실적 제한 요소**

강아지나 고양이가 주된 반려동물이기는 하지만 다양한 종류의 반려동물이
존재하며 모든 동물을 대상으로 제작하기에는 한계가 있다. 또한, 강아지와
고양이도 다양한 종류가 있기 때문에 모든 종을 고려하기가 어렵다.

**3. 과제 내용**

반려동물 프로필을 등록하고, 반려동물의 산책 동선, 사용자 위치 기반 근처
동물병원 검색, 투약 시간 알림 기능을 제공한다. 반려동물의 사진을
등록하여 일기 형식으로 관리할 수도 있다.

**1) 프로필 관리**

반려동물의 프로필을 등록할 수 있도록 한다. 반려동물의 사진을 등록하고,
이름, 나이, 종 등을 입력한다. 질병 여부나 수술 여부 등 각종 특이사항을
등록할 수 있도록 한다. 추가적인 특이사항을 입력할 수 있도록 구분이
정해지지 않은 내용도 기록할 수 있는 칸을 제공한다.

**2) 산책 동선**

산책이 필요한 반려동물의 경우 산책 동선을 관리할 수 있도록 한다.
사용자의 위치를 기반으로 하여 출발점을 자동으로 지정하고 사용자가
도착점을 지정하여, 사용자가 이동할 때마다 거리를 자동으로 계산해준다.

**3) 동물병원 검색**

사용자 근처의 동물병원 위치를 검색한다. 사용자의 위치를 자동으로
받아와서 지정된 반경 내에 위치하는 동물병원을 지도에 표시한다..

**4) 투약 여부**

반려동물이 투약해야 할 약이 있는지를 관리한다. 약이 있다면 먹어야 할
시간대마다 알림을 제공한다.

5\) 사진 등록 및 일기 관리

반려동물과 함께하는 일정을 기록하기 위해 사진 등록 및 일기장 기능을
제공한다. 날짜를 따로 지정하지 않는다면 오늘 날짜로 사진을 등록하여
다음에 사용자가 원하는 날짜의 사진을 쉽게 찾을 수 있도록 한다. 동시에
일기 작성 기능을 제공하여 반려동물과 함께한 특별한 날들의 기록을
편리하게 한다.

**4. 과제 수행 방법**

  개발언어        JAVA, PHP   
  --------------- ----------- ----------------
  개발 O/S        Android     
  개발 프로그램   앱 개발     Android Studio
                  DB 관리     Mysql, Sqlite

**1) 프로필 관리**

메인 화면에서 데이터베이스에 등록된 반려동물의 목록을 표시한다. 반려동물
프로필 편집 화면에서 반려동물의 이름, 종, 사진 등 각종 정보를 입력하고
데이터베이스에 저장한다. 등록된 반려동물의 프로필은 마찬가지로 편집
화면에서 확인할 수 있으며, 내용을 수정한 후 수정 버튼을 통해 반려동물의
프로필 내용을 수정하거나 삭제 버튼을 통해 프로필을 삭제할 수 있다.

**2) 산책 일정**

자신의 위치에 마커가 생성이 되고 원하는 산책 도착지를 길게누르면 그
도착지의 대한 설명을 작성할 수 있다. 도착지의 이른과 설명을 작성한 뒤
출발 버튼을 누르면 현재 위치와 도착 위치의 사이가 좁아질 때 마다 몇 m가
남았는지 Toast 메시지로 표시해준다.

반려동물의 산책 코스를 짜기 위해서 구글맵을 사용했다. 구글맵을 사용할 수
있는 Api 키를 받아 프로그램 안에서 지도를 사용할 수 있도록 했다.
구글맵을 사용할 때는 구글플레이 스토어 계정이 필요하다.

Api 키를 발급받기 위해서는 사용자 인증 정보를 만들어야 하는데 구글 맵을
사용할 패키지 이름과 SHA-1 인증서 디지털 지문을 입력해야하고 그렇게 발급
받은 키를 코드에 넣어주면 된다.

**3) 동물병원 검색**

근처 병원 위치나 정보를 제공하기 위해 구글맵을 이용하여 동물병원에 대한
정보가 기록되어 있는 데이터베이스를 가져와서 화면에 보여준다. 산책과
마찬가지로 구글 맵 Api 키를 받아와서 구글 맵을 사용할 수 있도록 한다.

퍼미션 코드로 자신의 위치 정보 제공을 허용하여 사용자위 위치를 자동으로
지정한다. 지도에 마커로 현재 위치를 표시한 후 동물병원 검색 버튼을
클릭하면 주변 1km 내에 있는 동물병원을 검색하여 마커로 표시해준다.
마커를 클릭해보면 동물병원의 이름과 상세주소를 확인할 수 있다.

위 산책 일정과 같이 퍼미션 허용이 된 상태에서 동물병원 위치를 찾기 위해
place api 키을 발급받는다. 이 api를 사용하기 위해서는 build.gradle
파일에서 minSdkVersion를 15 이상으로 사용해야 한다.

**4) 투약 여부**

사용자가 지정한 시간에 알림 기능을 사용하여 투약 시간에 알림을
제공하도록 한다. 프로그램을 닫아도 백그라운드에서 실행되어 프로그램을
사용하지 않고 다른 일을 하고 있어도 알람이 제때 울리도록 한다. 알림을
끄고 투약했다는 버튼을 누르면 오늘 일기에 투약했다는 기록이 남을 수
있도록 하여 투약 여부를 확인할 수 있도록 한다.

**5) 사진 등록 및 일기 관리**

선택한 반려동물의 일기를 작성할 수 있도록 한다. CalendarView를 사용하여
날짜를 선택하고 제목, 내용, 사진을 등록한다. 등록된 일기의 목록을
제공하고, 목록을 클릭하면 일기의 세부 내용을 확인할 수 있도록 한다.

**제 2 장 기대효과 및 활용 방안**

**제 1 절 창의성 측면**

현재 반려동물과 함께 하는 사람들이 증가하고 있으므로 그런 사람들에게
편의성을 제공하기 위한 애플리케이션을 개발하는 것이 목적이다. 사람이
사용하는 플래너나 스케줄러에서 구성을 착안하여 기본적인 틀을 구성한다.
더 나아가 세부적인 내용은 반려동물의 종이나 생활 방식에 맞게 재구성하여
반려동물의 일정을 관리하는데 편리하도록 한다.

**제 2 절 기술적 측면**

반려동물의 하루 루틴에 맞게 애플리케이션에서 알람을 제공한다. 또한, 여러
개의 사이트로 각각 떨어져 있는 기능들을 하나의 애플리케이션으로 통합할
수 있다. 기존의 경우 사람이 반려동물에 대한 각각의 요소를 따로
관리하여야 했는데 이 프로그램을 사용할 경우 비교적 적은 시간과 노력으로
각종 기록 및 일정을 관리할 수 있다. 반려동물을 위한 물품을 구매하고,
가까운 동물병원의 위치를 사용자가 직접 찾지 않아도 애플리케이션 내에서
제공하는 등 다양한 기능의 제공으로 반려동물을 보다 효과적으로 보살필 수
있다. 반려동물을 위해 다른 부분에 쏟았던 시간을 애플리케이션의 사용을
통해 반려동물과 함께 시간을 보내거나 자신의 개인적 혹은 경제적 활동에
활용할 수 있다.

**제 3 절 경제․산업적 측면**

현재 반려동물에 대한 정보들의 공유가 대부분 반려동물 커뮤니티에서
이루어진다. 커뮤니티도 여러 곳으로 구분되어 있기 때문에 이를 통합하고
관리하는 것이 필요하다. 통합이 잘 이루어진다면 커뮤니티 사용자들을
애플리케이션 이용자로 확보할 수 있으며, 이용자들이 가진 정보를 통한
애플리케이션의 확장 또한 가능하다.

**제 4 절 활용 방안**

이 프로그램은 반려동물과 함께 사는 사람들이 시간적 여유를 가지고
반려동물을 보살필 수 있도록 도움을 주는 프로그램이다. 프로그램의 다양한
기능으로 반려동물의 일정과 상태를 더욱 쉽고 체계적으로 관리할 수 있다.
사용자가 일정을 잊게 되더라도 해당 프로그램의 사용을 통해 반려동물에
대한 모든 것을 놓치지 않도록 도와주며, 이 프로그램이 반려동물과 함께
살아가는 사회에서 높은 활용도를 보일 것이다.

**제 5 절 발전 계획**

현재 이 프로그램은 안드로이드 스튜디오에서 제공하는 기본 UI를 사용하고
있다. 이 UI는 항목 간의 구분이 불명확하고 클릭이 가능한 부분과 그렇지
않은 부분이 두드러지게 나타나지 않기 때문에, 사용자가 한눈에 알아보기
쉽고 프로그램의 주제와 맞는 UI로 변경할 계획을 가지고 있다. 또한, 일기의
검색 기능이 구현되어 있지 않은데, 데이터베이스 접근과 처리가 쉬운 날짜를
기준으로 하여 사용자가 원하는 날짜의 일기를 찾을 수 있도록 하는 기능을
추가할 계획이다.

**내가 맡은 개발**

투약 시간과 산책 일정, 동물병원 찾기 부분을 개발했습니다.
