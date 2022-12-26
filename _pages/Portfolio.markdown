---
title: "Portfolio"
permalink: /portfolio/
sitemap: true
---

## WATANK
### 2021.09-2021.12
Team Project  
Team member: 4  
role: Frontend, Project Managing  
Github Link: <https://github.com/Tikoring/watank>  
![play1](../assets/images/WATANK/play_image1.JPG "play_image1"){: width="49%" height="50%"}
![play2](../assets/images/WATANK/play_image2.JPG "play_image2"){: width="49%" height="50%"}  
  
### Tech Stack
**Frontend**
* C#
* Unity(2020.3.18f1) 
 
**Backend**
* photon
  
### Description
2D 포격 슈팅 게임  
Unity Engine을 학습하는 수업에서 모여 진행항 프로젝트입니다.  
기존 게임 중 포트리스를 벤치마킹해서 만들었고, 다 대 다 멀티 플레이를 고려해서 만들었습니다.  
현재는 프로토타입으로 탄과 캐릭터만 동기화 되어 있습니다.  

### Implementation
* Unity Engine 자체 패키지를 활용해 키보드 입력과 지형에 따른 오브젝트 제어(Frontend, 본인외 1명)
* 카메라 움직임 제어 및 포탄 움직임에 따른 카메라 트래킹(Frontend)
* 포탄과 지형 지물간의 상호작용(Frontend)
* Abstract Class를 이용한 특수 스킬 구현(Frontend, 본인)
* Photon을 이용한 플레이어 간 연결 구축(Backend)
* 탄환과 플레이어블 캐릭터 동기화(Backend)

### Dev Process
* git 내에서 backend와 frontend간 branch를 나눠 결과물을 merge하는 방식 이용
 * backend 및 frontend간 개발 영역 분리를 위해 각각의 branch 분리
* 주간 회의로 주간 일정 수립 및 전체 일정 조정
* P0, P1, P2로 구현 순서 정립
* 주간에 발생한 버그에 대한 픽스를 회의 당일 해결하는 방법으로 처리

### Activity
* 게임 기획 및 애셋 결정
* Flow Chart 구성
* Frontend에서 사용자 입력에 따른 오브젝트 제어
* 각 오브젝트의 애셋 적용에 발생하는 문제 해결
* 불필요한 변수 제거 및 중복되는 변수 통합

### Learned
* 협업을 위한 Github PR, Merge 등을 학습할 수 있엇습니다.
* Unity Engine에서 물리법칙이 적용되는 방식과 사용자 입력에 대한 처리 방법을 알 수 있었습니다.
* 명확한 기획의 필요성과 설계의 필요성에 대해 인지할 수 있었습니다.
* Class Diagram 등의 부재로 클래스와 변수가 무분별하게 생성됨 => 다른 사람의 코드를 분석해서 통합 여부를 판단해야 하기 때문에 불필요한 시간 소모가 많았습니다.
* 기능 추가에 따른 확장성을 고려하지 않아 추가할 때, 새롭게 코드를 작성했어야 하는 문제 발생했습니다.
* Frontend와 Backend간 완전히 독립된 개발은 통합 시 문제를 야기할 수 있다는 것을 알게 되었습니다.(상호 이해가 필요)
* 개발 영역이 너무 많이 소분해서 캡슐화에 실패한 부분이 존재 => 각 영역의 경계를 사전에 정립하는 것이 좋을 것이라고 생각이 들었습니다.

<br/>
<br/>

## 너만오면고(캡스톤 프로젝트)
### 2022.04-2022.05
Team Project  
Team member: 2  
role: Frontend, Project Managing  
Github Link: <https://github.com/Tikoring/capstone-2022-02>  
![index](../assets/images/Capstone/Index.jpg "index"){: width="49%" height="50%"}
![main](../assets/images/Capstone/Main.jpg "main"){: width="49%" height="50%"}  
  
![map](../assets/images/Capstone/Map.jpg "map"){: width="49%" height="50%"}
![chat](../assets/images/Capstone/Chat.jpg "chat"){: width="49%" height="50%"}
  
### Tech Stack
**Frontend**
* Flutter  

**Backend**
* Dart
* Firebase
  
### Description
스포츠 파티 매칭 서비스  
국민대학교 2022 capstone design에 출품한 팀 프로젝트입니다.  
코로나가 끝나면서 외부 활동이 늘어나는 것에 주목해 새롭게 운동을 시작하는 사람, 운동을 배우려고 하는사람, 같이 운동할 사람을 찾는 경우 등 이러한 대상들에게 편의를 제공하고자 서비스를 기획하였습니다.
서비스의 목표는 사용자의 인근에서 진행될 운동 파티를 보이거나, 사용자가 직접 운동 파티를 모집하는 형태로 사용자 간의 교류를 활성화하는 것입니다.

### Implementation
* Flutter와 Dart를 이용한 IOS/Android 화면 구성(Frontend, 본인)
* NaverMap API를 이용한 사용자 인근의 파티 목록 시각화(Frontend, 본인)
* Firebase API를 이용한 사용자 데이터 저장 및 파티 정보 저장(Backend)
* Firebase API를 이용한 사용자간 채팅 구현(Backend, Frontend)
* VWORLD를 이용한 주소 <=> 위, 경도의 변환과 주소 검색 구현(Backend)

### Dev Process
* frontend와 backend의 개발 분리 및 PR을 이용한 통합
* 주간 회의로 주단위 목표 설정 및 진행도 확인
* 작성한 QA 리스트를 기반으로 주간 회의에서 성취도 분석

### Activity
* 주간 성취도 분석 및 진행도 확인
* 주단위 목표 설정
* UI/UX를 고려한 화면 구성

### Learned
* Git을 이용한 버전관리 숙달 및 Readme 구성을 하였습니다.
* 기존에 존재하는 API를 활용한 개발에 응용해보는 기회가 되었습니다.
* QA를 고려해서 개발할 때, 처음부터 고려하는 것이 아니라 중간에 추가하는 경우에는 기존에 완성된 구현을 새로 실시해야하는 부분이 있어서 초기 설계 단계의 중요성을 다시금 알수 있었습니다.
* Frontend와 Backend 연결 시의 문제를 최소화 하기 위해서 더미 데이터를 활용하는 방식을 이해하였습니다.
* 개발 중간에 웹에서 모바일로 타겟 환경이 변경된 것 때문에 기간 내에 완전한 서비스를 지원하는 프로젝트를 완성하지 못한 것이 아쉽습니다.
* 여전히 기획 단계에서의 명세 부족으로 인한 기능 구현이 복잡해지는 부분이 나타났습니다.