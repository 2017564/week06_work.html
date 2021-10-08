# week06_work.html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heejung's self-introduction webpage</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="http://www.w3schools.com/w3css/4/w3.css">
    <style>
        body {width: 980px; margin: auto; text-align: center; }
        * {font-family: "돋움", Arial, Helvetica, sans-serif}
        h2{color: rgb(51, 51, 51); background: rgb(209, 149, 90, 0.7); text-align: center; font-size: 35px;}
        ul { list-style-type: none; margin: 0;padding: 0;  overflow: hidden; }
        li {float: left;}
        li a {  display: block; color:black; text-align: left; padding: 14px 16px;text-decoration: none;}
        /* Change the link color to #111 (black) on hover */
        table {width: 100%;}
        table {height: 70px;color: black;}
        th, td {padding: 10px;text-align: left;}
        th {background: rgb(209, 149, 90); color:white;}
        nav{font-weight: bold;}

    </style>
</head>
<body>
    <header>
        <img src="./images01/myphoto.jpg" alt="" width="20%">
        <h1>Heejung Lim</h1> <br>
    </header>
</div>
<div id="profile">
    동아대학교 경영정보학과 20학번 임희정 
    <hr color="tan" padding="100px"> 
</div>
<nav>
    <ul class="w3-bar w3-center w3-white ">
        <li class="w3-bar-item w3-button w3-padding-large"><a href="#프로필">profile</a></li>
        <li class="w3-bar-item w3-button w3-padding-large"><a href="#수업">my subject</a></li>
        <li class="w3-bar-item w3-button w3-padding-large"><a href="#좋아하는 노래(동영상)">favorite song</a></li>
        <li class="w3-bar-item w3-button w3-padding-large"><a href="#좋아하는 사진">favorite photo</a></li>
        <li class="w3-bar-item w3-button w3-padding-large"><a href="#좋아하는 동영상">favorite media</a></li>
    </ul>
</nav>   
<hr color="tan" padding="100px"> 
<section class="w3-left w3-container" style="width:70%;">
    <h2> profile</h2>
    <table border="1">
        <tr>
            <th>내용</th>
            <th>일자</th>
        </tr>
        <tr>
            <td>출생</td>
            <td>경상북도 구미시</td>
        </tr>
        <tr>
            <td>17.03~20.2</td>
            <td>구미 형곡고등학교 졸업</td>
        </tr>
        <tr>
            <td>20.3~현재</td>
            <td>부산 동아대학교 재학중</td>
        </tr>
        <tr>
            <td>20.10~21.01</td>
            <td>다우미디어센터 인턴기자 활동</td>
        </tr>
    </table>
    <br>
    <article class="media w3-large w3-text-indigo w3-margin-tops"></article><h2 id="수업"> my subject</h3> 
    <hr id="수업">
    <iframe src="./myinformation.html" frameborder="0" width="65%" height="300px">
        지원되지 않는 브라우저입니다
    </iframe>
    <article class="media w3-large w3-text-indigo w3-margin-tops"></article><h2 id="좋아하는 노래(동영상)"> favorite song</h3> <br>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/7ioGCoB-8DY" title="YouTube video player"
         frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
         allowfullscreen></iframe>
    <article class="media w3-large w3-text-indigo w3-margin-tops"></article><h2 id="좋아하는 사진"> favorite photo</h3> <br>
        <div class="photo" >
            <div class="w3-row">
              <img class="w3-col s3 w3-border w3-margin"  src="./images01/photo1.jpg" alt="사진1" />
              <img class="w3-col s3 w3-border w3-margin" src="./images01/photo2.jpg" alt="사진2" />
              <img class="w3-col s3 w3-border w3-margin" src="./images01/photo3jpg.jpg" alt="사진3" />
            </div>
        </div>
    <article class="media w3-large w3-text-indigo w3-margin-tops"></article><h2 id="좋아하는 동영상"> favorite media</h3> <br>
        <div class="media" width="65%" height="300px" >
            <video class="w3-col s6 w3-border w3-padding-large" width="50%" src="./images01/media2.mp4" autoplay="True" controls="True"></video>
        </div>
</section>

<aside class="right">
    <div class="login">
        <h3 >Log In</h3>
            <form action="#" class="w3-padding-large " > <br>
                            아이디 :<input type="text" name="id"/> <br/> <br>
                            패스워드:<input type="password" name="pass"/> <br /><br />
                <input type="submit" value="로그인" /> &nbsp;
                <input type="reset" value="초기화" /><br /> <br>
                <a href="register.html" target="_blank" id="register">회원가입</a>
                <a href="#" id="forgot">비밀번호분실</a>
            </form>
     </div> <br>
     <div id="aside-list-2" >
    <h4 class="w3-text-indigo ">나의 블로그 글</h4>
        <ul class="text-left">
            <li class="w3-bar-item w3-button w3-padding-small"><a href="https://blog.naver.com/acb4287/222405878480">블로그, 2월부터 6월까지</a></li>
            <li class="w3-bar-item w3-button w3-padding-small"><a href="https://blog.naver.com/acb4287/222247812256">블로그, [노래] Let Me Down Slow, New Hope Club </a></li>
            <li class="w3-bar-item w3-button w3-padding-small "><a href="https://blog.naver.com/acb4287/222207586752">블로그, [노래] everything, 10cm</a></li>
        </ul>
</div>
 </aside>
</div>  
<footer>
    <div class="w3-row">
        <div class="w3-col s4  w3-container" >
            <ul>
                <h5> Contact Us</h5>
              <li>Phone: 010 4030 ****</li> <br>
              
              <i class="glyphicon glyphicon-envelope"></i>
            </ul>
        </div>
        <div class="w3-col s4  w3-container" >
			<h5> Follow Us</h5>
            <li>Email: <a href="mailto:acb4287@naver.com" title="Email Us">acb4287@naver.com</a></li>  
            <li>INSTAGRAM: <a href="https://www.instagram.com/be_winsome_/" title="insta Us">@be_winsome_</a></li>
             <li>Facebook: <a href="https://www.facebook.com/profile.php?id=100009692622373" title="Facebook Us">임희정</a></li>
			<a href="https://www.facebook.com/swhwang64"><i class="fa fa-facebook" style="font-size:30px;color:white"></i></a>
			<a href="https://twitter.com/sense64"><i class="fa fa-twitter" style="font-size:30px;color:white"></i></a>
			<a href="#"><i class="fa fa-instagram" style="font-size:30px;color:white"></i></a>
			<br /><br/>

		</div>
		<div class="w3-col s4 w3-container" >
			<h5> About Us</h5>
			  <a href="#" class="btn btn-block btn-base btn-icon fa-check"><span>Try it now</span></a>
			
		</div>
    </div>
</footer>
<br> <br>
</body>
</html>
