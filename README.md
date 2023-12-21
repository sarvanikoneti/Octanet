# Octanet
# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="main">
    <div class="navbar">
        <div class="icon">
            <h2 class="logo">JAI JAWAN</h2>
        </div>
        <div class="menu">
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">SERVICE</a></li>
                <li><a href="#">CONTACT</a></li>

            </ul>
        </div>
        <div class="search">
            <input class="srch" type="search" name="" placeholder="Type to text">
            <a href="#"> <button class="btn">Search</button></a>
        </div>
    </div>
    <div class="content">
        <h1>Eternal<br><span>JAWAN</span> <br></h1>
        <p class="par"> In the heart of adversity, the Eternal Jawan rises, an unyielding symbol of courage and honor. <br>
            In the selfless commitment of the Jawan, sacrifice<br>
             becomes a silent anthem, echoing with unwavering determination<br>
             and a profound sense of duty. Each step forward is a relinquishment<br>
             of personal comfort, a testament to the heroism that transcends the<br>
             ordinary, embodying the essence of unwavering dedication to safeguard the nation.<p>
             <button class="cn"><a href="#">JOIN US</a></button>
        <div class="form">
            <h2>Login Here</h2>
            <input type="email" name="email" placeholder="Enter Email Here">
            <input type="password" name="" placeholder="Enter password Here">
            <button class="btnn"><a href="#"></a>Login</button>

            <p class="link">Don't have an account<br>
            <a href="#">Sign up</a> here</a></p>
            <p class="liw">log in with</p>
            <div class="icons">
                <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                <a href="#"><ion-icon name="logo-linkedin"></ion-icon></a>
                <a href="#"><ion-icon name="logo-google"></ion-icon></a>
                <a href="#"><ion-icon name="logo-facebook"></ion-icon></ion-icon></a>
            </div>
         </div>
            </div>
         </div>   
    </div>
</div>   
<script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
</body>
</html>

# style.css
*{
    margin: 0;
    padding: 0;
}
.main{
    width: 100%;
    background: linear-gradient(to top, rgba(0,0,0,0.5)50%, rgba(0,0,0,0.5)50%), url(vijayawada.png);
    background-position: center;
    background-size: cover;
    height: 109vh;
}
.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}
.icon{
    width: 200px;
    float: left;
    height: 70px;

}
.logo{
    color: rgb(47, 137, 202);
    font-size: 40px;
    font-family: Lucida Sans;
    padding-left: 10px;
    float: left;
    padding-top: 10px;
}
.menu{
    width: 400px;
    float: left;
    height: 70px;
}
ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}
ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
    
}
ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
} 
ul li a:hover{
    color: rgb(39, 115, 166);
} 
.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}
.srch{
    font-family: Lucida sans;
    width: 200px;
    height: 20px;
    background: transparent;
    border: 1px solid #fff;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-right-radius: 5px;
    border-top-left-radius: 5px;

}
.btn{
    width: 100px;
    height: 40px;
    background: rgb(39, 132, 166);
    border: 2px solid rgb(47, 148, 202);
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
}
.btn:focus{
    outline: none;

}
.srch:focus{
    outline: none;

}
.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color: #fff;
    position: relative;
}
.content .par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: 'Lucida Sans Regular';
    letter-spacing: 1.2px;
    line-height: 30px;   
}
.content h1{
    font-family: 'Gill sans';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;

}
.content .cn{
    width: 160px;
    height: 40px;
    background: rgb(47, 143, 202);
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
}
.content .cn a{
    text-decoration: none;
    color: black;
    transition: .3s ease;

}
.cn:hover{
    background-color: #fff;
}
.content span{
    color: rgb(47, 114, 202);
    font-size: 65px;
}
.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%, rgba(0,0,0,0.8)50%);
    position: absolute;
    top: -20px;
    left: 870px;
    border-radius: 10px;
    padding: 25px;
}
.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: rgb(47, 140, 202);
    font-size: 22px;
    background-color: #fff;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}
.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid rgb(47, 114, 202);
    border-top: none;
    border-right: none;
    border-left: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;

}

.form input:focus{
    outline: none;
}
::placeholder{
    color: #fff;
    font-family: 'Lucida Sans Unicode';
}
.btnn{
    width: 240px;
    height: 40px;
    background: rgb(47, 135, 202);
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: #fff;
    transition: 0.4s ease;

}
.btnn:hover{
    background: #fff;
    color: rgb(47, 135, 202);

}
.btnn a{
    text-decoration: none;
    color: black;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color: rgb(47, 161, 202);
}
.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
.icons a{
    text-decoration: none;
    color: #fff;
}
.icons ion-icon{
    color:#fff;
    font-size: 30px;
    padding-left: 14px;
    padding-top: 5px;
    transition: 0.3s ease;
}
.icons ion-icon:hover{
    color: rgb(47, 158, 202);
}
# end
