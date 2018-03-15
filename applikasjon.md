<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <meta name="description" content="sykkelstativer">  
  <meta name="author" content="David Kong">
  <title>Sykkelstativer | API</title>
  <link rel="stylesheet" href="./css/style.css">
<!--
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Cinzel|Merriweather|Titillium+Web" rel="stylesheet">
-->  
  </head>
<body>
    <div id="result"></div>
    
  <script>
//   var myJSON = '{ [ "id":210, "title":"Birkelunden", "number_of_locks":10, "availability": 7 ], [ "id":191, "title":"Jakob kirke", "number_of_locks": 9 ] }';
   var myJSON = '{ "id":210, "title":"Birkelunden", "number_of_locks":10, "availability": 7 }';
   var myObj = JSON.parse(myJSON)
  
  document.getElementById("demo").innerHTML = myObj.title;


    
</script>



<!--  <script src="myScript.js"></script>-->

</body>
</html>
