<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <title>מאיר שלמה - טכנולוגיה מתקדמת</title>

    <style>
        body {
            background-image: url('ma1.png');
            color: black;
            font-family: Rubik;
        }
        h1{
            text-align: center;
        }
        p{
            text-align: center;
        }
        .img-1{
            text-align: center;
        }
        
        .כפתור{
            width: 60px;
            height: 60px;
            background-color: rgb(0, 255, 170);
            color: blue;
            border-radius: 30%;
            cursor: pointer;
            transition: transform 1s;
        }
        .כפתור:hover{
            transform: scale(1.8);

        }

        #טקסט{
            display: none;
        
        }
            
            
        
    </style>
</head>

<body>
    <h1>:עליי</h1>
    <p>,היי אני מאיר שלמה <br> אני מתחמה בתחום הטכנולוגיה עצמה כבר הרבה שנים </p>
    <div class="img-1">
        <img src="מאיר/מאיר" alt="שגיאת 401 ">
    </div>
    
    <a href="https://www.youtube.com/"> תלחץ כאן</a>
    <button onclick="הצגטקסט()" class="כפתור">help</button>
    <p id="טקסט">This option will be launched soon!</p>
</body>


<script>
    function הצגטקסט() {
        var טקסט = document.getElementById('טקסט')
        טקסט.style.display = 'block';
    }

        setTimeout(function() {
            טקסט.style.display = 'none'; 
        }, 5000);
</script>

</html> 

האתר שלי
