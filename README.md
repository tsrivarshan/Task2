# Task2
<html>
 <head> 
  <script>
  function myfun1(){
   document.getElementById("G").style.background="red";
 
  }
  function myfun2(){
   document.getElementById("G").style.background="yellow";
  }
  function myfun3(){
   document.getElementById("G").style.background="violet";
  }
 </script> 
 </head> 
 <body> 
  <table border="2" align="center" width="40"> 
   <tbody> 
    <tr> 
     <th id="G" style="font-size:40px" align="center" colspan="3"> HELLO! JAVASCRIPT </th> 
    </tr> 
    <tr> 
     <td text align="center"><button type="button" onclick="myfun1();">Mr.Red</button></td> 
     <td text align="center"><button type="button" onclick="myfun2();"> Mr.Yellow</button></td> 
     <td text align="center"><button type="button" onclick="myfun3();"> Mr.Violet</button></td> 
    </tr> 
   </tbody> 
  </table> 
 </body>
</html>
