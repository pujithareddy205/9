<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breakpoints</title>
    <style>
        body{
            font-family: 'Courier New', Courier, monospace;
            text-align: center;
            padding: 50px;
            transition: all 0.5s ease;
        }
        h1{
            font-size: 50px;
        }
        p{
            font-size: 20px;
        }
        body{
            background-color: blue;
        }
        @media (max-width: 1199px){
            body{
                background-color: aquamarine;
            }
            h1{font-size: 22px;}
            p{font-size: 10px;}
        }
         @media (max-width: 991px){
            body{
                background-color: lightcoral;
            }
            h1{font-size: 22px;}
            p{font-size: 10px;}
        }
        @media (max-width: 767px){
            body{
                background-color: lawngreen
            }
            h1{font-size: 22px;}
            p{font-size: 10px;}
        }
        @media (max-width: 599px){
            body{
                background-color: lightslategray;
            }
            h1{font-size: 22px;}
            p{font-size: 10px;}
        }
    </style>
</head>
<body>
    <h1>Responsive Breakpoints </h1>
    <p>Resize the window for opening in mobile/tab</p>
</body>
</html>
