<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>

    <style>
      .sw{
        color:blue;
      }
      #smc{
        color:green;
      }
    </style>
    <script>
        function
    </script>
  </head>
  <body>
    <script>
      var food = {
        "breakfast" : "egg"
        "lunch" : "pizza"
        "dinner" : "chicken"
      }
    </script>
    <script>
      for( var in key food ){
        document.write('key'+':'+'key[food]'+'<br>');
      }
    </script>
      <h1><a href="intro.html">장희수의 프로필</a></h1>
    <h3 style="background-color:black; color:white">20819</h3>
    <h4><span class="sw">소프트웨어 1등,</span> <span id="smc">세명컴퓨터고등학교</span></h4>
    <ol>
    <li> <a href="1.html"> 1번째</a></li>
    <li> <a href="2.html"> 2번째</a></li>
    <li> <a href="3.html"> 3번째</a></li>
    </ol>
    <p>4차 산업혁명을 이끌어가는 세명컴퓨터고등학교 게임소프트웨어과 학생 장희수 입니다.</p>
    <input  id="pink_white" type="button" value="pink" onclick="
    document.querySelector('body').style.backgroundColor = 'pink';
    document.querySelector('body').style.color = 'white';
    ">
    <input id="powderblue_white" type="button"  value="powderblue" onclick="
    document.querySelector('body').style.backgroundColor = 'powderblue';
    document.querySelector('body').style.color = 'white';
    ">
    <input type="button" id="change" value="on" onclick="
      var simple=document.querySelector('body');
    if(document.querySelector('#change').value === 'on'){
      simple.style.backgroundColor = 'yellow';
      simple.style.color = 'black';
      document.querySelector('#change').value = 'off';
    }else{
      simple.style.backgroundColor = 'black';
      simple.style.color = 'yellow';
      document.querySelector('#change').value = 'on';
    }
    ">
    <input type="button" id="question" value="email" onclick="
        alert('mistsky09@gmail.com')
        ">
  </body>
</html>
