# Intro
> Unity 게임 개발자를 지향하는 프로그래머 구태용입니다   
> 게임 제작 팀프로젝트의 팀장 경험을 통해 디자인 작업의 시간 조율 및 기획자와의 조율등 각 직책 마다의 작업을 이해하며   
> 프로젝트 개발을 통해 만족할만한 최선의 결과를 내는데 노력하고 있습니다   

# Skill
> Engine
<pre><code>- Unity 2018 ~ Unity 6</code></pre>
> Programming Language
<pre><code>- C#
- C++
- JavaScript</code></pre>
> Support tool
<pre><code>- Slack, Discord
- Notion
- Github</code></pre>

# Awards & Activities
|수상&활동명|내용|기관명|
|------|---|---|
|경기 콘텐츠 진흥원장상(대상)|경기 메타버스 해커톤 개발 팀장|경기 콘텐츠 진흥원|
|경기 지역발전 리빙랩 수상(은상)|경기도 지역발전 리빙랩 공모전 프로그램 팀장|대학 산업협력|
|PlayX4 B2B|Ordeal of Spire게임 제작 및 프리플레이|---|


# Project
## Team Project
### 1. < Ordeal of Spire - Leader/Programmer(14) >
> **2025 PlayX4**에 참여한 PC게임으로 제작된 로그라이트의 14인 팀 프로젝트 입니다 (기획2, 프로그래머1, 아트11)   

https://github.com/user-attachments/assets/68379acd-2334-4b69-bf66-6c5cb77ebc83

<pre><code>- 개발기간: 2024.1 ~ 2024.11 / 2025.4 ~ 2025.5 (기획 3개월, 프로토타입 2개월, 아트포함 개발6개월, 보스개발 2개월)
- 사용엔진: Unity 2022.3.22f1 LTS (Dev), Spine 4.2 (Ani)
- 서포트툴: Discord, Github, Photoshop
- 설계한 시스템: 전투(공격, 피격, 콤보, 스킬) 및 이동, 디버프, 맵 및 몬스터 랜덤 생성, 보스 패턴, 라운드 전환, 체력 및 스테미너, 인터페이스(대화, 상태창) 등등
- 에셋 및 리소스: 자체 제작</code></pre>
**[해당 작업의 상세 작업 내용은 해당 프로젝트 페이지에서 확인 가능합니다](https://github.com/ekarose0/Ordeal-of-Spire_Portfolio)**
> 위 프로젝트는 총괄 팀장이자 단일 프로그래머로 초기 기획부터 보스제작까지 담당하였으며, Unity 2022.3.22f1로 제작하였습니다

#### 1-1.소개
|게임 이미지1|게임 이미지2|게임 이미지3|
|:-----:|:-----:|:-----:|
|<img width="300" height="168.75" alt="image" src="https://github.com/user-attachments/assets/5302391f-1431-472b-9c15-2d237a8983d2" />|<img width="300" height="168.75" alt="image" src="https://github.com/user-attachments/assets/2270b53a-da85-4b97-a441-c74437dae39f" />|<img width="300" height="168.75" alt="image" src="https://github.com/user-attachments/assets/a402b13d-efd6-4c80-9f8f-3babd93fa2a4" />|

#### 1-2. 메인 사용 기술
|기술|설명|
|:------:|:--------------------------|
|디자인 패턴|**싱글톤** 패턴을 사용하여 데이터 구조 관리<br>**Manager** 스크립트를 통한 하위 스크립트 관리<br>**Define**을 통한 정의 관리|
|Scriptable Object|Scriptable Object를 통한 빠른 DB관리(캐릭터, 몬스터, 맵) 및 설정|
|Save|Json을 통한 정보 저장/불러오기|
|Pool|소환되는 오브젝트는 Pool을 통한 접근 및 저장|

#### 1-3. Inspector 커스텀
|관련 이미지| 작성 스크립트|
|:-----:|:------:|
|<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/88a1d772-1044-48f6-8d41-83a70c14a802" />|<img width="798" height="500" alt="image" src="https://github.com/user-attachments/assets/52cf784e-4222-45e0-802e-7d4bd75f84e4" />|
|<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/f3ee5e69-6baf-4fc1-82fb-1b9b18d82088" />|<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/573dd6fc-9847-43b1-8283-eb3a170900ef" />|

<pre><code>개발자 외의 타 개발군에서 해당 프로젝트에 쉬운 접근성과 가시성을 표시하는걸 목적으로 제작하여 개발기간을 줄이는 목적으로 제작하였습니다.
버튼을 통한 기능추가 및 이미지와 프리팹등 다양한 설정값을 설정하여 이를 바탕으로 실제 게임에 적용됩니다. 
DB를 Scriptable Object를 사용하여 인게임 내에서 쉽게 관리하고 리소스를 쉽게 관리 하기위해 작성되었습니다.</code></pre>

#### 1-4. 오브젝트 풀 관리

|오브젝트 이미지|관리 스크립트|
|:-----:|:-----:|
|<img height="500" alt="image" src="https://github.com/user-attachments/assets/6da8c08f-dce7-47ea-8616-8dc815ff49c1" />|<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/40bca22f-c412-492b-864b-2e625526743d" />|
|<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/6be637a1-a157-4b00-a116-49ad9ce74471" />|<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/3bc9b971-6d53-4fb9-b6fb-81faea0cea94" />|

<pre><code>Object들을 Pool을 통해 관리하며, 각 객체에 접근하는 것이 가능합니다.
또한, 각 오브젝트를 소환하는 메서드는 GameManager의 Pool로 접근하여 자식으로 소환하고 관리합니다</code></pre>

### 2. < Defense Card - Leader/Programmer(3) > 
> PC게임으로 제작된 카드게임의 3인 팀 프로젝트입니다 (기획1, 프로그래머2)

https://github.com/user-attachments/assets/54825c2c-154e-4b06-9e95-ced1aaadd6de   

<pre><code>- 개발기간: 2024.9 ~ 2024.12 (4개월)
- 사용엔진: Unity 6000.0.25f1 LTS (Dev)
- 서포트툴: Discord, Github, notion
- 설계한 시스템: DB관리, 카드 족보, 변경 연출, UI
- 목표: 프로그래머끼리의 협동 </code></pre>
> 해당 프로젝트는 팀장으로 기획을 통해 나온 내역을 다른 프로그래머와 협업하는데 중점을 맞추었으며, 유니티6를 사용하는데 의의를 두었습니다. 

### 3. < KMU_Leaving Lab - Programmer(3) >
> 모바일로 제작된 AR 네비게이션의 3인 프로젝트입니다 (기획2, 프로그래머1)

## Single Project

## Game Modding

### 1. <Marisa! ReturnTheBook KR Trans>
> 마리사! 책 돌려줘! 게임의 Harmony 기반 한글 모드입니다 #[링크](https://github.com/ekarose0/MarisaReturnTheBook_TranslateKR)

### 2. < Eldenring >
> NEXUS Seamless Co-op 한국어 담당 (EKa001) #[링크](https://www.nexusmods.com/eldenring/mods/510 "파일 스크립트 내 기여자 기제")

> NEXUS Tranksmogrify 한국어 담당 (EKa001) #[링크](https://www.nexusmods.com/eldenring/mods/3596 "페이지 기여자 기제")

### 3. < Atelier Lyza2 PS Button mod >
> 아틀리에 라이자2 게임의 UI 변경 모드입니다 #[링크](https://github.com/ekarose0/Atelier-Ryza2-PS4-Switch-Button-Replacement)

### 4. < Thaumcraft 4 Translate >
> 마인크래프트의 Thaumcraft4의 한국어 번역(에드온포함) 모드입니다 #[링크](https://github.com/ekarose0/Thaumcraft4-TC4_Addon-Korean-Translate)


# Youtube
 [![Video Label](http://img.youtube.com/vi/6ebRzNvSmD4/0.jpg)](https://youtu.be/6ebRzNvSmD4)   
더보기: #[링크](https://www.youtube.com/@E_Ka01)
