
<html>
<style>
  
  body {
    background-image: url(http://np.cpami.gov.tw/filesys/image/01_chinese/04_news/201401/0225_2.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;
    background-size: cover;
  }
  
  .blackborder{
    border:2px black solid;
  }
  
  p {
    font-family:"微軟正黑體";
    font-size: 18px;
  }
  
  h1{
    font-family:"微軟正黑體";
    font-weight:bold;
  }
  
  h2{
    font-family:"微軟正黑體";
    font-weight:bold;
  }
  
  td{
    font-family:"微軟正黑體";
    font-size:18px;
  }
  
  .button{
    background-color: #a0fdff;
    border: 2px solid black;
    color: #0645ad;
    padding: 8px 24px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
    display:block;
  }
  
  .button:hover {
    background-color: #A1D0FF;
  }
  
  #flip{
    background-color: #a0fdff;
    border: 2px solid black;
    color: black;
    padding: 8px 42px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
    display:block;
  }
  
  .button-bar {
    position:fixed;
    top: 5%;
    right: 5%;
  }
  * {
        box-sizing: border-box
    }
    
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }
    
    .mySlides {
        display: none
    }
    
    img {
        vertical-align: middle;
    }
    /* Slideshow container */
    
    .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
    }
    /* Next & previous buttons */
    
    .prev,
    .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }
    /* Position the "next button" to the right */
    
    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }
    /* On hover, add a black background color with a little bit see-through */
    
    .prev:hover,
    .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
    }
    /* Caption text */
    
    .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
    }
    /* Number text (1/3 etc) */
    
    .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
    }
    /* The dots/bullets/indicators */
    
    .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }
    
    .active,.dot:hover {
        background-color: #717171;
    }
    /* Fading animation */
    
    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    /* On smaller screens, decrease text size */
    
    @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }

    .tab {
            overflow: hidden;
            border: 1px solid #ccc;
            background-color: #f1f1f1;
        }
        /* Style the buttons inside the tab */
        
        .tab button {
            background-color: inherit;
            float: left;
            border: none;
            outline: none;
            cursor: pointer;
            padding: 14px 16px;
            transition: 0.3s;
            font-size: 17px;
        }
        /* Change background color of buttons on hover */
        
        .tab button:hover {
            background-color: #ddd;
        }
        /* Create an active/current tablink class */
        
        .tab button.active {
            background-color: #ccc;
        }
        /* Style the tab content */
        
        .tabcontent {
            display: none;
            padding: 6px 12px;
            border: 1px solid #ccc;
            border-top: none;
        }

  
</style>

<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
  <script>
    $(document).ready(function() {
      $('#top').click(function () {
        $('html, body').animate({scrollTop: 0},1000);
      });
      $('#bottom').click(function () {
        $('html, body').animate({scrollTop:$(document).height()-$(window).height()}, 1000);
      });
      $('#a').click(function () {
        $('html, body').animate({scrollTop:$("#A").offset().top}, 1000);
      });
      $('#b').click(function () {
        $('html, body').animate({scrollTop:$("#B").offset().top}, 1000);
      });
      $('#c').click(function () {
        $('html, body').animate({scrollTop:$("#C").offset().top}, 1000);
      });
      $('#d').click(function () {
        $('html, body').animate({scrollTop:$("#D").offset().top}, 1000);
      });
      $('#e').click(function () {
        $('html, body').animate({scrollTop:$("#E").offset().top}, 1000);
      });
      $('#f').click(function () {
        $('html, body').animate({scrollTop:$("#F").offset().top}, 1000);
      });
      $("#flip").click(function(){
        $(".button").slideToggle("slow");
      });
    });
  </script>
</head>

<body>
  <div id="google_translate_element"></div>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'zh-tw', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit%22></script>
<h1 style="font-size:40px;text-align:center">東沙環礁國家公園</h1>
<h1 id="A">基本資訊</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
  
<p><b>東沙環礁位在南海北方，環礁外形有如滿月，由造礁珊瑚歷經千萬年建造形成</b>，由於地理、生態特殊，擁有豐富多樣的海洋生物，範圍是以環礁為中心，加上環礁外圍12浬海域為界，<b>海陸域總面積約為353,667.95多公頃。比現有6座國家公園總面積還大</b>，相當臺灣島的十分之一，範圍涵蓋了島嶼、海岸林、潟湖、潮間帶、珊瑚礁、海藻床及大洋等不同但相互依存的生態系統，資源特性有別於臺灣沿岸珊瑚礁生態系，複雜性遠高於陸域生態。</p>

 <p>東沙國家公園成立於2007年1月，位於南海北端，介於香港、臺灣與呂宋島間，為臺灣海峽的南方大門。環礁距離東北方的高雄有240浬，南距南沙太平島640浬，面積廣達8萬多公頃，主要由造礁珊瑚建造而成，東沙島是環礁裡唯一出露海面的陸域。</p>
<div class="tab">
        <button class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen">珊瑚礁生態系</button>
        <button class="tablinks" onclick="openCity(event, 'Paris')">海草床</button>
        <button class="tablinks" onclick="openCity(event, 'Tokyo')">植物</button>
        <button class="tablinks" onclick="openCity(event, 'one')">動物</button>
        <button class="tablinks" onclick="openCity(event, 'two')">相關影音</button>
    </div>

    <div id="London" class="tabcontent">
        <h3><b>珊瑚礁生態系</b></h3>
        <p>東沙環礁以其珊瑚礁生態所著稱，也是南海北部的大型珊瑚礁，且接近珊瑚多樣性的分布熱點- 珊瑚大三角(The Coral Triangle)，故海洋生物多樣性非常豐富。珊瑚適宜生長在23-28℃水質溫暖清澈且陽光充足的海域，全球珊瑚主要分布在南北緯30 度間的熱帶至亞熱帶海域，而東沙環礁正位於此地帶。造礁珊瑚形成珊瑚礁，依形成原因不同，共有裙礁、堡礁及環礁等三種形態，珊瑚礁其生態的形成皆需長久的時間與保育才得以保存，因此近乎正圓形的東沙環礁更顯難得。<br>東沙環礁外環礁珊瑚礁相:開放性海域，水流交換良好、波浪作用力大、水深大、水質清澈、透光度高，平均珊瑚覆蓋率高<br>東沙環礁內潟湖珊瑚礁：內環礁海水交換程度較差，沉積物多且水質混濁，以較能夠忍受濁度的菊珊瑚科、蕈珊瑚科及微孔珊瑚科為主。</p>
    </div>

    <div id="Paris" class="tabcontent">
        <h3><b>海草床</b></h3>
        <p>東沙島周邊海域有全國最大的海草床分布，面積約1,185公頃，是臺灣其他區域海草床加總起來的20倍之多。目前東沙紀錄有7種海草，包括單脈二藥草、圓葉水絲草、鋸齒葉水絲草、水韭菜、鐮葉叢草、泰來草和卵葉鹽草等，不僅提供多樣性海洋生物生活的空間，也是食物鏈中重要的基礎生產者，其年吸收碳量約為一萬公噸。東沙海域紀錄7種（世界海草種數約60種</p>
    </div>

    <div id="Tokyo" class="tabcontent">
        <h3><b>植物</b></h3>
        <p>東沙島的植物的分布類型可分為泛熱帶分布、熱帶舊世界分布及東南亞、西南太平洋諸島分布三種模式。東沙島是熱帶偏北的太平洋島嶼，面積小，氣候深受海洋影響，島上植被屬於熱帶海岸林，和鄰近的西沙群島、南沙群島或是海南島的種類多有相似之處，祇是某些植種的數量和分布有些許差異。主要分為沙灘植群，海岸灌叢與海岸林過度帶植物，海岸林植群，海岸灌叢植群</p>
    </div>

    <div id="one" class="tabcontent">
        <h3><b>動物</b></h3>
        <p>東沙島的面積雖小，棲地的多樣性也不高，但是鳥類的多樣性卻很高，仔細比較可以發現出現的鳥類多數以候鳥為主，許多是不普遍的種類，有些鳥種甚至僅為單隻記錄，但也有部份鳥種（如翻石鷸和金斑行鳥）的群聚數量可達50 隻以上。<br>東沙島是一個由珊瑚砂構成的島嶼，距離最近的大陸也在數百公里以外，加上面積小、較缺淡水來源，島上並無兩棲類動物遷入棲息，爬蟲類也僅有適應性強的小型種類能夠在此生活，目前只有二種爬蟲類棲息島上，分別為蜥蜴類的疣尾蝎虎和眼睛退化的鉤盲蛇</p>
    </div>

    <div id="two" class="tabcontent">
        <h3>相關影音</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/Ze4bAsh-xs0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

    <script>
        function openCity(evt, cityName) {
            var i, tabcontent, tablinks;
            tabcontent = document.getElementsByClassName("tabcontent");
            for (i = 0; i < tabcontent.length; i++) {
                tabcontent[i].style.display = "none";
            }
            tablinks = document.getElementsByClassName("tablinks");
            for (i = 0; i < tablinks.length; i++) {
                tablinks[i].className = tablinks[i].className.replace(" active", "");
            }
            document.getElementById(cityName).style.display = "block";
            evt.currentTarget.className += " active";
        }

        // Get the element with id="defaultOpen" and click on it
        document.getElementById("defaultOpen").click();
    </script>

<div class="slideshow-container">
  
   <div class="mySlides fade" style="display: none;">
        <div class="numbertext">1 / 6</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/publish/desktop/desktop_800x600_01.jpg">
        <div class="text"></div>
   </div>

   <div class="mySlides fade" style="display: none;">
        <div class="numbertext">2 / 6</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/publish/desktop/DSC9465_800x600.jpg">
        <div class="text"></div>
    </div>

   <div class="mySlides fade" style="display: block;">
        <div class="numbertext">3 / 6</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/publish/desktop/desktop_800x600_03.jpg">
        <div class="text"></div>
    </div>
    
   <div class="mySlides fade" style="display: none;">
        <div class="numbertext">4 / 6</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/publish/desktop/DSC4707_1024_768.jpg">
        <div class="text"></div>
    </div>
    
   <div class="mySlides fade" style="display: none;">
        <div class="numbertext">5 / 6</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/publish/desktop/DSC6_1024x768.jpg">
        <div class="text"></div>
    </div>
    
   <div class="mySlides fade" style="display: none;">
        <div class="numbertext">6 / 6</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/publish/desktop/DSC7_1024x768.jpg">
        <div class="text"></div>
    </div>
    
   <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
   <a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>

<br>

<div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
    <span class="dot" onclick="currentSlide(5)"></span>
    <span class="dot" onclick="currentSlide(6)"></span>
</div>


<script>
   var slideIndex = 1;
   showSlides(slideIndex);

   function plusSlides(n) {
        showSlides(slideIndex += n);
    }

   function currentSlide(n) {
        showSlides(slideIndex = n);
    }

   function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if (n > slides.length) {
            slideIndex = 1
        }
        if (n < 1) {
            slideIndex = slides.length
        }
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";
    }
</script>

</div>

<h1 id="B">國家公園標示意涵</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:30px;">
<img style="width: 90px; height: 90px;" src="https://i.imgur.com/3Ionk8I.png" align="left"><p>海洋國家公園管理處處徽以海洋國家公園管理處英文名稱之M為設計元素，運用流暢飄逸之書法韻味筆觸表現海浪波動，象徵海洋生態旺盛生命力，及搭配深淺藍色與白色之對比視覺效果，融合於水墨自由暈開之圖形，呈現海洋資源豐沛之意象。</p>
</div>

<h1 id="C">公園特色介紹</h1>
<h2>一、環礁直徑約25公里</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:40px;">
<p><img class="blackborder" style="width:200px;height:180px;" src="https://www.marine.gov.tw/filesys/image/01_chinese/newimages/0401/40101.jpg" align="left">東沙環礁國家公園境內包括東沙島和環礁。其中的東沙島呈現馬蹄形，常年露出水面，整座島地勢低平，最高處海拔只有7.8公尺，東西長約2,800公尺，寬約865公尺，陸域總面積174公頃，島上覆有貝殼砂，無明顯地形上的遮蔽，有低矮熱帶灌木遍布，島的西側則有兩條沙脊延伸，環抱一個小潟湖，外形很像招潮蟹的大螯，潟湖在退潮時水深不及1公尺。</p><br>
<br><p><img class="blackborder" style="width:200px;height:180px;" src="https://www.marine.gov.tw/filesys/image/01_chinese/newimages/0401/40124.jpg" align="right"><b>東沙環礁為一直徑約25公里的圓形環礁，礁台長約46公里，寬約2公里，海水落潮時，周圍礁台可浮現水面</b>。環礁底部坐落在大陸斜坡水深約300~400公尺的東沙台階上，包含有礁台、潟湖、沙洲、淺灘、水道及島嶼等特殊地形。<b>據推測，東沙環礁的形成需要千萬年的時間，屬世界級的地景景觀</b>。</p>
</div>

<h2>二、桌形、分枝形的軸孔珊瑚是主要造礁物</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:40px;">
<p><img class="blackborder" style="width:180px;height:160px;" src="https://www.marine.gov.tw/filesys/image/01_chinese/newimages/0301/d09104.jpg" align="left">環礁的珊瑚群聚屬於典型的熱帶海域珊瑚，<b>以桌形和分枝形的軸孔珊瑚為主要造礁生物</b>，主要分布在礁脊表面及溝槽兩側，目前紀錄的珊瑚種類有250種，其中14種為新紀錄種，包括藍珊瑚及數種八放珊瑚。</p><br>

<br><p><img class="blackborder" style="width:200px;height:200px;" src="https://www.marine.gov.tw/filesys/image/01_chinese/newimages/0301/d09106.jpg" align="right">廣大的珊瑚礁海域，有著複雜的空間結構，魚種計有556種，其中有許多在臺灣海域未曾紀錄過的魚種，如黃棕美蝦虎魚、鸚哥鯊、史式海龍、稀棘魚尉等。除了豐富多樣的魚群及珊瑚類外，東沙環礁海域內孕育無數五顏六色的無脊椎動物。東沙島孤懸外海，擁有潟湖、海域、和潮間帶等棲息環境，因此成為遷徙性鳥類過境的落腳處，島上也有少數留鳥及冬候鳥，鳥類記錄有130種，主要以鷸科、鷺科及鷗科為主。</p>
</div>

<h2>三、海底沉船約29艘可供考古</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<p>天然資源豐富又位於南海航道上的東沙環礁，自古以來不只漁船絡繹不絕，商船亙是往來頻繁，但此海域附近多灘洲暗礁，且夏季多有颱風侵襲，航海事故迭有傳聞，<b>因此南海也就成為了世界上沉船最為集中的海域之一</b>。據統計，從古至今交錯於東沙環礁附近海域的船舶擱淺或沉沒數計約28艘，因此可以合理地推測東沙環礁海域水下文化資產應該十分豐富，國際上許多海洋考古研究者對之具有高度研究興趣，未來極具國際海洋考古合作研究之潛力。</p>
</div>


<h1 id="D">交通資訊</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;"> 
<p><b>東沙環礁國家公園目前目前係以環境資源保育與復育、深化海洋學術研究為發展目標，尚未開放民眾登島遊憩活動</b>，歡迎您星期一~星期日09:00至12:00，14:00至17:00蒞臨高雄市楠梓區德民路24號(高雄都會公園內)的海洋國家公園管理處解說服務中心 參觀，服務電話：(07)360-1898。</p>
</div>


<h1>資料來源</h1>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<a href="http://np.cpami.gov.tw/%E9%97%9C%E6%96%BC%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92/%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92%E7%B0%A1%E4%BB%8B/293-%E4%B8%AD%E6%96%87/%E5%85%B6%E4%BB%96/%E5%90%84%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92%E4%BB%8B%E7%B4%B9/37-2009-07-07-05-55-36.html">台灣國家公園</a><br>
<a href="https://www.marine.gov.tw/index.php">海洋國家公園管理處</a>
</div>

</body>

<div class="button-bar">
<a id ="flip">選單</a>
<a class="button" id="a" href="#">基本資訊</a>
<a class="button" id="b" href="#">標示意涵</a>
<a class="button" id="c" href="#">特色介紹</a>
<a class="button" id="d" href="#">交通資訊</a>
<a class="button" id="e" href="#">住宿資訊</a>
<a class="button" id="f" href="#">美食資訊</a>
<a class="button" id="top" href="#">網頁頂端</a>
<a class="button" id="bottom" href="#">網頁底部</a>
<a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
</div>

</html>
