# punk.io
<!DOCTYPE HTML>
 
<html>
 
  <head>
 
    <meta name="viewport" content="width=320; user-scalable=no" />
 
    <meta http-equiv="Content-type" content="text/html; charset=utf-8">
 
    <title>PhoneGap Android App</title>
 
              <script type="text/javascript" charset="utf-8" src="phonegap.js"></script>       
 
              <script type="text/javascript" charset="utf-8">
 
                        var showMessageBox = function() {
 
                             navigator.notification.alert("Hello World of PhoneGap");
 
                        }
 
                        function init(){
 
                             document.addEventListener("deviceready", showMessageBox, true);               
 
                        }
 
  </script>
 
  </head>
 
  <body onload="init();"  >
 
  </body>
 
</html>
