# Mondrian-Art-by-html-and-css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mondrian Project</title>
    <style>
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 0;
            margin: 0;
            height: 100vh;

        }
        .container{
            width: 748px;
            height: 748px;
            background: #000;
            display: grid;
            gap: 9px;
            grid-template-columns:320px 198px 153px 50px;
            grid-template-rows: 414px 130px 155px 20px;
            

        }
        .item{
            background-color:#f0f1ec;
        }
        .red{
            background-color: red;
        }
        .blue{
            background-color: #004592;
        }
        .yello{
            background-color: yellow;
        }
        .black{
            background-color: black;
        }
        .w1{
            grid-column: span 3;

        }
        .w2{
            grid-row: span 2;
        }
        .w3{
            grid-area: 2/2/4/4;
        }
        .w4{
            grid-row: span 2;
        }
    </style>

</head>
<body>
    <div class="container">
        <div class=" red"></div>
        <div class="item w1"></div>
        <div class="item w2"></div>
        <div class="item w3"></div>
        <div class="blue"></div>
        <div class="item w4"></div>
        <div class="item w5"></div>
        <div class="yello"></div>
        <div class="black"></div>
        
    </div>
    
</body>
</html>
