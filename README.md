# tz-6-ESHKEREEEEE
egor noob
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="tz-6.css">
<title>Document</title>
</head>
<body>
<main>
  <styles>
    * {
box-sizing: border-box;
}

body {
font-family: system-ui;
margin: 0;
background-color: #DDD; 
}

input, textarea, button, select { 
    font: inherit;
}
.playground { 
    padding: 20px;
}

.btn {
all: unset;
outline: revert;
padding: 10px;
background-color: white;
position: relative;
}

.btn::before {
content:"";
box-sizing: border-box;
display: inline-block;
background-color: #007409;
width: 10px;
height: 10px;
position: absolute;
bottom: 0;
left: 0;
border-radius: 0 10px 0 0;
}

.btn::after {
content:"";
box-sizing: border-box;
display: inline-block;
background-color: #007409;
width: 10px;
height: 10px;
position: absolute;
top: 0;
right: 0;
border-radius: 0 0 0 10px;
}
<h1>Buttons</h1>
<div class="playground">
<button class="btn">Login</button>
</div>
<div class="playground">
<button class="btn">Register</button>
</div>
</styles>
</main>
</body>
</html>
