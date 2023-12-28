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

모드와 Forge의 다운로드 및 설치 방법에 대해서 다루는 파트입니다.

### 1. 1. 모드 목록

> 픽셀몬 리포지드([링크](https://reforged.gg/ko)) 진입 후 **1.20.2(ALPHA)** 및 **1.20.2-9.2.5(Forge 48.0.22)** 다운로드
>
> 본 레파지토리(github 화면 상단)의 **mods.zip** 다운로드

<details>
<summary>포함된 모드(참고용)</summary>

모드 | 개요 | 사이트 링크
-----|------|--------------
collective-1.20.2-7.16|호환성 향상|[Collective curse forge](https://www.curseforge.com/minecraft/mc-mods/collective)
jei-1.20.2-forge-16.0.0.28|아이템 및 조합법 확인|[Just Enough Items curse forge](https://www.curseforge.com/minecraft/mc-mods/jei)
journeymap-1.20.2-5.9.18-forge|미니맵|[Journey Map curse forge](https://www.curseforge.com/minecraft/mc-mods/journeymap)
spark-1.10.58-forge|서버 이슈트래킹|[Spark curse forge](https://www.curseforge.com/minecraft/mc-mods/spark)
stackrefill-1.20.2-4.1|인벤토리 편의성|[Stack Refill curse forge](https://www.curseforge.com/minecraft/mc-mods/stack-refill)

</details>


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
