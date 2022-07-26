<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>САХАРОВ</title>
    <style>
        .navbar{
            height: 75px;
            width: 100%;
            background-color: #6C9A33;
            position: sticky;
            top: 0%;
            z-index: 101;
            display: flex;
            justify-content: space-between;
            align-items: center;
            
        }
        .logo img {
            display: flex;
            height: 75px;
            width: 75px;
            padding-left: 7.5%;
        }
        .nav_menu a{
            color: white;
            margin-right: 1em;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.25em;
            margin-right: 1em;
            text-decoration: none;
        }
        body{
            margin: 0;
            overflow-x: hidden;
            background-color: #B85C80;
        }
        h1{
            color: white;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            text-align: center;
            text-justify: center;
            position: relative;
        }
        a{
            display: inline-block;
            padding: 0.75em 0.5em;
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.25em;
            position:relative;
            margin: 10px;
        }
        .photo{
            width: 100vw;
            height: 100vh;
            color: white;
            background-color:#B85C80;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
        }
        .photo::before {
            content: '';
            position: absolute;
            width: 90%;
            height: 5px;
            background-color: white;
            top:10%
        }
        .photo::after{
            content: '';
            position: absolute;
            width: 90%;
            height: 5px;
            background-color: white;
            bottom:10%
        }
        img {
            height: 55vh;
            width: 20vw;
            border-radius: 25px;
            position: relative;
        }
        .about{
            background-color: #933157;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            height: 100vh;
        }
        .about_container{
            display: flex;
            height: 400px;
            width: 300px;
            background-color:#477413;
            flex-direction: column;
            transition: all ease-in .15s;
        }
        .about_container:hover {
            box-shadow: 4px 3px 1px 1px #4C8D00,
                        5px 4px 2px 2px #254800,
                        6px 5px 3px 3px #203B01;
            transform: translate(-6px, -6px);
        }
        .item-1 {
            display: flex;
            height: 100%;
            background-color:#C4E79A;
            margin: 5%;
            justify-content: center;
            align-items: center;
        }
        .item-2 {
            display: flex;
            justify-content: space-around;
            flex-basis: 20%;
            background-color:#94C160;
            margin: 3%
        }
        .info {
            display: flex;
            flex-basis: 40%;
            margin: 5%;
            background-color:#C4E79A;
        }
        .info h1 {
            color: black;
            font-size: .8em;
            margin: 10%;
        }
        .about li{
            color: black;
            font-size: 1em;
            margin: 10%;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif ;
            font-weight: bold;
        }
        .subjects{
            width: 100vw;
            height: 100vh;
            color: white;
            background-color:#6E1236;
            position: relative;
            align-items: center;
            text-align: center;
            justify-content: center;
            text-justify: center;
            justify-items: center;
        }
        .subjects h1{
            color: white;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            margin: 0;
            top: 5%;
        }
        .subjects a {
            color: white;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }
        .menu {
            position: relative;
            top: 100px;
        }
        .menu li {
            background: #ddd;
            border: 3px solid #0d0b02;
            margin-right: 35px;
            margin-top: 150px;
            width: 17.5%;
            height: 5%;
            list-style: none;
            display: inline-block;
        }
        .menu li {
            cursor: pointer;
        }
        .menu a {
            color: white;
            font-weight: bold;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <nav class="logo">
            <img src="Labrador-PNG-Image.png" alt="logo">
        </nav>
        <nav class="nav_menu">
            <a href="#home">Домой</a>
        </nav>
    </nav>
    <h1 id="home">САХАРОВ НИКИТА ДЕНИСОВИЧ</h1> 
    <div class="container">
        <div class="photo">
            <img src="IMG_3637.jpg" alt="Я">
        </div>
        <div class="about">
            <div class="about_container">
                <div class="item-1">
                    <ul class="about_menu">
                        <li>Занимался футболом 100лет</li>
                        <li>FFFFF</li>
                        <li>FFFFF</li>
                        <li>FFFFF</li>

                    </ul>
                </div>
                <div class="item-2">
                    <div class="info">
                        <h1>10 "А" класс</h1>
                    </div>
                    <div class="info">
                        <h1>МБОУ СОШ №5</h1>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="subjects">
        <h1>Предметы</h1>
        <ul class="menu">
            <li><a href="math.html">Математика</a></li>
            <li><a href="#">Русский язык</a></li>
            <li><a href="#">Физика</a></li>
            <li><a href="#">Химия</a></li>
            <li><a href="#">Биология</a></li>
            <li><a href="#">География</a></li>
            <li><a href="#">Физкультура</a></li>
            <li><a href="#">Обж</a></li>
        </ul>
    </div>
</body> 
</html>
