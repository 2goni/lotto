외부 웹 주소 :http://mit4.iptime.org:2780 <br>
로또번호를 사용자의 입력 정보에 따라 추천해주는 프로젝트입니다. <br>
이프로젝트를 만들 당시 황금비율에 빠져있어서 황금비를 이용한 로또 추천 알고리즘을 적용 했습니다. <br>
사람마다 가지고있는 특성으로 로또번호를 추천 받을수 있으면 재밌을거 같아 제작했습니다.<br>
이 프로젝트는 JAVA, Spring, mybatis, mariaDB, jsp를 이용해 만들어졌습니다.<br>

<h1> 로또 추천 알고리즘</h1>
  <h3> 초기 </h3>
  로또 랜덤 시드값으로 서버 날짜와 사용자 입력 값(생년월일)을 전부 더한후 1.618(황금비) 곱하기 <br>
  - 문제점 : 2월 4일생과 4월 2일생 같은 로또번호 추천받음 <br>
  <h3> 사용자 이름 받기</h3>
  사용자 이름 아스키 값으로 변환해서 시드값에 더하기
  - 초기 문제점 해결
  - 문제점 : 작성값이 개인정보라서 예민할수 있음
 
  
