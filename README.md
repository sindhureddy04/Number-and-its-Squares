# Number-and-its-Squares
Enter number to known the square of it

<html>
  <head>
    <title>Number and its Squares</title>
  </head>
  <body>
    <script type="text/javascript">
      var num=prompt("Enter a number: \n","");
      var msgstr;
      if(numm >0&& num!=null){
        msgstr="Number and its Squares are \n";
        for(i=1;i<=num;i++)
          {
            msgstr=msgstr+i+"^2"+i*i+"\n";
          }
        alert(msgstr);
      }
      else
        alert("Invaild Input");
    </script>
  </body>
</html>
