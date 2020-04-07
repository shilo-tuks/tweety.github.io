<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style style="text/css">
* {box-sizing: border-box;}76

body {
  margin: 0;
  font-family: montserrat, montserrat, montserrat;
}

.topnav {
  overflow: hidden;
  background-color: white;
}

.topnav a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #4682B4;
  color: black;
}

.topnav a.active {
  background-color: white;
  color: white;
}

.topnav .search-container {
  float: right;
}

.topnav input[type=text] {
  padding: 6px;
  margin-top: 8px;
  font-size: 17px;
  border: none;
}

.topnav .search-container button {
  float: right;
  padding: 6px 10px;
  margin-top: 8px;
  margin-right: 16px;
  background: #4682B4;
  font-size: 17px;
  border: none;
  cursor: pointer;
}

.topnav .search-container button:hover {
  background: #4682B4;
}

@media screen and (max-width: 600px) {
  .topnav .search-container {
    float: none;
  }
  .topnav a, .topnav input[type=text], .topnav .search-container button {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .topnav input[type=text] {
    border: 1px solid #ccc;  
  }
}
.scroll-slow {
 height: 50px;	
 overflow: hidden;
 position: relative;
 background: #4682B4;
 bottom: 0px;
 color: white;
 border: 1px solid #008ECC;
}
.scroll-slow p {
 position: absolute;
 width: 100%;
 height: 100%;
 bottom: 0px;
 margin: 0;
 line-height: 50px;
 text-align: center;
 /* Starting position */
 -moz-transform:translateX(100%);
 -webkit-transform:translateX(100%);	
 transform:translateX(100%);
 /* Apply animation to this element */	
 -moz-animation: scroll-left 25s linear infinite;
 -webkit-animation: scroll-left 25s linear infinite;
 animation: scroll-left 25s linear infinite;
}
/* Move it (define the animation) */
@-moz-keyframes scroll-left {
 0%   { -moz-transform: translateX(100%); }
 100% { -moz-transform: translateX(-100%); }
}
@-webkit-keyframes scroll-left {
 0%   { -webkit-transform: translateX(100%); }
 100% { -webkit-transform: translateX(-100%); }
}
@keyframes scroll-left {
 0%   { 
 -moz-transform: translateX(100%); /* Browser bug fix */
 -webkit-transform: translateX(100%); /* Browser bug fix */
 transform: translateX(100%); 		
 }
 100% { 
 -moz-transform: translateX(-100%); /* Browser bug fix */
 -webkit-transform: translateX(-100%); /* Browser bug fix */
 transform: translateX(-100%); 
 }
}
</style>
</style>
</head>
<body>

<div class="topnav">
  <a class="active" href="#home">Home</a>
  <div class="search-container">
    <form action="/action_page.php">
      <input type="text" placeholder="Order No..." name="search">
      <button type="submit"><i class="fa fa-search"></i></button>
    </form>
  </div>
</div>

<div style="padding-left:16px">
  <h2>Order Details</h2>

</div>
 <div class="scroll-slow">
<p>Message as a sum of strings... </p>
</div>

</body>
</html>
