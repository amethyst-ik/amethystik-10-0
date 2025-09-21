# amethystik-10-0
мой 10-ый проэкт

--- html ---


<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>amethystik-10-0</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <form action="" method="get">
        <input name="s" placeholder="Искать здесь..." type="search">
        <button type="submit"></button>
    </form>
</body>
</html>


--- css ---



body {
    background: linear-gradient(to top, #1a002b, #5800b1,#1a002b);
    padding: 60px 0px 0px 0px;
    background-attachment: fixed;
    font-family: arial;
}

* {box-sizing: border-box;}

form {
    text-align: center;
    position: relative;
    width: 500px;
    margin: 0 auto;
}

input {
    width: 100%;
    height: 42px;
    padding-left: 15px;
    border: solid #ffffff00;
    border-radius: 50px;
    outline: none;
    background: #340064;
    color: #ffffff;
    box-shadow: 0px 0px 25px 0px #8400ff;
    transition: all 0.5s  ease;
}

input:hover {
    background-color: #8400ff;
    box-shadow: 0px 0px 25px 5px #8400ff;
}

input::placeholder {
    color: #8400ff;
}

button {
    position: absolute; 
    top: 0;
    right: 0px;
    width: 42px;
    height: 42px;
    border: none;
    background: #8400ff;
    border-radius: 0 50px 50px 0;
    cursor: pointer;
    box-shadow: 0px 0px 25px 0px #8400ff;
}

button:before {
    content: "\f002";
    font-family: FontAwesome;
    font-size: 20px;
    color: #ffffff;
}
