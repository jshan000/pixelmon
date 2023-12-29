# Pixelmon world info.

## 목차

[1.](#1-다운로드-방법) 다운로드 방법
   
   [1.1.](#1-1-모드-목록) 모드 목록
   
   [1.2.](#1-2-설치-방법) 설치 방법
   
[2.](#2-서버-개요)  서버 개요

   [2.1.](#2-1-서버-정보) 서버 정보

   [2.2.](#2-2-서버-룰) 서버 룰


---

## 1. 다운로드 방법

모드와 Forge의 다운로드 및 설치 방법에 대해서 다루는 파트


### 1. 1. 모드 목록

> 픽셀몬 리포지드([링크](https://reforged.gg/ko)) 진입 후 **1.16.5(STABLE)** 및 **1.16.5-9.1.10 (Forge 36.2.34)** 다운로드
>
> 본 레파지토리(github 화면 상단)의 **mods.zip** 다운로드

![리포지드 사이트 버튼](https://github.com/jshan000/pixelmon/assets/54829817/3d8e87fa-ce0f-4146-881c-a89151a69697)  
<sup>리포지드 사이트에서 클릭해야 할 버튼</sup>

![다운로드 누른 후 버튼](https://github.com/jshan000/pixelmon/assets/54829817/894167d1-0c5a-46b7-9bfc-7db380c936f8)  
<sup>다운로드를 누르면 5초를 기다린 후 우측 상단에 skip 버튼이 생기니 눌러서 다운하자</sup>

![mods.zip](https://github.com/jshan000/pixelmon/assets/54829817/8c2a1782-b84b-41a7-84c9-65f984305e70)
<sup>mods.zip은 해당 문서에서 위로 올라가보면 존재하니 참고</sup>


<details>
<summary>포함된 모드(*참고용)</summary>

모드 | 개요 | 사이트 링크
-----|------|--------------
Bookshelf-Forge-1.16.5-10.4.33|모드 호환성 패치|추후 추가
byg-1.3.6|바이옴 추가|추후 추가
entityculling-forge-mc1.16.5-1.5.2|클라이언트 렉 개선|추후 추가
ferritecore-2.1.1-forge|램 사용률 최적화|추후 추가
Hwyla-forge-1.10.11-B78_1.16.2|툴팁 출력|추후 추가
jei-1.16.5-7.8.0.1009|아이템 목록 출력|추후 추가
journeymap-1.16.5-5.8.5p6|미니맵|추후 추가
NaturesCompass-1.16.5-1.9.1-forge|바이옴 나침반|추후 추가
Pixelmon-1.16.5-9.1.10-universal|픽셀몬|https://reforged.gg/ko
PixelmonInformation-1.16.5-9.0.11-2.3.0|픽셀몬 정보 추가|추후 추가
PokeballReveal-1.16.5-1.0.0|픽셀몬 볼 정보 추가|추후 추가
smoothboot-forge-1.16.4-1.2.2|부팅 속도 개선|추후 추가

</details>

**모두 다운 받았다면 아래로 내려가자**


### 1. 2. 설치 방법

> 설치는 다음과 같은 순서로 진행 (*아래에서 자세하게 설명)
>
> 1. [1.1.](#1-1-모드-목록)에 기입된 방법으로 mods.zip과 픽셀몬, Forge 다운로드
> 2. mincraft에 Forge client 설치하기
> 3. mincraft 내부 mods 폴더에 모드 이동하기
> 4. mincraft 내부 config 폴더에 콘피그 파일 이동하기
> 5. mincraft 실행 후 설치

> Forge 설치

1. 다운받은 **forge-1.16.5-36.2.34-installer.jar** 실행 <-- **Java 8**이 없다면 실행되지 않음.. 먼저 다운 받을 것
2. 
![Forge 설치](https://github.com/jshan000/pixelmon/assets/54829817/7c888d4b-8de3-4606-bb64-0fbd3067dfa3)  
<sup>포지 설치 시 해당 화면에서 확인만 누르자</sup>

2. Install client 클릭 후 OK <-- 만약 자신이 임의로 마인크래프트 폴더를 옮긴 적이 있다면 경로를 지정, 모르겠으면 안하면 됨
3. 이후 실행시킬 때 추가 설치는 자동으로 됨

> 이후의 과정

![실행창](https://github.com/jshan000/pixelmon/assets/54829817/0f61571a-907b-4cae-9efa-c5ecc22bed9e)
<sup>윈도우+R키를 누르면 나오는 창으로 위처럼 입력하고 확인을 누르자</sup>
1. **윈도우 + R**키를 입력하여 실행창으로 진입
2. 입력창에 <b>%appdata%</b>를 기입 후 확인
3. **.minecraft** 디렉토리(폴더)로 진입
4. **mods 폴더**가 있다면 **mods 폴더에 mods.zip 안의 모드(.jar 파일들)와 픽셀몬 모드(forge만 제외)를 옮김** <--- 없다면, mods 폴더를 만든 뒤에 넣으면 됨

   4.1. **mods 폴더에 있던 기존의 모드는 제거하거나 옮겨두어야 함**

5. **config 폴더**가 있다면 **config 폴더에 mods.zip 안의 config(config 폴더의 내용물)를 옮김** <--- 없다면, config 폴더를 그대로 넣으면 됨
   
   5.1. **config 폴더에 있던 기존의 파일은 제거하거나 옮겨두어야 함**

> 마인크래프트 실행 후 설치

1. 모든 과정이 종료되면, **마인크래프트 런처**를 실행
2. **플레이 버튼 좌측의 버전**이 **forge** (1.16.5-forge-36.2.34)로 설정되어 있는지 확인 후 실행
3. 서버 domain 입력 후 접속


---

### 2. 서버 개요

서버의 정보와 config에 입력된 룰에 대한 내용입니다.

#### 2. 1. 서버 정보

서버 주소

``` choenan09.codns.com ```

서버 운영

``` 한율(Discord ID: hanyul) ```

서버 개설 시간

``` 미정, 보통 17:00 ~ 23:00 예상 ```

#### 2. 2. 서버 룰

> 대전제

1. 서버가 운영되는 시간 의외의 시간에 발생한 모든 일에 대해서는 룰 바깥에서 적용됩니다.
2. 마인크래프트 서버에 접속하여서 일어나는 일 의외의 모든 일에 대해서는 룰 바깥에서 적용됩니다.

> 픽셀몬 config 순정과 다른 점

**battle**
1. pvp로 경험치 획득 불가

**config**
1. move tutor(기술상인)이 ~20~->40 개의 기술을 들고 옴
2. always have mega ring and dynamax band -> 처음부터 메가 링과 다이맥스 밴드를 들고 시작
3. 침대가 포켓몬을 치료하지 않음
4. **자전거를 자체적으로 금지**
5. 대책으로 라이딩을 해금, 속도 제한은 현재 땅 0.2, 하늘 0.8
