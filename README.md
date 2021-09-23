<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Surprise🤍🤍</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/b99e675b6e.js"></script>
    <style type="text/css">
        @import url('https://fonts.googleapis.com/css?family=Josefin+Sans&display=swap');
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            list-style: none;
            text-decoration: none;
            font-family: 'Josefin Sans', sans-serif;
        }
        
        body {
            background-color: #fff;
        }
        
        .wrapper {
            display: flex;
            position: relative;
        }
        
        .wrapper .sidebar {
            width: 200px;
            height: 100%;
            background: #4b4276;
            padding: 30px 0px;
            position: fixed;
        }
        
        .wrapper .sidebar h2 {
            color: #fff;
            text-transform: uppercase;
            text-align: center;
            margin-bottom: 30px;
        }
        
        .wrapper .sidebar ul li {
            padding: 15px;
            border-bottom: 1px solid #bdb8d7;
            border-bottom: 1px solid rgba(0, 0, 0, 0.05);
            border-top: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .wrapper .sidebar ul li a {
            color: #bdb8d7;
            display: block;
        }
        
        .wrapper .sidebar ul li a .fas {
            width: 25px;
        }
        
        .wrapper .sidebar ul li:hover {
            background-color: #594f8d;
        }
        
        .wrapper .sidebar ul li:hover a {
            color: #fff;
        }
        
        .wrapper .sidebar .social_media {
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
        }
        
        .wrapper .sidebar .social_media a {
            display: block;
            width: 40px;
            background: #594f8d;
            height: 40px;
            line-height: 45px;
            text-align: center;
            margin: 0 5px;
            color: #bdb8d7;
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
        }
        
        .wrapper .main_content {
            width: 100%;
            margin-left: 200px;
        }
        
        .wrapper .main_content .header {
            padding: 20px;
            background: #fff;
            color: #717171;
            border-bottom: 1px solid #e0e4e8;
        }
        
        .wrapper .main_content .info {
            margin: 20px;
            color: #717171;
            line-height: 25px;
        }
        
        .wrapper .main_content .info div {
            margin-bottom: 20px;
        }
        
        h1 {
            padding: 0 auto;
            margin: all;
            font: 2em verdana, helvetica, sans-serif;
            background-color: #fff;
        }
    </style>
</head>

<body>

    <div class="wrapper">
        <div class="sidebar">
            <h2>MY SOCIAL MEDIA</h2>
            <ul>
                <li><a href="https://www.facebook.com/fikri.walid.10" target="_blank"><i class="fab fa-facebook-f">ACEBOOK</i></a></li>
                <br>
                <li><a href="mailto:walid.fikri20022014@gmail.com"><i class="fab fa-google">MAIL</i></a></li>
                <br>
                <li><a href="https://www.instagram.com/the_voidwalkerrrr" target="_blank"><i class="fab fa-instagram">INSTAGRAM</i></a></li>
                <br>
            </ul>

        </div>
        <div class="main_content">
            <div class="header">
                <font color="#256569">
                    <h1 align="center" style="font-size: 20pt; padding-bottom:30;"><span>WELCOME!! Have a nice day 🥰</span></h1>
                </font>
            </div>
            <div class="info">
                <h2><u><small>Hello this my new website where you can type anything you want🤗</small></u></h2><br>
                <form action="mailto:walid.fikri20022014@gmail.com" method="POST" enctype="text/plain">
                    <textarea name="The message" id="" cols="80" rows="20" value="Your message"></textarea><br>
                    <input type="submit" value="submit ">

                </form>
            </div>
        </div>
    </div>


</body>

</html>
