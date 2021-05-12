# Unrealengine 공부하기

# 1일

### 프로젝트 세팅

#### 1번 새 프로젝트 선택

![image](https://user-images.githubusercontent.com/80494367/117901233-df730e80-b305-11eb-892b-164e4d5c5d25.png)

게임 / 영상 / 건축 / 제품 디자인 등에 사용          
    
![image](https://user-images.githubusercontent.com/80494367/117901506-717b1700-b306-11eb-99ad-0c34c357918f.png)
    
자신이 만들고자 하는것 맞게 선택
    
![image](https://user-images.githubusercontent.com/80494367/117900345-f87ac000-b303-11eb-99c4-4819fcde02fe.png)
    
블루프린트 / C++ : 코드 이용
    
레이 트레이싱 : 랜더링 결과를 고품질로 (간접광 등 이용)

### 마켓 플레이스
   
![image](https://user-images.githubusercontent.com/80494367/117900582-7212ae00-b304-11eb-92b7-9ee311cb02d8.png)
   
#### 각종 상품 구성 확인

### 본격적인 실행 프로젝트
   
![image](https://user-images.githubusercontent.com/80494367/117902709-0bdc5a00-b309-11eb-9c79-6a537ce59383.png)
   
####  ctrl 마우스 휠로  콘텐츠 브라우저 파일 아이콘 크기 조절 가능
   
   왼쪽 창 : 툴 창
   오른쪽 창 : 아웃라이너 + 특성(채널박스 등)
      
![image](https://user-images.githubusercontent.com/80494367/117903143-fae01880-b309-11eb-939a-add19da37064.png)
![image](https://user-images.githubusercontent.com/80494367/117903180-0a5f6180-b30a-11eb-950e-30c62041a24a.png)
   
##### 리플렉션 : 반사 이펙트
볼륨 : 포스트 프로세스 볼륨 / 라이트매스 임포턴스 볼륨
공간감 살리기   


### 세팅창들

![image](https://user-images.githubusercontent.com/80494367/117903676-f2d4a880-b30a-11eb-9fe2-b2ec0bad5fe2.png)

#### 플래그
![image](https://user-images.githubusercontent.com/80494367/117903879-5232b880-b30b-11eb-80ab-37fe32b56b13.png)

water , mass 플래그

#### 프로젝트 세팅
![image](https://user-images.githubusercontent.com/80494367/117904129-c0777b00-b30b-11eb-8603-d155c421857e.png)
   
   맵 & 모드 :  기본적인 맵세팅 등

![image](https://user-images.githubusercontent.com/80494367/117904408-47c4ee80-b30c-11eb-9e38-8ad11193f143.png)

   입력 (컨트롤 창)
   

나이아가라 : Fx플래그



### 인게임

##### ctrl + L 마우스 이동 통해  광원 위치(어디서 비치는지  시간 흐름처럼)


### 매터리얼

![image](https://user-images.githubusercontent.com/80494367/117909227-cde53300-b314-11eb-9f70-a8c50f098b0e.png)

![image](https://user-images.githubusercontent.com/80494367/117909471-45b35d80-b315-11eb-92c8-76696eafcda8.png)

   
#### 1번키 + 클릭 :  상수 창
2번키 + 클릭 : 2포인터(2배열)
3번키 + 클릭 : 3포인터(3배열)
T키 + 클릭 : 텍스쳐
L : Lerp
M : Multiply

c : 선택한 옵션들을 그룹화

ctrl 클릭으로 연결 괸 선 제거 가능

// 언리얼 복사 : ctrl + w
   
   
### landscape
   
   ![image](https://user-images.githubusercontent.com/80494367/117909797-e275fb00-b315-11eb-9bc1-b681680646da.png)

   ####landscape LayerBlend : 각 특성(땅 나무 하늘)마다 레이어를 주고  각 레이어마다 편집
     배이스 컬러 / 노말맵 / 러프니스 / 엠비언트 오클루젼 등  각 지형(landscape)의 물체마다 텍스쳐 입히기
   
   ![image](https://user-images.githubusercontent.com/80494367/117910927-cffcc100-b317-11eb-8ce4-ab2cb04c2e86.png)
   
   landscape LayerCoords : 지형의 크기(UV) 조절 / 
      

### asset 집어넣기
#####   

![image](https://user-images.githubusercontent.com/80494367/117921441-b5ccde00-b32b-11eb-9999-0395d2d28254.png)
   
   skeletal mesh  : 뼈대가 존재하는것들
   mesh  고급 툴 > Import Mesh LODs  :  LOD 전부다 순서맞게 임포트
      
   Generate Lightmap UVs : 자동으로  라이트맵 구현
      
   Transform : 로테이션  위치  크기 등 조절가능 // 사전 임포트하는 오브젝트의 방향이 어긋날때 미리 수정
      
   Material
   
   
![image](https://user-images.githubusercontent.com/80494367/117922824-02191d80-b32e-11eb-8b8f-70d82644bfea.png)

UV채널 0,1,2... 기존 UV맵  라이트맵
콜라이더 : 단순 / 복합 콜라이더 (충돌)

![image](https://user-images.githubusercontent.com/80494367/117924344-8e2c4480-b330-11eb-87b9-2265b8acc1f5.png)

각 텍스쳐 맞게  연결해주기  이후 매터리얼 오브젝트에 입히기
   
      
## 랜드스케이프
모드에서 랜드스케이프
![image](https://user-images.githubusercontent.com/80494367/117926510-d8fb8b80-b333-11eb-965c-c28fc0cbabdd.png)


![image](https://user-images.githubusercontent.com/80494367/117929260-8e7c0e00-b337-11eb-8c6b-f7750683aea1.png)
## 랜드스케이프 + 플랜트 모드

지형편집 +  플랜츠 심기 :  블루프린트  브러쉬를 사전에 플래그로 설치한 랜드로  맞춘후  그리기

![image](https://user-images.githubusercontent.com/80494367/117929864-427d9900-b338-11eb-8859-407160372b86.png)


effect  curnoise 에서 효과 추가 가능(랜드 모양)

