# webprogram
<!DOCTYPE html>
<html>
    <head>
    <title>나의 소개</title>  
    <style>
        body{background-color: pink; color: green; margin-left: 40px; margin-right: 40px;}
        h3{text-align : center ; color : blue;}
        hr {height : 5px; border : solid grey; background-color : gray;}
        span{color: brown; font-size: 20px;}
    </style>
    <script>
        function show() {
            document.getElementById("fig").src="shrek.png";
        }
        function hide() {
            document.getElementById("fig").src="";
        }
    </script>
    </head>
    <body>
        <h3 onmouseover="show()" onmouseout = "hide()"> 슈렉</h3>
        <hr>
        <div><img id="fig" src=""> </div>
        저는 대한민국에서 태어나서 컴퓨터 공학을 전공하는 학생입니다.
        제가 제일 좋아하는 과목은 <span> 웹 프로그래밍 </span> 이고,
        그 중에서도 <span> 자바스크립트 </span> 를 제일 잘합니다.


    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
    <title>웹 페이지 구성 요소</title>  
    <style>
        body{background-color: pink; color: green; margin-left: 40px; margin-right: 40px;}
        h3{text-align : center ; color : brown;}
        hr {height : 10px; border : solid grey; background-color : gray;}
        span{color: violet; font-size: 20px;}
    </style>
    </head>
    <body>
        <h3> Elvis Presley</h3>
        <hr>
        He was an American singer and actor. In November 1956, he made his film debut in<span> Love Me Tender</span>. He is often referred to as "<span>the King of Rock and Roll</span>".


    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
    <title>웹 페이지 구성 요소</title>  
    <style>
        body{background-color: pink; color: green; margin-left: 40px; margin-right: 40px;}
        h3{text-align : center ; color : brown;}
        hr {height : 10px; border : solid grey; background-color : gray;}
        span{color: violet; font-size: 20px;}
    </style>
    <script>
        function show() {
            document.getElementById("fig").src="shrek.png";
        }
        function hide() {
            document.getElementById("fig").src="";
        }
    </script>
    </head>
    <body>
        <h3> Elvis Presley</h3>
        <div><img id="fig" src=""> </div>
        He was an American singer and actor. In November 1956, he made his film debut in<span onmouseover="show()" onmouseout = "hide()"> Love Me Tender</span>. He is often referred to as "<span>the King of Rock and Roll</span>".
     
    </body>
</html>

<!DOCTYPE html>
<html>
    <head>
    <title>오류를 찾으세요</title>  
    <style>
        h3{text-align : center ; color : darkred;}
        span{color: blue; font-size: 20px;}
    </style>
    </head>
    <body>
         <h3> Elvis Presley</h3>
         He was an American singer and actor. In November 1956, he is often referred to as "<span>the King of Rock and Roll</span>".


    </body>
</html>
