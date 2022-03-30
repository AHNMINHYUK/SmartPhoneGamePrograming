# SmartPhoneGamePrograming
##### 게임 개요
![160738267-e7d5bea3-5099-4bbf-be0f-9d3abab0af08](https://user-images.githubusercontent.com/89964495/160738537-f741f10c-0aa4-4eba-88fe-5f8489a1cd88.png)
![image](https://user-images.githubusercontent.com/89964495/160734884-380455d8-ab76-4972-af89-4ccf53d0f80d.png)
##### - Stage는 총 3개로 구성
##### - 각종 장애물을 피하고 몬스터를 해치운다
##### - 각 Stage 마지막에는 보스가 존재
##### - 보스를 해치워야 다음스테이지로 이동 가능
##### - 몬스터에게 피격당하거나 장애물에 걸리면 해당 스테이지를 처음부터 다시 시작하게 된다.
##### - 플레이어는 총알로 몬스터를 해치울 수 있으며 점프를 이용하여 장애물을 피할 수 있다.
##### - 플레이어가 타일이 없는 낭떠러지로 떨어지게 될경우 게임오버
##### 게임 특징
![image](https://user-images.githubusercontent.com/89964495/160734694-f8a7faeb-7b8b-4d15-b0e9-6620c1fce262.png)
##### 몬스터
##### - 바닥 타일이 있는 곳에 몬스터 배치
##### - 플레이어에게 피격당할 경우 몬스터는 사망
##### - 몬스터는 따로 공격이 없으나 플레이어와 접촉시 게임오버
##### - 스테이지 마다 몬스터가 다르다
##### 보스
##### - 보스의 HP가 2분의1로 감소하게 되면 공격패턴 변경
##### - 보스 또 한 스테이지마다 다름
##### 장애물
##### - 바닥 타일이 있는 곳에 장애물 배치 예정
##### - 장애물은 곳곳에 숨겨져 있는 형식으로도 배치 할 예정
##### - 장애물과 플레이어 접촉 시 게임오버
##### 조작법
![image](https://user-images.githubusercontent.com/89964495/160735367-4416aeee-0139-41f5-b6aa-1013d36e23bf.png)
##### - 게임은 가로View를 고정한 상태로 진행 예정
##### - 2D 횡스크롤 게임
##### - 왼쪽 하단에 방향키 왼쪽, 오른쪽 이동버튼 두개가 존재
##### - 오른쪽 하단에 총알을 발사할 수 있는 버튼과 점프버튼이 존재
##### 예상게임흐름
![image](https://user-images.githubusercontent.com/89964495/160742546-224d882d-abf2-4c18-a95d-85d34135cc83.png)
##### 구현할 내용
##### 플레이어
![image](https://user-images.githubusercontent.com/89964495/160735527-de648177-e132-43c3-9300-dfb12a010bd9.png)
##### - 플레이어는 기본적으로 점프와 공격 모션이 가능
##### - 2D 도트 이미지를 활용
##### - 플레이어가 소지한 총알은 누를때마다 나가며 총알 갯수에 대한 제한은 없다
##### 몬스터
##### - 3종의 몬스터를 구현 예정
##### - 스테이지 마다 다른 몬스터들을 구현할 예정
##### - 몬스터들의 애니메이션은 각각 다름
##### - 보스는 많은 체력을 보유하고 있으며 총알로 피격을 해야만 물리칠 수 있다.
##### 장애물
![image](https://user-images.githubusercontent.com/89964495/160735880-330bd30c-e6eb-412b-955f-1031b58840cd.png)
![image](https://user-images.githubusercontent.com/89964495/160735938-9f3ab608-81c6-46ac-9565-d65a22b0ee94.png)
##### - 장애물은 바닥 타일에 숨겨져 있기도 하며 눈에 직접적으로 보이기도 한다.
##### - 장애물은 사진과 같이 가시를 사용하며 가시는 숨겨져 있기도 하다.
##### - Y축에선 떨어지는 장애물을 구현할 예정
##### 개발일정 계획

|제목|내용|
|:---:|:---:|
|1주차|리소스 수집|
|2주차|조작 버튼 배치 및 플레이어 애니메이션 구현|
|3주차|Stage1 맵 배치(플레이어 발판 배치), 장애물 충돌처리 구현|
|4주차|Stage1 몬스터 및 보스 애니메이션 구현|
|5주차|몬스터 및 보스 충돌처리 구현|
|6주차|Stage2, Stage3 맵 배치(플레이어 발판 배치)|
|7주차|Stage2 장애물 및 몬스터(보스포함) 충돌처리 구현|
|8주차|Stage3 장애물 및 몬스터(보스포함) 충돌처리 구현|
|9주차|버그수정 및 최종시현|
