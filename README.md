# README.md  

# 목차
Ch 1. 깃허브 파일
0 체크 및 주의사항
1 파일 정리 및 관리
2 마크다운  
  2.1 마크다운 적용  
  2.2 마크다운 실사용  
  2.3 마크다운 기본 문법  
  2.4 자주 쓰는 이모지    
3 레포지토리 분류 및 순서         
4 깃허브 코드 검색 인덱싱


A 레포지토리 라이센스     
B 기록 플랫폼  
Z Self Feedback    
 
References

-----

# Ch 1. 깃허브 파일
## 0 체크 및 주의사항
  - 커밋메시지 컨벤션(깃 시작 및 초기여도 기왕이면 따르려하기)

## 1 파일 정리 및 관리    
  - 업데이트 시점 의미 있는 경우 : 파일 위에 날짜나 버전 적어두기
    
## 2 마크다운
### 2.1 마크다운 적용  
  - **##1. & ###1.1 & (공백 2개_for txt)-+-**  
    ~<-> m) 번호항목만 : ( **띄어쓰기 4개 베이스 or 번호 항목 뒤에 띄어쓰기** / 탈출 : (빈줄) 후의 줄앞이 띄어쓰기 2개 이하 )~
    
  - 항목 : 두번 째 항목이니까 '+'사용 / ** 탈출 : (빈줄)**.  
(빈 줄 없으면 줄 시작에 띄어쓰기가 몇 개가 있던 결과는 위 항목 내의 위치임)
    + 항목
      - 항목
        >> ~굳이, 굳이, 궁금하다면 읽을 내용~
         
        ( 빈줄 ) _ 세로선 '>' 끝내기
        
        > ~굳이, 궁금하다면 읽을 내용~   
  
        ~읽을, 어느정도 중요한 내용~   
  - ~입력하는 내용 종류에 따라 더 맞는 폼이 다를 수 있어서 + 규칙은 좋게 바꿔나갈 거라, 모든 글에 동일하게 적용돼있지 않음~
    
  - 항상  
    + ( **엔터 전 띄어쓰기 두 번** : 복붙 _ 앞뒤 항목 아닌 걸로 가도 괜찮기 위하여)
    + 줄의 시작 부분의 공백[띄어쓰기] : 추가 4개(코드블록), 추가 2개&항목 기호(항목 생성)를 제외하고는 다 무시
  
  - 정보
    + -항목 전줄, >뒤줄(얘는 해제하려면 빈 줄 입력도 해야함) 줄간격 ㄱㅊ해짐  
    + ~~\~\~(공백X)글중단선\~\~~~ / _\_기울임\__
    + \ : 기호에 대한 기능 해제
  
### 2.2 마크다운 실사용  
- 사용법 (한국어) : https://gist.github.com/ihoneymon/652be052a0727ad59601  
- AI 분야 사람 예시  
  + https://github.com/skaurl
- 깃허브 포트폴리오, 깃허브 다양한 틀   
  > https://cucus.notion.site/Github-43b0293b3595488595a47a45d8741f25  
  + 참고할 만한    
    > https://github.com/changh95  
- 깃허브 공식
  + 퀵시작 https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github
  + 시작 https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github
  ![image](https://github.com/journeythrunrun/00-common/assets/164328543/a8fdb462-edb4-4cd9-8e95-0927f8a01cc0)
  
  ```  
  You can format text and include emoji, images, and GIFs in your profile README by using GitHub Flavored Markd own. For more information, see "Getting started with writing and formatting on GitHub." For a hands-on guide to customizing your profile README, see "Quickstart for writing on GitHub."

  # ex)
  An "About me" section that describes your work and interests Contributions you're proud of, and context about those contributions Guidance for getting help in communities where you're involved
  ```

  > https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme  
  > https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes  

### 2.3 마크다운 기본 문법
  - 사진
    
  - '#, ## 1.' : 자동 목차 선택도 가능  
  - 코드 블럭   
    + M1. 억음  부호  
      ```   
      ~~   
      ```   

    + M2. 빈줄+Tap / 띄어쓰기 네 번+빈줄  

  - 수평선  
    다 한줄 씩만 그어짐  
    
    ---------------------------------------  
    * * *  
    ***  
    *****  
    - - -  

  - 링크
    + M1. 파란줄 : <  >
    : <http://example.com/>
    + M2. 링크 주소대신 특정 글자로 보이는 방법 
    : ""는 마우스 대면 보이는 글씨
    [Google](https://google.com, "google link")
    + M3.
    [Google][googlelink]
  
    [googlelink]: https://google.com "Go google"
  
  - 이미지[사진]
    + New issue에서 링크 가져오기 [https://velog.io/@www_1216/github-issue%EB%A1%9C-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%B2%A8%EB%B6%80%ED%95%98%EA%B8%B0]
    + ![Alt text](/path/to/img.jpg) [https://gist.github.com/ihoneymon/652be052a0727ad59601]

  - Pass
    + 일반텍스트 끝나고 (빈줄) 만들기      
    + 줄바꿈_다음이 항목줄 시작이 아니면 : 띄어쓰기 2번 + 엔터해야함

-------

    
### 2.4 자주 쓰는 이모지  
  - 전체 : https://gist.github.com/rxaviers/7360908
  - ✴️
    ```
    :eight_pointed_black_star:
    ```
  
  - 🅰️  
    ```  
    :a:  
    ```
    
## 3 레포지토리 분류 및 순서     
  - 현재 : 초기엔 그냥 간단 분류법 진행. 최적안 선택 및 비교 분석 안했음  -> 이름 변경할 수도 있음  
    + 이유 1. 초기엔 레포지토리 이름 변경의 단점 발휘가 안되기 때문임 : 다른 사용자와의 상호작용 및 외부 활용 없음, 만든 양도 적음   
    + 이유 2. 내가 어떤 거를 할지 모르니 어떤 구조가 최적일지 한계가 있음 )
      
  - 적용안  
    A. 레포지토리 이름을 이용한 분류 1단 어느정도만 & 프로필에서 마인드맵처럼 레포지토리 분류를 잘 보여주는 방법  ( 이미지든 외부 플러그인? 등이든 )  
    B. 분류를 기본 2단 조합으로 할까 : (첫 분류가 서로 다른 순서분류집합/사전이랄까. A(=특정분류세트)-)   
    
  - 레포지토리 이름을 이용한 다양한 방법  
    + **추가 도입 시 체크 : 사용했던 방법과 충돌하지(섞임) 않는지 훑기**   
    + **아래 방법들의 조합 무한대번 가능** : A-01-, A01, 01A : 안섞이려면 -사용이 낫다.  
      - 섞이는 예시 : A- B- BA- 섞임  
      - 처음부터 전부 3bit 사용하는 방법도 존재는 함. 헥사코드 방법도 있긴함

    m1. 0번대, 00번대, 000번대 : 이거들끼리도 이름 순으로 하면 조금 섞이긴 함  
    m2. 알파벳순서 ( 대문자, 소문자 ) : a / A / aA / a-A / aa /   
    m3..... 특정 문자 반복 : i, ii, a, aa  
    m4... 챕터라는 단어 의미 표현 : 영어_챕터_ch,chap  
      <-> 이거 쓰면 못 쓰는 방법 : 알파벳 소문자
      
## 4 깃허브 코드 검색 인덱싱
  - 블로그에 관련 내용 더 있음  
  - 코드 검색의 경우 기본 분기만 인덱싱됩니다. * 5MB 미만인 파일만 검색할 수 있습니다.
  각 파일의 처음 500KB만 검색할 수 있습니다.



-----
## A 레포지토리 라이센스
  - [1] ChatGPT4 질문 핵심 내용 : 레포지토리 라이센스는 보통 뭐로 하니? 뭐가 좋니? 회사 것 아닌 개인 것일 때 기왕이면 누가 가져다 쓸거면 출처 정도는 해줬으면 좋겠음
    > 개인 프로젝트에 적합한 라이센스를 선택할 때는 프로젝트를 어떻게 공유하고 싶은지에 따라 다릅니다. 출처를 명시하도록 요구하면서도 타인이 프로젝트를 자유롭게 사용, 수정, 배포할 수 있게 하고 싶다면, 오픈 소스 라이센스 중 하나를 고려해 볼 수 있습니다. 가장 널리 사용되는 라이센스 중 몇 가지를 소개하겠습니다.
    + MIT 라이센스: 이 라이센스는 매우 유연하며, 사용, 복사, 수정, 배포를 포함하여 거의 제한 없이 프로젝트를 사용할 수 있도록 허용합니다. 단, 라이센스 복사본과 저작권 고지를 소프트웨어의 모든 복사본이나 중요한 부분에 포함시켜야 합니다. 이는 출처 표시 요구를 만족시키며, 매우 간단하고 이해하기 쉬워 개인 프로젝트에 인기가 높습니다.
  
    + Apache 2.0 라이센스: Apache 라이센스도 비슷한 유연성을 제공하지만, 사용자가 수정된 버전을 배포할 때 변경 사항에 대한 고지를 요구합니다. 또한, 특허 소송에 관한 보호 조항도 포함하고 있어, 조금 더 복잡하지만 보호를 강화하고 싶은 프로젝트에 적합할 수 있습니다.
  
    + GNU 일반 공중 사용 허가서(GPL): GPL 라이센스는 사용자가 프로젝트를 사용, 수정, 배포할 수 있도록 허용하지만, 수정된 버전도 동일한 라이센스 하에 공개되어야 한다는 'copyleft' 조건을 가지고 있습니다. 이는 프로젝트가 오픈 소스로 유지되도록 보장하지만, GPL 라이센스가 적용된 코드를 사용하는 모든 프로젝트 역시 GPL을 따라야 하므로 사용에 제약이 따를 수 있습니다.  
      
    + 크리에이티브 커먼즈 저작자 표시(CC BY): 소프트웨어보다는 창작물(예: 글, 이미지, 음악)에 더 자주 사용되지만, 출처를 명시해야 하는 조건 하에 작품을 자유롭게 사용할 수 있도록 허용합니다.
  
    > 개인 프로젝트에 어떤 라이센스를 사용할지 결정할 때는 프로젝트를 어떻게 공유하고 싶은지, 어떤 조건을 부여하고 싶은지에 따라 결정해야 합니다. MIT 라이센스나 Apache 2.0 라이센스는 유연하면서도 출처 표시 요구를 충족시켜 널리 사용됩니다. 프로젝트의 특성과 개인적인 선호도를 고려하여 선택하세요.




## B 기록 플랫폼
### B.1 올릴 만한 대상 
- 기술 내용 / 행사 / 일상 / 독서
### B.2 플랫폼 선택 시 고려 사항
- from 자료[1]
  + 위지윅(WYSIWYG) vs 마크다운
  + 코드 **하이라이팅**
  + **디자인 커스터마이징 범위**
  + **검색 엔진 최적화(SEO)**  
    [chat GPT] SEO 최적화: 티스토리 플랫폼은 사용자가 메타 태그, 제목, 설명 등 SEO 관련 요소를 커스터마이징할 수 있게 해줍니다. 올바른 SEO 전략을 사용한다면, 해외 검색 엔진에서도 좋은 성능을 낼 수 있습니다.  
  + 통계 지원 여부
  + **광고** 지원 여부  

- from 나 맞춤화   
  +
  + 해외 유입 가능 ( - 이건 너무 먼 일 같긴 하다. + 물론 나중에도 안옮기려면 그게 낫긴하지만 말이다. )

### B.3 적용안
- (1) 모든 곳에 마크다운으로 작성 & 여러 플랫폼에 올리기



## Z Self Feedback  
>> Feedback의 주제는 특정돼있지 않으며 주로 Daily Feedback에 가까움

## References
[1] Upstage AI lab 3기_학습 블로그 가이드 : https://github.com/journeythrunrun/common_private/blob/main/README.md _ [A]
