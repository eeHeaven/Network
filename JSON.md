 ## JSON
 
 JSON 그자체 는 단순히 데이터 포맷일 뿐. 어떠한 통신 방법도, 프로그래밍 문법도 아닌 단순히 데이터를 표시하는 표현 방법일 뿐                                     
 간단한 데이터를 xml보다 좀 더 간단하게 표현하기 위해 만든 것                     
 XML보다 기능이 적기 때문에 파싱도 빠르고 간단하기 때문에 클라이언트 사이드에서, 특히 모바일에서 더욱 유용               
사실 서버 입장에서도 더 유용하기 때문에 많은 서비스들이 XML보다는 JSON을 권장                               
**단순히 데이터를 받아서 객체나 변수로 할당해서 사용하기 위한 것**            
Xml 은 헤더가 붙지만 json은 단순히 {},로 데이터를 나누기 때문에 훨씬 편하고 가볍다.    

JSON의 한계는 JSON으로 가져올 수 있는 데이터는 해당 자바스크립트가 로드된 서버의 데이터에 한정된다는 것                 
예를 들어서 http://kwz.kr/json.js에서 불러올 수 있는 데이터는 kwz.kr 서버에 존재하는 것만 가능함. 구글 데이터를 불러온다거나 네이버 데이터를 불러온다거나 할 수 없음.               
JSON은 단순히 데이터 포맷일 뿐이고 그 데이터를 불러오기 위해선 XMLHttpRequest()라는 자바스크립트 함수를 사용해야 하는데 이 함수가 동일 서버에 대한 것만 지원하기 때문               
