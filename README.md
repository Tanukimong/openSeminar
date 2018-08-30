# 사자가 딴짓할 때

딴짓 주제 : Matlab & Github

## 개요
- 너몽의 첫번째 오픈 세미나에 대한 자료가 모두 포함되어 있습니다.
- 너몽 연락처 : https://open.kakao.com/o/sH7GNJF <- 세미나 종료후 헷갈리는게 있다면 물어보세요!

## 사전준비
- Matlab 설치해오기 : http://electronic.hanyang.ac.kr/notice/view_hi.php
  - **주의! : 반드시 설치할때 Symbolic toolbox 옵션 체크!!** -> 아니면 아래의 Symbolic 사용불가.

## 수업 과정
### Git
목표 : Github를 이용하여 수업자료 다운받기
- 어디에 쓸모있는가?
- 설치 방법
  - Student혜택 ID 만들기 : https://education.github.com/pack
  - Sourcetree 설치 : https://www.sourcetreeapp.com
  - Atom editor 설치 : https://atom.io
- 실습
  - Lv0 : 수업자료 Cloning
    - 이 Git 저장소를 Cloning
    - [설명] Flow of use (사용 시나리오)
  - Lv1 : Git 저장소 생성
    - 한 번에 Local 저장소와 이에 연결된 Remote 저장소 생성
      - 생성된 Local 저장소 -> SourceTree에서 확인
      - 생성된 Remote 저장소 -> 자신의 Github계정에 접속하여 확인
    - [설명] Local vs Remote
  - Lv2 : Commit
    - README.md 파일 생성
    - Commit하여 Local Git 중간 저장
    - Commit내역 모두 Local Git에 올리기
    - 버전 한눈에 보기
  - Lv3 : Branch와 Merge
    - Branch : 원본을 손상하지 않고 개선하기
    - Merge와 Conflict
      - Conflict의 조건 (Branch change -> Master change)
      - Conflict 해결법
        - Example : Branch change -> Master change & Merge from branch to Master
  - Tip
    - 오픈 소스기반의 협업시 중요
    - Pull시 Conflict 조건 (Local change -> Remote change)
    
### Matlab
목표 : Matlab을 이용하여 초등~대학수학 문제를 컴퓨터로 검증시킨다.
- Matlab은 어디에 쓸모있는가?
  - 신호처리, 인공지능, PID제어기 설계 등등
- 사자초등학교
  - **사칙연산**
  - ANS
  - 변수를 확인하는 법
- 사자중학교
  - 요소연산 (.연산)
  - **Symbolic toolbox를 이용한~**
    - Graph 그리기
    - 연립방정식 풀기
    - 결과를 원하는대로 보기
      - 인수분해, factor
      - 식 전개, expand
      - 식 내림차순으로 정리, collect(eqn,x)
      - 익숙하게 보기, pretty
- 사자고등학교
  - **Graph 꾸미기** <- 과제할 때 짱 좋음!!
    - **그래프 비교 : subplot**
    - **그래프 설명 붙히기 : title**
    - **보고싶은 범위 지정하기 : axis**
    - **xy축이 각각 뭔지 설명하기 : label**
    - 식을 서로 비교 : hold on/off
    - 숨겨진 기능 : 식을 부드럽게 만들기
- 사자대학교
  - **오! 나의 구글신님!**
    - Matlab문서 찾기
  - **두 행렬 한 번에 비교하기 ==**
  - 선형대수
    - linspace와 : 연산
    - **:와 1, end를 이용한 행렬 접근**
    - 0행렬, 1행렬 간단하게 생성
    - LU 분해
    - **역행렬 구하기**
  - Convolution
    - conv : https://kr.mathworks.com/help/matlab/ref/conv.html
  - Fourier Transform
    - fft와 ifft
    - Audio불러와서 실습해보기
      - sound와 Fs(Sampling frequency)
      - audioinfo와 audioread
  - **단순화 방법**
    - for loop
      - 사용시 주의사항 feat. 행렬연산
    - Function화
    - if문

### 광고(?)
- https://hanyang.wiki <- 심심하면 들려주시고, 괜찮다면 항목 작성 부탁
