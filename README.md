<!DOCTYPE html>
<html>
<head>
<style>
  @keyframes fiery {
    0%{color:red;}
    25%{color:orange;}
    50%{color:yellow;}
    75%{color:orange;}
    100%{color:red;}
  }
  h1{
    font-size: 60px;
    text-align: center;
    animation-name: fiery;
    animation-duration:2s;
    animation-iteration-count: infinite;
  }
body {
  margin: 0;
  overflow: hidden;
}

#image {
  position: absolute;
  width: 100%;
  height: 100%;
  background:url(headphone.jpg);
  background-size: cover;
  animation: fadeIn ease 3s;
}

@keyframes fadeIn { 
  0% {opacity:0;}
  100% {opacity:1;}
}
@keyframes {
  100%{opacity:1;}
  0%{opcacity:0 ;}
}

#left, #right {
  width: 100%;
  height: 100%;
  background: url('file:///C:/Users/Students/Desktop/Improved%20website/logolib.jpg') no-repeat center center fixed; 
  background-size: cover;
  transition: all 2s;
}

#left {
  left: 1;
}

#right {
  right: 1;
}

body.animate #left {
  transform: translateX(-100%);
}

body.animate #right {
  transform: translateX(-100%);
}

/* Add this block for text animation */
.text-animation {
    font-size:30px;
    color:white;
    position:absolute;
    top:50%;
    left:50%;
    size:60%;
    transform:translate(-50%, -50%);
    animation: fieryTextAnimation 3s; /* Add fieryTextAnimation here */
    animation-delay:2s; 
}

}


@keyframes fieryTextAnimation {
    0% {color:red;}
    25% {color:orange;}
    50% {color:yellow;}
    75% {color:red;}
    100% {color:red;}
}
</style>
</head>
<body>

<div id="image">
  
<!-- Add this line for text animation -->
<div class="text-animation"><h1>PortSide Rhythms</h1></div>

<div id="left"></div>
<div id="right"></div>
</div>

<script>
setTimeout(function() {
    document.body.className = 'animate';
    setTimeout(function() {
        window.location.href = 'file:///C:/Users/Students/Desktop/ORG%20Website/Improved%20website/WEBSITEORGINAL.html'; // Redirect to the next page
    }, 2000); // Redirect after the animation ends
}, 5000); // Start animation after 5 seconds
</script>

</body>
</html>
<html>
<head>
<style>
@import url('https://fonts.googleapis.com/css?family=Orbitron');
h1{
  font-family: 'Orbitron', sans-serif;
  font size:60px;
  color: white;
  text-align: center;
  text-shadow:  0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000, 0 0 50px #ff0000, 0 0 60px #ff0000, 0 0 70px #ff0000, 0 0 80px #ff0000;
  animation:fire 2s infinite;  
}
@keyframes fire {
    from {text-shadow: 0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000, 0 0 50px #ff0000, 0 0 60px #ff0000, 0 0 70px #ff0000, 0 0 80px #ff0000;}
    to {text-shadow: -10px -10px 20px #ff0000, -10px -10px 30px #ff0000, -10px -10px 40px #ff0000, -10px -10px 50px #ff0000, -10px -10px 60px #ff0000, -10px -10px70px #ff0000, -10px -10px80px #ff0000;}
</style>
</head>
</html>
<body>
  
  </body>



