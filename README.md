# 사자가 딴짓할 때

딴짓 주제 : Matlab & Github

## 팁
- 너몽의 첫번째 오픈 세미나에 대한 자료가 모두 포함되어 있습니다.
- Sample 1보다 Sample 2가 음질이 좋아서 LPF 적용후의 변화를 더 잘 느낄 수 있습니다.

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
- Github를 이용하여 수업자료 다운받기
  - Git cheat sheet by 너몽.
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
## 다시 Git.
- 간단한 if문 기반의 프로그램 작성 후 버전관리 
  - git init
  - git add
  - git commit
  - git remote
  - git push/pull
