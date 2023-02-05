<html>
    <head>
          
<style>
    *{
    margin: 0;
    padding: 0;
}

.logo{
    color: chocolate;
    font-size: 0.5cm;
    padding: 25px 25px;
}

.logo2{
    font-size: 2.75cm;
    color: black;
    padding-top: 150px;
    padding-left: 550px;
}

.logo3{
    font-size: 2.75cm;
    color: cyan;
    padding-top: 0px;
    padding-left: 550px;
}

ul {
    
    margin-right: 20px;
    float: right;
    position: relative;
    list-style: none;
    background-color: white;
    border: 1px;
}

ul li{
    
    margin-top: 10px;
    margin-bottom: 0px;
    display: inline-block;
    padding-left: 10px;
    position: relative;
    border: 10px 10px solid burlywood;
}

ul li a{
    background: #262626;
    width: 120px;
    border: 1px solid #fff;
    height: 50px;
    line-height: 50px;
    display: block;
    color:white;
    text-decoration: none;
    text-align: center;
    font-size: 20px;
   
}


ul ul li {
    background: #262626;
    width: 100px;
    border: 1px solid #fff;
    height: 50px;
    line-height: 50px;
    width: 120px;;
    text-align: left;
    font-size: 20px;
}


ul li ul.drop li{
    display: block;
}

ul li ul.drop {
    width: 100%;
    background-color: #22438C;
    position: absolute;
    z-index: 999;
    display: none;
}

ul li a:hover{
    background-color: blueviolet;
    color: white;
}

ul li:hover ul.drop{
    background-color:white;
    color: white;
    display: block;
}

ul ul.drop li:hover{
    background-color: blueviolet;
    color: white;
}
</style>

    </head>
    <body>
        <ul>
            <li><a href="#">HOME</a></li>
            <li>
                <a href="#">FURNITURE</a>
                <ul class="drop">
                    <li>SOFA</li>
                    <li>TV UNIT</li>
                    <li>BED</li>
                </ul>
            </li>
            <li>
                <a href="#">INTERIOR</a>
            <ul class="drop">
                <li>WALL</li>
            </ul>
            
            </li>
            <li>
                <a href="#">CONTACT</a>
            <ul class="drop">
                <li>9723398249</li>
            </ul>
            </li>
            <li>
                <a href="#">HELP</a>
            <ul class="drop"> 
                <li>CHAT</li>
                <li>CALL</li>
            </ul>
            </li>
        </ul>
    </body>
    <body>
        <div class="logo">KUNJ DESIGN ™</div>
    </body>
    <body>
        <div class="logo2">KUNJ</div>
    </body>
    <body>
        <div class="logo3">DESIGN</div>
        
    </body>
</html>
