# youtube 링크 걸 때 전체화면 버튼 활성화 시키는 방법

---
* 아래의 명령어 복사하고 "코드" 라고 되어 있는 부분에 
YouTube 동영상(https://youtu.be/WPVA9tJMZWQ)중 뒷부분(WPVA9tJMZWQ)을 붙여 넣으면
정상적으로 전체화면이 표시됨  
* 소스코드 앞에 꼭 '<' 표시를 넣어줘야 동작함   
* allowfullscreen="true" 라는 부분이 전체화면 버튼을 활성화 시켜주는 부분임
* 네이버 블로그에 적용하고 싶을 경우 이전 버전 에디터는 html편집기에서 적용하면 되지만 블로그 에디터 3.0에서는 지원 안함(구글 크롬 개발자 도구로 수정하면 됐었지만, 최근에는 그마저도 막힘, 오히려 유튜브로 가서 전체화면을 보는 경우가 생겨 유튜브 조회수만 늘려주게 되는데 왜 그런 정책을 펴는지 이해할 수 없음.

---

* **1080p화질로 재생**  
embed src="http://www.youtube.com/v/코드?version=3&hl=ko_KR&vq=hd1080" type="application/x-shockwave-flash" width="640" height="360" ="always" _allowfullscreen="true"_></embed>  


* **720p화질로 재생**  
embed src="http://www.youtube.com/v/코드?version=3&hl=ko_KR&vq=hd720" type="application/x-shockwave-flash" width="640" height="360" ="always" _allowfullscreen="true"_></embed>
 

* **일반화질로 재생**  
embed src="http://www.youtube.com/v/코드?version=3&hl=ko_KR" type="application/x-shockwave-flash" width="640" height="360" x-allowscriptaccess="always" _allowfullscreen="true"_></embed>
 
 
* **예제**  
embed src="http://www.youtube.com/v/WPVA9tJMZWQ?version=3&hl=ko_KR&vq=hd1080" type="application/x-shockwave-flash" width="640" height="360" ="always" _allowfullscreen="true"_></embed>  


---
### 예제가 적용된 홈페이지 
[![아래 사진을 클릭하세요.](https://raw.githubusercontent.com/mtinet/you/gh-pages/youtube_link.png)](http://mtinet.github.io/youtube_fullScreenVideoLink)  

_위에 index.html 파일을 확인해보면 동영상에 나오는 아주 간단한 홈페이지의 소스코드를 확인할 수 있습니다._
