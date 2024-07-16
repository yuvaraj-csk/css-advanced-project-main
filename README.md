# CSS ADVANCED PROJECT

## HTML CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simplified Dribbble Clone</title>
    <link rel="stylesheet" href="asserts/style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">Dribbble</div>
            <nav>
                <ul>
                    <li><a href="#">Shots</a></li>
                    <li><a href="#">Designers</a></li>
                    <li><a href="#">Teams</a></li>
                    <li><a href="#">Community</a></li>
                    <li><a href="#">Jobs</a></li>
                </ul>
            </nav>
            <div class="auth-buttons">
                <button class="signup">Sign up</button>
                <button class="signin">Sign in</button>
            </div>
        </div>
    </header>
    <main>
        <div class="search-bar">
            <input type="text" placeholder="">
            <button class="learn-more">Search</button>
        </div>
        <section class="shots">
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbJcstXNq3SRWlo-8a-Pk0flIWjImDyYABPw&s" alt="Shot 1">
                <div class="shot-info">
                    <div class="title">Famous</div>
                    <div class="likes">❤ 4,044</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWaUCDDFZHNElY0YCBM8E720fQ6HbZX9PNMw&s" alt="Shot 2">
                <div class="shot-info">
                    <div class="title">Balkan Brothers</div>
                    <div class="likes">❤ 2,404</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXQ3y7-2hnwaAGxlPItrGbpHmwmJ8hR65Mvw&s" alt="Shot 3">
                <div class="shot-info">
                    <div class="title">Jan Losert</div>
                    <div class="likes">❤ 3,985</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://mir-s3-cdn-cf.behance.net/projects/404/818ef171213987.Y3JvcCwyMjQ1LDE3NTYsMCww.png" alt="Shot 4">
                <div class="shot-info">
                    <div class="title">Mattias Johansson</div>
                    <div class="likes">❤ 2,602</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://media.licdn.com/dms/image/D4D05AQFjBjPwpRHwRA/videocover-high/0/1711546069701?e=2147483647&v=beta&t=1tsEUHQUOYN9x1SLVL42FvujeiskYdGIDX_aHa537DA" alt="Shot 5">
                <div class="shot-info">
                    <div class="title">Ruslan Siiz</div>
                    <div class="likes">❤ 2,369</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/85900e57255643.59ce60fd4ef78.png" alt="Shot 6">
                <div class="shot-info">
                    <div class="title">Paperpillar</div>
                    <div class="likes">❤ 1,022</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://cdn.shopify.com/s/files/1/0558/6413/1764/files/Rewrite_Logo_Design_Basics_That_Designers_Must_Follow_0_1024x1024.jpg?v=1700191437" alt="Shot 7">
                <div class="shot-info">
                    <div class="title">lucas fields</div>
                    <div class="likes">❤ 5,414</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqL4r8ncF7Z17GHyI2-b3Xu6TmOj92P5kBUQ&s" alt="Shot 8">
                <div class="shot-info">
                    <div class="title">Hallo Lab</div>
                    <div class="likes">❤ 4,237</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbo35ode5qwf9ZFgJ8ptMoUC0AwHL-ZjjY6Q&s" alt="Shot 9">
                <div class="shot-info">
                    <div class="title">Rv Studio</div>
                    <div class="likes">❤ 1,845</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://cdn.dribbble.com/userupload/8738247/file/original-7c3297d43948e3b66fa91070b0a6de0b.png?resize=752x" alt="Shot 10">
                <div class="shot-info">
                    <div class="title">nixtio</div>
                    <div class="likes">❤ 7,175</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://images-na.ssl-images-amazon.com/images/I/41UftldeKhL._SL500_._AC_SL500_.jpg" alt="Shot 11">
                <div class="shot-info">
                    <div class="title">Lain</div>
                    <div class="likes">❤ 4,272</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQW4WflhOOvMDmDFo5wOT7CzQ-6v0qsoJafHg&s" alt="Shot 12">
                <div class="shot-info">
                    <div class="title">Stevan Rodic</div>
                    <div class="likes">❤ 4,527</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://mir-s3-cdn-cf.behance.net/projects/404/59e808167390485.Y3JvcCwzODM1LDMwMDAsOTQsMA.png" alt="Shot 13">
                <div class="shot-info">
                    <div class="title">Coric Design</div>
                    <div class="likes">❤ 7,327</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTnnV5MguiBtS6fE2nIWu7X4Fvyzz_wtmDGww&s" alt="Shot 14">
                <div class="shot-info">
                    <div class="title">Vedant Hedge</div>
                    <div class="likes">❤ 5,275</div>
                </div>
            </div>
            <div class="shot">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTmYLyczGP-fPnyAwnTRRyiJhGRxVGc9FVNLQ&s" alt="Shot 15">
                <div class="shot-info">
                    <div class="title">Alexandra Zutto</div>
                    <div class="likes">❤ 2,545</div>
                </div>
            </div>
                </div>
            </div>
        </section>
    </main>
</body>
</html>
```
## CSS CODE
```
/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    max-width: 1200px;
    margin: auto;
}

header {
    background-color: #333;
    color: white;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    position: relative;
}

nav ul li a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    background: #ea4c89;
    left: 0;
    bottom: -5px;
    transition: width 0.3s;
}

nav ul li a:hover::after {
    width: 100%;
}

.auth-buttons button {
    margin-left: 10px;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    transition: background 0.3s;
}

.auth-buttons .signup {
    background-color: #ea4c89;
    color: white;
}

.auth-buttons .signin {
    background-color: #fff;
    color: #322626;
}

.auth-buttons .signup:hover {
    background-color: #d43d72;
}

.auth-buttons .signin:hover {
    background-color: #f1f1f1;
}

main {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

.search-bar {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}

.search-bar input {
    width: 300px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px 0 0 5px;
    outline: none;
}

.search-bar button.learn-more {
    padding: 10px 20px;
    background-color: #ea4c89;
    border: none;
    color: white;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
    transition: background 0.3s;
}

.search-bar button.learn-more:hover {
    background-color: #d43d72;
}

.shots {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
}

.shot {
    background-color: white;
    padding: 10px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.shot:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
}

.shot img {
    width: 100%;
    border-radius: 10px;
}

.shot-info {
    display: flex;
    justify-content: space-between;
    margin-top: 10px;
}

.title {
    font-size: 16px;
    font-weight: bold;
}

.likes {
    font-size: 14px;
    color: #ea4c89;
}
```
## OUTPUT
![Dribbbleoutput](https://github.com/user-attachments/assets/4c8c4d0d-a8e6-4c49-9c07-b452d305f5d6)
