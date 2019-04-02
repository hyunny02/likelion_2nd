
# 구현의도
카메라 회사이다 보니 깔끔하고 예술적인 분위기를 조성하기 위해 background image를 사용함. 

'당신의 순간을 담다'라는 키워드를 통해 회사의 가치관을 표현하며 카메라회사의 이미지를 담았다.
# 역할분담
### 이성현 
page1(main), page3(제품소개)
### 이지우 
page2(회사소개), page4(위치안내)

# 오류내용+해결방법
### 이성현
-창크기가 바뀜에 관계없이 창 정보를 고정시키고자 함.
Body width 100% + min-width:1000px  잘 안됨
-> 각각의 div 에 설정하였다.

-글자 크기를 px 고정 값이 아니라 em %를 사용하여 가변적으로 사용

-하이퍼링크시에 마우스를 올리거나 색이 변하는 것을 막기 위해 
css a태그 관련 코드를 사용 but hover시에 파란색밑줄은 없어지지 않음 -> 해결못함

-해상도에 따라서 유동적인 웹페이지를 구성하고자 화면 크기 배분에서 %를 사용함
### 이지우
-메인 이미지 밑 내용들을 원하는 위치에 정렬하고자 함.
-> 세세하게 div를 나눴다.
-구글 맵을 사용하고자 함.
->자바 스크립트를 이용해야 하는데, 모르는 영역이기 때문에 일단 코드를 긁어왔다.


#간단한 소감
### 이성현
꽉 찬 화면에서 만드는 것은 쉬웠지만 창의 크기가 변하며 각각 다른 환경에서의 사용자에게 똑같은 웹서비스를 제공하기 위해 고려해야할 것들이 많다는 것을 알게 되었다.
### 이지우
팀 과제를 처음 해봤는데, 나의 부족한 부분을 선배가 보완해주셔서 배울 점이 많았던 것 같다.
### 참고문서 링크
1. 구글지도 API를 이용하여 회사소개에 지도 넣기 / http://happycgi.com/14849
2. 페이지 연결 / https://aboooks.tistory.com/87

### 완성본 스크린샷 올리기
### 1. page1_main
![](.\image\screen_1)
### 2. page2_introduce
![](.\image\screen_2)
### 3. page3_product
![](image\screen_3_1)
![](.\image\screen_3_2)
### 4.page4_contact
![](.\imgae\screen_4)
