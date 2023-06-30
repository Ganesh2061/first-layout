# first-layout<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>layout</title>
    <style>
      *{
        margin:0px;
        padding:0px;
        box-sizing: border-box;
        font-family: Arial, Helvetica, sans-serif;


      }
      #logo-div{
        width:100%;
        min-height: 50px;
        background-color: lightgray;
        padding-left:2%;
        line-height:50px;
        margin-bottom: 10px;
      }
      
      #nav{
        width:100%;
        min-height: 30px;
        background-color: lightgray;
        text-align: center;
        line-height: 30px;
        margin-bottom: 10px;
      }
      #header{
        width:100%;
        min-height:80px;
        background-color: lightgray;
        text-align: center;
        line-height: 80px;
        margin-bottom: 20px;

      }
      
      #sidebar{
      width:20%;
      min-height:400px;
      background-color: lightgray;
      float: left;

      }
      #parent{
        width:100%;
        min-height:400px;
        margin-bottom: 10px;

      }
      #bodyarea{
        width: 75%;
        background-color: lightgray;
        min-height:400px;
        float:right;

      }
      .clearfix::after{
      content:"";
      display: block;
      clear:both;
      }
      #footer{
        width:100%;
       min-height:50px;
       background-color: lightgray;
       text-align: center;
       line-height: 50px;
      }
    </style>
    
</head>
<body>
 <div>
<div id="logo-div">logo</div>
 
<div id="nav">navigation</div>

<div id="header">header/banner</div>

<div id="parent" class ="clearfix">
<div id="sidebar">side bar</div>

<div id="bodyarea">bodyarea</div>

</div>
<div id="footer">footer</div>
</div>
</body>
</html>
