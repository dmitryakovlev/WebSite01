# WebSiteCCOne
Project Coderscamp 01


HTML 

    <!doctype html>
    <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Dmitriy Yakovlev</title>
    <link href="https://fonts.googleapis.com/css?family=Montserrat:700|Raleway:400,500,700" rel="stylesheet">
    <link rel="stylesheet" href="style.css" type="text/css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
<div class="container">

    <div class="photo"></div>
    <div class="info">
        <div class="name">Martyna</div>
        <div class="prof">UX/UI Designer</div>
        <div class="social">
            <a href="#" class="media"> <i class="fa fa-twitter fa-lg"></i> </a>
            <a href="#" class="media"> <i class="fa fa-facebook fa-lg"></i> </a>
            <a href="#" class="media"> <i class="fa fa-github fa-lg"></i> </a>
            <a href="#" class="media"> <i class="fa fa-linkedin fa-lg"></i> </a>
        </div>
    </div>

    <div class="main">
        <div class="about">About <span style="color: #e9514e;">Me</span></div>
        <div class="text">Vestibulum erat tortor, auctor vel purus eu, dapibus faucibus mi. Duis maximus eros id est volutpat tempus. Sed aliquam mi at sagittis posuere. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae. Vivamus tincidunt vel ex quis viverra. In viverra augue ut tempus pharetra.</div>
        <button type="button">DOWNLOAD RESUME</button>
    </div>
    <div class="contacts">
        <ul class="bold">
            <li>Age</li>
            <li>E-mail</li>
            <li>Phone</li>
            <li>Country</li>
        </ul>
        <ul>
            <li>21</li>
            <li>martyna@gmail.com</li>
            <li>+48 577 975 817</li>
            <li>Poland</li>
        </ul>
    </div>
</div>
</body>
</html>



CSS

body {
    margin: 0;
    padding: 0;
    background: url("img/pattern2.jpg") repeat;
    font-family: 'Raleway', sans-serif;
    font-size: 16px;
    font-weight: 400;
    line-height: 24px;
    color: #292929;
}

.container {
    margin: 167px auto 100px;
    width: 1032px;
    height: 586px;
    background: white url("img/header.jpg") no-repeat;
    border-radius: 16px;
    box-shadow: 0 15px 25px rgba(0, 0, 0, 0.1)
}

.photo {
    float: left;
    margin: 48px 0 0 48px;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    width: 280px;
    height: 280px;
    background: url("img/photo.jpg") no-repeat;
    border: white solid 4px;
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.1);
}

.info {
    display: block;
    float: left;
    width: 704px;
    text-align: center;
}

.name {
    margin-top: 112px;
    font-family: 'Montserrat', sans-serif;
    font-size: 54px;
    color: white;
}

.prof {
    font-size: 24px;
    font-weight: 500;
    margin-top: 26px;
    color: white;
}

.social {
    display: flex;
    flex-direction: row;
    justify-content: center;
}

.media {
    margin: 34px 16px 0 0;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    width: 40px;
    height: 40px;
    border: white solid 1px;
    border-radius: 100%;
    -webkit-transition-duration: 0.4s;
    transition-duration: 0.4s;
    cursor: pointer;
}

.media:hover {
    background: rgba(256, 256, 256, 0.3);
}

.media:last-child {
    margin-right: 0;
}

.fa {
    color: white;
    padding-top: 12px;
}

.main {
    clear: both;
    float: left
}

.about {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    font-size: 24px;
    padding: 26px 0 0 48px;
}

.text {
    padding: 10px 0 0 48px;
    color: #666666;
    width: 630px;
}

button {
    margin: 25px 0 0 48px;
    padding: 11px 15px;
    color: #e9514e;
    font-weight: 700;
    font-size: 14px;
    background: white;
    border: #e9514e solid 1px;
    border-radius: 4px;
    font-family: 'Raleway', sans-serif;
    -webkit-transition-duration: 0.4s;
    transition-duration: 0.4s;
    cursor: pointer;
}

button:hover {
    background-color: #e9514e;
    color: white;
}

.contacts {
    display: flex;
    float: left;
    margin: 35px 0 0;
}

.contacts li {
    color: #666666;
    list-style-type: none;
    margin: 9px 0 0;
}

.contacts .bold li {
    font-weight: 700;
    margin-left: 8px;
    color: #292929;
}

ul:last-child {
    margin-left: -22px;
}
