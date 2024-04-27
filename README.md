# assignment
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
       
    <link rel="stylesheet" href="css/test.css">
    <title>Assignment</title>
</head>

<body>
    <div class="content">
       <div class="div">
        <div class="title-inf">
            <img src="imgaes/logo2.jfif" alt="logo">
            <p>terps calculator inc</p>
            <img src="imgaes/Logo.jpg" alt="logo">
        </div>
    
        <div class="links-inf">
            <a href="https://www.google.com">www.google.com</a>
            <a href="https://www.google.com">www.google.com</a>
            <a href="https://www.google.com">www.google.com</a>
        </div>
        <div class="data-inf">
            <h2>introduction</h2>
            <p><b>terps calculator inc .</b> implements and provide any thing we <br> can use in our life </p>
            <h2>calculator</h2>
            <a href="#">
                <i class="fas fa-calculator"></i>
                grade calculator</a>
            <a href="#">
                <i class="fas fa-calculator"></i>
                insert calculator</a>
        </div>
        <div class="copy-right">
            <p> terps calculator inc &copy</p>
        </div>
       </div>
    </div>
</body>

</html>

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
<css>

body{
    background-image: url(../imgaes/background.jpg);
}
.content{
    width: 60%;
    margin: auto;
    background-color: #fff;
    border-top: 10px solid #a0a19b;
    border-right: 10px solid #ededed;
    border-left: 10px solid #a0a19b;
}
.div{
    border-top: 10px solid #ededed;
    border-right: 10px solid #a0a19b;
    border-left: 10px solid #ededed;
    padding: 25px;
}
.title-inf{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 70%;
    margin: auto;
    text-align: center;
    background-color: #ffb6c1;
    padding: 10px;
    border: 3px solid #a0a19b;
}
.title-inf img{
    width: 80px;
    height: 80px;
}
.title-inf p{
    font-size: 25px;
    margin-top: 60px;
}
.links-inf{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 70%;
    margin: auto;
    margin-top: 20px;
    text-align: center;
    background-color: #ffb6c1;
    padding: 10px;
    border: 3px solid #a0a19b;
}
.links-inf a{
    color: red;
}
.data-inf{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    width: 70%;
    margin: auto;
    margin-top: 20px;
    text-align: left;
    background-color: #ffb6c1;
    padding: 10px;
    line-height: 2;
    border: 3px solid #a0a19b;
}
.data-inf h2{
    text-decoration: underline;
}
.data-inf a{
    color: red;
}
.data-inf i{
    color:#BED7DC ;

}
.copy-right{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 70%;
    margin: auto;
    margin-top: 20px;
    text-align: center;
    background-color: #ffb6c1;
    padding: 10px;
    border: 3px solid #a0a19b;

}
.copy-right p{
    font-size: 15px;
}
