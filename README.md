<!DOCTYPE HTML>
	<title>디폴트숙제-심우영</title>
	<head>
		<meta charset="UTF-8">
		<style type="text/css">
			body{
				background-color:#87CEEB;
				width: 700px; 
				margin: 0 auto;
				text-align: center;
			}
			button{
				background-color: #FFFFFF;
				border: none;
				color: blue;
				text-align: center;
				margin: 8px 16px;
			}
			#mondai{
				color:red;
				width:300;
				font-size:20pt;
			}
			#margin{
				width: 400px;
				margin: 0 auto;
			}
		</style>
		<script ="text/javascript">
			function chang(){
				alert("정답")
			}
			function nono(){
				alert("오답")
			}
		</script>		
	</head>
	<body>
		<h1 id="mondai">문제 1번</h1>
		<br>
		<div id="margin">이 음식의 이름은??</div>
		<img src="http://ton-q.com/image/menu/lunch/p_don_pc.jpg" width="600" height="428">
		<br>
		<br>
		<a href="wrong.html">
			<button onclick="nono();">1.돈가스</button>
		</a>
		
		<a href="defaulthw1.html">
			<button onclick="chang();">2.가츠동</button>
			
		</a>
		
		<a href="https://github.com/">
			<button>3.규동</button>
		</a>
		
		<a href="https://github.com/">
			<button>4.짜장면</button>
		</a>
		
		<a href="https://github.com/">
			<button>5.피자</button>
		</a>
	</body>
</html>
