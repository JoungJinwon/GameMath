# 게임 수학

"이득우의 게임 수학" 교재를 보고 실습한 예제 CK소프트렌더러 프로젝트입니다.

## 전체 로드맵

![로드맵](https://github.com/onlybooks/gamemath/blob/main/Document/로드맵.png "로드맵")

<p align="center">
<a href="https://ideugu.notion.site/05b87813fe644590bf0a09d5e7030909"> [단계별 예제 확인하기] <a>
</p>
  
## 요구사항
- 비주얼 스튜디오 2022 사용
- CMake 3.1버젼 이상 ( https://cmake.org/download/ ) 
- 본 프로젝트는 윈도우만 지원합니다.

## 사용하는 키

| 키                    |            기능            |
| --------------------- | :------------------------: |
| F1                    |         일반 모드          |
| F2                    |     와이어 프레임 모드     |
| F3                    | 깊이 버퍼 모드 ( 3D 전용 ) |
| F10                   |  2D 엔진과 3D 엔진의 변경  |
| 왼쪽,오른쪽 화살표 키 |      캐릭터 좌우 회전      |
| 위,아래 화살표 키     |      캐릭터 전후 이동      |
| 홈(Home),엔드(End)    |      카메라 FOV 조절       |

## 일반 모드

텍스쳐를 매핑해 렌더링합니다. 기즈모는 표시되나 본은 표시되지 않습니다.

<img src="https://github.com/onlybooks/gamemath/blob/main/Document/Samples/17-3c.gif">

## 와이어프레임 모드

선을 사용해 외곽선만 렌더링합니다. 기즈모와 본을 모두 표시해줍니다.

![와이어프레임 모드](https://github.com/onlybooks/gamemath/blob/main/Document/Wireframe1.png "와이어프레임 모드")

가까이서 확대하는 경우 동차좌표계에서 삼각형이 분할되는 과정을 확인할 수 있습니다.

![와이어프레임 모드 2](https://github.com/onlybooks/gamemath/blob/main/Document/Wireframe2.png "와이어프레임 모드 2")

## 깊이 버퍼 모드

원근 투영 변환 후 깊이 값을 선형화시켜 보여줍니다.

![깊이 버퍼 모드](https://github.com/onlybooks/gamemath/blob/main/Document/Depth.png "깊이버퍼 모드")
