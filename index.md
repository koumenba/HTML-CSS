<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>欣欣的动画相册</title>
    <style>
        * {
    margin: 0;
    padding: 0;
}
body {
    background-color: #000;
    perspective: 2000px;
    perspective-origin: 50% -100%;
}
img {
    display: block;
    width: 180px;
    height: 180px;
    overflow: hidden;
}
ul {
    position: relative;
    width: 180px;
    height: 320px;
    margin: 160px auto;
    transform-style: preserve-3d;
    animation: rotate 15s linear infinite;
}
@keyframes rotate {
    100% {
        transform: rotateY(360deg);
    }
}
li {
    list-style: none;
    position: absolute;
    top: 0;
    left: 0;
}
ul li:nth-of-type(1) {
     transform: rotateY(40deg) translateZ(-320px);
}
ul li:nth-of-type(2) {
     transform: rotateY(80deg) translateZ(-320px);
}
ul li:nth-of-type(3) {
     transform: rotateY(120deg) translateZ(-320px);
}
ul li:nth-of-type(4) {
     transform: rotateY(160deg) translateZ(-320px);
}
ul li:nth-of-type(5) {
     transform: rotateY(200deg) translateZ(-320px);
}
ul li:nth-of-type(6) {
     transform: rotateY(240deg) translateZ(-320px);
}
ul li:nth-of-type(7) {
     transform: rotateY(280deg) translateZ(-320px);
}
ul li:nth-of-type(8) {
     transform: rotateY(320deg) translateZ(-320px);
}
ul li:nth-of-type(9) {
     transform: rotateY(360deg) translateZ(-320px);
}
</style>
</head>
<body>
    <ul>
        <li>
            <img src="../image/girl1.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl2.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl3.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl4.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl5.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl6.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl7.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl8.jpg" alt="The Piture of A Girl">
        </li>
        <li>
            <img src="../image/girl9.jpg" alt="The Piture of A Girl">
        </li>
    </ul>
</body>
</html>
