# Websites
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        #header{
            margin: 1em;
            text-align: center;
        }
        img{
            width: 100%;
            height: 100%;
        }
        #container{
            display: flex;
            align-items: center;
            justify-content: space-evenly;
            gap: 1em;
            flex-wrap: wrap;
        }
        .card{
            box-shadow: 0px 0px 20px #00000042;
            text-align: center;
            max-width: 600px;
        }
        p{
            padding: 0.4em;
        }
        a{
            text-decoration: none;
            color: black;
        }
    </style>

</head>
<body>
    <h1 id="header">Templates 😄</h1>
    <div id="container">
        <!-- First -->
        <a href="First_Template(Descover City)/index.html">
            <div class="card">
                <img src="screenshots/pic1-min.png" alt="">
                <p>Discover City </p>
            </div>
        </a>
        <!-- Second -->

        <a href="Portfolio-template-main/index.html">
            <div class="card">
                <img src="screenshots/pic2-min.png" alt="">
                <p>Portfolio</p>
                
            </div>
        </a>
        <!-- Third -->
        <a href="Template1(Real Istate)/index.html">
            <div class="card">
                <img src="screenshots/pic3-min.png" alt="">
                <p>Real Istate</p>
                
            </div>
        </a>
        <!-- Fourth -->
        <a href="Template2(University)/index.html">
            <div class="card">
                <img src="screenshots/pic4-min.png" alt="">
                <p>University</p>
            </div>
        </a>
    </div>

    
    
    
</body>
</html>
