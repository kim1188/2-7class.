 # 2-7class
아직 미완성
<html lang="ko">
    <head>
        <title>2학년 7반 시간표</title>
        <meta charset="UTF-8">
        <meta property="og:title" content="2학년 7반 시간표">
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <link href="https://fonts.googleapis.com/css2?family=Nanum+Gothic&display=swap" rel="stylesheet">
        <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
        <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script> 
        <script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
        <style>
            .제목{
                font-family: 'Nanum Gothic', serif;
                font-size:40px
            }
            caption{
                font-family: 'Nanum Gothic', serif;
                font-size:20px
            }
            div{
                font-family: 'Nanum Gothic', serif;
                font-size:18px
            }
            a { text-decoration:none; font-size:18px; }
            a:link { color: black; text-decoration: none;}
            a:visited { color: black; text-decoration: none;}
            a:hover { color:coral; text-decoration: none;}
            table { text-align: center; }
               th, td { border: 1px solid #dadada; }
            body {-ms-user-select: none; -moz-user-select: none; -webkit-user-select: none; -khtml-user-select: none; user-select:none;}
        </style>
    </head>
    <body>
        <center> 
        <h1 class="제목">2학년 7반 시간표</h1>
        <h1 id="clock" style="color:coral; font-family:'Nanum Gothic';">00:00</h1>
        <script>
        var clockTarget = document.getElementById("clock");
        function clock() {
            var date = new Date();
            var day = date.getDay();
            var week = ['일', '월', '화', '수', '목', '금', '토'];
            var hours = date.getHours();
            var minutes = date.getMinutes();
            clockTarget .innerText = `${week[day]}요일 ` + 
            `${hours < 10 ? `0${hours}` : hours}시 : ${minutes < 10 ? `0${minutes }`  : minutes }분`;
            }
        function init() {
        clock();
        setInterval(clock, 1000);
        }
        init();
        </script>
        <div>미완성인 부분 있으니까</div>
        <div>참고해서 수정할 부분 톡으로 전해줘</div>
        <hr>
        <script> AOS.init(); </script>
        <!--------------------------------------------------------------------------------------------------------------------------------------------------------->
        <div data-aos="zoom-in">
          <div>　</div>
          <<<시간표
          <table>
                  <tr>
                    <th></th>
                    <th>월</th>
                    <th>화</th>
                    <th>수</th>
                    <th>목</th>
                    <th>금</th>
                  </tr>
                <tbody>
                  <tr height="80">
                    <th>1</th>
                    <td><a href="https://zoom.us/j/5104395898?pwd=ci9ncHpRTkV6amtvTHVSYzhNK043QT09">영어1(박보라)</a></td><!--영어1(박보라 쌤) 줌 수업-->
                    <td><a href="">문학(박신영)</a></td><!--문학(박신영 쌤) 줌 수업-->
                    <td><a href="https://zoom.us/j/6620251058?pwd=c21Kb2tBdEkyS1JjNnZLWkIvLzBrZz09">기하(신지현)</a></td><!--기하(신지현 쌤) 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/7029964982?pwd=VE83Z25QazYwVE5CZGlZV0xQdFNiZz09">수학1(오혜미)</a></td><!--수학1(오혜미 쌤) 줌 수업-->
                    <td><a href="">수학1(박시영)</a></td><!--수학1(박시영 쌤) 줌 수업-->
                  </tr>
                  <tr height="80">
                    <th>2</th>
                    <td><a href="https://zoom.us/j/6574050599?pwd=OHYxdS9PWUdEaS91Y2h1TXpOZXh6Zz09">생물1</a></td><!--생물1 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/7412490253?pwd=dS9lQVlkazFsaEQ2UFR4cCtxcUxXdz09">기하(김병준)</a></td><!--기하(김병준 쌤) 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/5980025567?pwd=KzVtSm43aTBtN0hpellzd09QcVdYUT09">진로(조현)</a></td><!--진로(조현 쌤) 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/4569059741?pwd=a3Bvc3NXRS80ajMzN2VMajZVUHpPZz09">물리1</a></td><!--물리1 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/3309633175?pwd=ajh5STV4NlNHemNDTjhWbms2SXFqdz09">문학(장준영)</a></td><!--문학(장준영 쌤) 줌 수업-->
                  </tr>
                  <tr height="80">
                    <th>3</th>
                    <td><a href="https://us02web.zoom.us/j/4569059741?pwd=a3Bvc3NXRS80ajMzN2VMajZVUHpPZz09">물리1</a></td><!--물리1 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/7029964982?pwd=VE83Z25QazYwVE5CZGlZV0xQdFNiZz09">수학1(오혜미)</a></td><!--수학1(오혜미 쌤) 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/3309633175?pwd=ajh5STV4NlNHemNDTjhWbms2SXFqdz09">문학(장준영)</a></td><!--문학(장준영 쌤) 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/5655603297?pwd=Sjk3UnhLODVqdVEwTXJRZk5qbXNGdz09">지학1(이승영)</a></td><!--지학1(이승영 쌤) 줌 수업--> 
                    <td><a href="">화학1(김양현)</a></td><!--화학1(김양현 쌤) 줌 수업-->
                  </tr>
                  <tr height="80">
                    <th>4</th>
                    <td><a href="https://us02web.zoom.us/j/3309633175?pwd=ajh5STV4NlNHemNDTjhWbms2SXFqdz09">문학(장준영)</a></td><!--문학(장준영 쌤) 줌 수업--> 
                    <td><a href="https://us04web.zoom.us/j/6231503832?pwd=WmJCeFA1K3Q1emloMzNoZ3MwaEVnQT09">체육</a></td><!--체육 줌 수업--> 
                    <td><a href="https://zoom.us/j/6574050599?pwd=OHYxdS9PWUdEaS91Y2h1TXpOZXh6Zz09">교양(백승혁)</a></td><!--교양(백승혁 쌤) 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/7412490253?pwd=dS9lQVlkazFsaEQ2UFR4cCtxcUxXdz09">기하(김병준)</a></td><!--기하(김병준 쌤) 줌 수업--> 
                    <td><a href="https://zoom.us/j/5104395898?pwd=ci9ncHpRTkV6amtvTHVSYzhNK043QT09">영어1(박보라)</a></td><!--영어1(박보라 쌤) 줌 수업--> 
                  </tr>
                  <tr height="80">
                    <th>5</th>
                    <td><a href="">미술(이지수)</a></td><!--미술창작(이지수 쌤 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/2669056200?pwd=Q3JOQUprR2c0bzRzVkptdmdXTGs4QT09">영어1(조영곤)</a></td><!--영어1(조영곤 쌤) 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/7029964982?pwd=VE83Z25QazYwVE5CZGlZV0xQdFNiZz09">수학1(오혜미)</a></td><!--수학1(오혜미 쌤) 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/2669056200?pwd=Q3JOQUprR2c0bzRzVkptdmdXTGs4QT09">영어1(조영곤)</a></td><!--영어1(조영곤 쌤) 줌 수업--> 
                    <td>　</td>
                  </tr>
                  <tr height="80">
                    <th>6</th>
                    <td><a href="https://us02web.zoom.us/j/4501224672?pwd=U0k2RW5MN0s0WXMxd2JvSWFOdkNXQT09">화학1(이경민)</a></td><!--화학1(이경민 쌤) 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/9167725349?pwd=TW1SdXZSS1p6K2VwZ0lTSFZNY294dz09">미술(황현경)</a></td><!--미술(황현경 쌤) 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/4501224672?pwd=U0k2RW5MN0s0WXMxd2JvSWFOdkNXQT09">화학1(이경민)</a></td><!--화학1(이경민 쌤) 줌 수업--> 
                    <td><a href="https://zoom.us/j/5104395898?pwd=ci9ncHpRTkV6amtvTHVSYzhNK043QT09">특색(박보라)</a></td><!--특색(박보라 쌤) 줌 수업--> 
                    <td>　</td>
                  </tr>
                  <tr height="80">
                    <th>7</th>
                    <td><a href="">진로(강금희)</a></td><!--진로(강금희 쌤) 줌 수업--> 
                    <td><a href="https://us02web.zoom.us/j/5655603297?pwd=Sjk3UnhLODVqdVEwTXJRZk5qbXNGdz09">교양(이승영)</a></td><!--과학교양(이승영 쌤) 줌 수업-->
                    <td><a href="https://us02web.zoom.us/j/5655603297?pwd=Sjk3UnhLODVqdVEwTXJRZk5qbXNGdz09">지학1(이승영)</a></td><!--지학1(이승영 쌤) 줌 수업--> 
                    <td><a href="https://zoom.us/j/6574050599?pwd=OHYxdS9PWUdEaS91Y2h1TXpOZXh6Zz09">생물1</a></td><!--생물1 줌 수업-->
 
                    <td>　</td>
                  </tr>
                </tbody>
          </table>
        </div>
            <br><br>
            <hr><h3>학교 홈페이지</h3>
            <a href="https://hyosung.riroschool.kr/">효성고 리로스쿨</a><!--효성고 리로스쿨-->
            <a href="http://hyosung.hs.kr/index.php">효성고 홈페이지</a><!--효성고-->
            <br><br>
        <image src="시간표.jpg"></image>
        </center>
    </body>
</html>
