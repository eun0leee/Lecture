### HTML의 중요성  
개발자 도구를 보면 
HTML이 웹 브라우저 환경의 베이스가 됨  
  
  
### Semantic Markup  
* 문서 구조와 정보 위계가 명확히 보이는 의미구조에 맞는 코드  
div링크 남발하지 말자.  
iv는 브라우저가 정보의 위계질서 파악하는데 큰 도움을 주지 못함  
nav 태그를 소중히 씀. 한 페이지 당 보통 1개.  
+ nav : 다른 웹페이지로 연결하는 링크 모음인 네비게이션 바를 만들 때 사용함  
```
  <nav> 
    <ul> 
      <li><a href="#">Home</a></li> 
      <li><a href="#">Blog</a></li> 
      <li><a href="#">Album</a></li> 
      <li><a href="#">Music</a></li> 
      <li><a href="#">Map</a></li> 
    </ul> 
  </nav>
```  
  
* 검색엔진 최적화(Search Engine Optimization)   
브라우저는 내용의 중요도를 코딩한대로 이해함  
그 중요도가 검색엔진에 반영됨  
