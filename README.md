# Bootstrap TEST

* Jquery, Bootstrap불러오기, 반응형 
```
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link href="assets/css/bootstrap-responsive.css" rel="stylesheet">
	<script src="http://code.jquery.com/jquery.js"></script>
	<link href="bootstrap/css/bootstrap.min.css" rel="stylesheet" media="screen">
```

* 유동형으로 변경, span으로 레이아웃 나누기

```
  <div class="containter">

	<div class="row hero-unit">
		<h2> JAVA SCRIPT</h2>	
		<p>자바스크립트를 열심히 배워봅시다.</p>
	</div>
	<div class="row-fluid">
		<div class="span4">
			<nav>
				<ul class="nav nav-tabs nav-stacked">
					<li><a href="#"> menu 1</a></li>
					<li><a href="#"> menu 2</a></li>
					<li><a href="#"> menu 3</a></li>
					<li><a href="#"> menu 4</a></li>
					<li><a href="#"> menu 5</a></li>	
				</ul>
			</nav>
		</div>
		<div class="span8">
			<article>
				자바스크립트는 스크립트 언어다
				자바스크립트(JavaScript)는 웹을 위한 인터프리터 언어이자 스크립트 언어다.
				자바스크립트로 작성된 프로그램을 스크립트라고 하며, 컴파일이 필요하지 않다. 그냥 HTML 웹 페이지에 스크립트를 삽입하기만 하면 동작하며 최신 웹 브라우저에서 모두 동작한다.
				자바스크립트를 주로 클라이언트 측 자바스크립트라고 하는데, 이는 스크립트가 웹 서버가 아닌 클라이언트 컴퓨터에 설치된 브라우저에서 실행된다는 의미다.
				<br><br>
				자바스크립트의 역할
				자바스크립트의 일반적인 용도는 웹 페이지에 기능을 더해 HTML 웹 페이지를 동적이고 살아 있게 만드는 것이다.
				자바스크립트는 다음과 같은 일을 할 수 있다. <br>
					<ul>
						<li>HTML 페이지 변경 및 HTML 엘리먼트와 콘텐츠의 추가나 제거</li>
						<li>CSS 및 HTML 엘리먼트의 스타일 변경</li>
						<li>사용자와의 상호작용, 폼의 유효성 검증	</li>
						<li>마우스와 키보드 이벤트에 대한 스크립트 실행</li>
						<li>웹 브라우저 제어, 쿠키 등의 설정과 조회</li>
						<li>AJAX 기술을 이용한 웹 서버와의 통신</li>
					</ul>
			</article>
		</div>
	</div>

</div>
```
