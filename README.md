# 프로젝트 속성
- 프로젝트 실행 실패시 확인 사항

## 모든 구성

### 구성 속성 - 디버깅
 - PATH=$(SolutionDir)\SFML-2.6.1\bin

### C/C++ - 일반 - 추가포함 디렉터리
 - $(SolutionDir)\SFML-2.6.1\include

 ### 링커 - 일반 - 추가 라이브러리 디렉터리
 - $(SolutionDir)\SFML-2.6.1\lib

 ## Debug
 ### 링커 - 입력

sfml-audio-d.lib
sfml-graphics-d.lib
sfml-network-d.lib
sfml-system-d.lib
sfml-window-d.lib
sfml-main-d.lib

 ## Relese
 ### 링커 - 입력
sfml-audio.lib
sfml-graphics.lib
sfml-network.lib
sfml-system.lib
sfml-window.lib
sfml-main.lib