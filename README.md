# sakk.github.io
<!DOCTYPE html>
<html lang="hu">    
<head>
    <link rel="stylesheet" href="stilus.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class-ek Css-el</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300&display=swap" rel="stylesheet">
</head>

<body>
    <h1>Class-ek Css-el</h1>
    <table>
        <tr>
            <td class="black"></td>
            <td class="white"></td>
            <td class="black"></td>

        </tr>
        <tr>
            <td class="white"></td>
            <td class="blue"></td>
            <td class="white"></td>

        </tr>
        <tr>
            <td class="black"></td>
            <td class="white"></td>
            <td class="black"></td>

        </tr>
    </table>
    
</body>
</html>

body{
    background-color: aquamarine;
}
table{
    margin: auto;
}
table, td{
    border: 2px solid black;
    border-collapse: collapse;
}
td{
    width: 200px;
    height: 200px;
}
.black{
    background-color: black;
}
.white{
    background-color: white;
}
.blue{
    background-color: blue;
}
