<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>第一个网页</title>
<style>
html{
    font-family: monospace;
}
body{
    background-color:gray;
}
body div{
    width:1600px;
    margin:0 auto;
}
div .header1 div:nth-of-type(2) img{
    position:absolute;
    top:0;
    z-index:-1;
}
div .header1 h1,h3,p,span{
    color:white;
    font-family: Century Gothic;
    font-weight:lighter;
}
div .header1 h1{
    font-size:65px;
    text-align: center;
    line-height: 400px;    
}
div .header1 span p{
    position:relative;  
    text-align:center;
    top:-160px;
    font-size:17px;
    letter-spacing:1.5px;
    color:rgba(255,255,255,0.5);
    line-height:1.7;
}
div .header1 div:nth-of-type(1){
    position:relative;  
    border:0.1px solid white;
    width:970px;
    height:250px;
    border-color:rgba(255,255,255,0.4);
    top:-75px;
}
div .header1 div h3{
    font-size:17px;
    letter-spacing:2px;
    text-align: center;
    margin-top:70px;
}
div .header1 div p{
    font-size:12px;
    letter-spacing:3px;
    color:rgba(255,255,255,0.4);
    text-align: center;
    margin-top:-5px;
}
div .header1 div span{
    position:relative;
    display:flex;
    margin:0 auto;
    width:770px;
    top:30px;
    justify-content: space-between;
    
}
div .header1 div span a{
    padding:15px 25px;
    text-decoration: none;
    border:0.1px solid white;
    border-color:rgba(255,255,255,0.4);
    color:rgba(255,255,255,0.5);
}
div .header1 div span a:nth-of-type(1),a:nth-of-type(2){
    padding:15px 80px 15px 20px;
}
div .header1 div span a:hover,div .header1 div span a:focus{
    color:black;
    background-color:white;
}
div .header2{
    position:relative;
    background-color:white;
    top:130px;
    height:710px;
}
.header2 h3,.header2 h2,.header2 div div ul{
    color:black;
    font-family: Century Gothic;
    font-weight:lighter;
}

.header2 h3{
    font-size:18px;
    text-align:center;
    padding-top: 90px;
}
.header2 h2{
    position:relative;
    width:680px;
    font-size:40px;
    text-align:center;
    top:20px;
    margin:0 auto;
}
.header2 div div{
    position:relative;
    top:150px;
    display:flex;
    flex-flow: wrap;
    width:1020px;
    margin:0 auto;
    justify-content: space-between;
}
.header2 div div ul li{
    width:400px;
    list-style-type: none;
}
.header2 div div ul li:first-child{
    line-height:3;
    font-size:20px;
    font-weight:550;
    letter-spacing:1.5px;
}
.header2 div div ul li:nth-of-type(2){
    letter-spacing:1.2px;
}
.header2 div div ul{
    padding-left:65px;
    background-repeat: no-repeat;
    background-position: center left;    
}
.header2 div div ul:nth-of-type(1){
    background-image:url(../3.png);
}
.header2 div div ul:nth-of-type(2){
    background-image:url(../4.png);
}
.header2 div div ul:nth-of-type(3){
    background-image:url(../5.png);
}
.header2 div div ul:nth-of-type(4){
    background-image:url(../6.png);
}




</style>

</head>
    <body>
    <div>
    <div class="header1">
        <h1>Hello World</h2>
        <span><p>China is speeding up strategic plan,shandards,traffic rules.laws and 

regulations<br>on accident-incurred liabilities for its smart car indestry.Economic 

information<br>Daily reported Thursday.</p></span>
        <div>
            <h3>CREATE YOUR ACCOUNT</h3>
            <p>IT IS ABSOLUTELY FREE</p>
            <span>
            <a href="#">denis@getcraftwork.com</a>
            <a href="#">Create your password</a>
            <a href="#">SICN UP</a>
            </span>
        </div>
        <div>
            <img src="../1.png">
            <img src="../2.png">
        </div>
    </div>
    <div class="header2">
        <h3>Boatloads of Awesome</h3>
        <h2>Ready-made, customizable, HTML landing page sections</h2>
        <div>
            <div>
                <ul>
                    <li>Mobile First</li>
                    <li>All modula are built mobile-first for maximum device compatibility.</li>
                </ul>
                <ul>
                    <li>Accessibility</li>
                    <li>Support for IE8, mobile and tablet devices, screenreaders and color blind 

.</li>
                </ul>
                <ul>
                    <li>Fluid Typography</li>
                    <li>On different screen sizes, fonts automagically scale with the viewport.</li>
                </ul>
                <ul>
                    <li>Customization</li>
                    <li>Make any design your own using the Style Editor. Personalize fonts, colors, 

and layouts to create the custom look you want.</li>
                </ul>
            </div>
            
        </div>
    </div>
    </div>
    </body>
</html>
