# assignment-04
Muhammad Aizaz Khan CS221065
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="menustyle.css">

<title>main menu</title>
</head>
<body>
<h1><em><b>PRODUCTS:</b></em></h1>
<ol type="A">
<li>FRESH PRODUCTS</li>
<ul type="disc">
<li>BLUEBERRY</li>
<li>CAPSICUM</li>
<li>FENUGREEK</li>
<li>CILANTRO</li>
</ul>
 
<li>SNACK FOODS</li></ol>
<ol type="i">
<li>CHOCO</li>
<ul type="square">
<li>CREPE CHOCLATE WAFERS</li>
<li>CADBURY DAIRY MILK</li>
<li>CRUNCHY OATS & HONEY BAR</li>
<li>KITKAT CRUNCHY</li>
</ul>
<li>SNACKS</li>
<ul type="circle">
<li>CHEEZ-IT</li>
<li>DORITO</li>
<li>POPCORN</li>
</ul>
</ol>
CSS FILE
body{
    background-color: rgb(228, 129, 162);
}

h1{     
    
    text-align-last: center;
    color: rgb(7, 3, 3);
    font-size: 40px;
    text-decoration:double;
}
ol{
    text-decoration: double;
   font-family:Arial, Helvetica, sans-serif;
   font-size: 20px;

}
.container{
    direction: rtl;
    border: 10px solid rgb(51, 167, 123);
    border-radius: 20px;
    height: 800px;
    width: 100%;
    background-image: url("image2.jpg");
    list-style-image:url("image2.jpg");
}
.list{
    border: 10px solid black;
    padding: 30px;
}
ul{
    list-style-position: outside;

}
li{
    font-size: 20px;
    list-style-type:disc;
    
}
