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

> 설치 순서
>
> 1. [1.1.](#1-1-모드-목록)에 기입된 방법으로 모드 다운로드
> 2. Forge 설치
> 3. mods 폴더에 모드 이동
> 4. config 폴더에 설정 파일 이동
> 5. 마인크래프트 실행 후 설치

설치는 위와 같은 방법으로 진행

> Forge 설치

1. 다운받은 **forge-1.20.2-48.0.22-installer.jar** 실행 <--- Java 8 및 jdk 17이 없다면 실행되지 않음.. 먼저 다운 받을 것
2. Install client 클릭 후 OK <-- 만약 자신이 임의로 마인크래프트 폴더를 옮긴 적이 있다면 경로를 지정, 모르겠으면 안하면 됨
3. 이후 실행시킬 때 추가 설치는 아래 항목에서 다룸

+ 이 과정에서 문제가 발생하는 경우가 종종 있습니다.
+ 포지를 설치할 때 버전을 꼭 확인하시길 바랍니다.

> 이후의 과정

1. **윈도우 + R**키를 입력하여 실행창으로 진입
2. 입력창에 <b>%appdata%</b>를 기입 후 확인
3. **.minecraft** 디렉토리(폴더)로 진입
4. **mods 폴더**가 있다면 **mods 폴더에 mods.zip 안의 모드(.jar 파일들)와 픽셀몬 모드(forge만 제외)를 옮김** <--- 없다면, mods 폴더를 만든 뒤에 넣으면 됨
5. **config 폴더**가 있다면 **config 폴더에 mods.zip 안의 config(config 폴더의 내용물)를 옮김** <--- 없다면, config 폴더를 그대로 넣으면 됨

> 마인크래프트 실행 후 설치

1. 모든 과정이 종료되면, **마인크래프트 런처**를 실행
2. **플레이 버튼 좌측의 버전**이 forge (1.20.2-forge-48.0.22)로 설정되어 있는지 확인 후 실행
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

> 픽셀몬 관련 룰

1. 픽셀몬 라이드 금지
2. 같은 전설 몹 제단은 1회 사용하면 사용 불가(global)
3. 시작 골드 10000 지급
4. tp(텔레포트 명령어) 금지
5. 각종 유틸적인 픽셀몬 명령어 사용 가능(확인류, 치트 제외)
6. 자전거 금지
7. 다이맥스 밴드 및 키스톤 밴드 지급
