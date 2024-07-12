# Layout-using-html-and-css
Basic layout using html and css , for the beginners using grid

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    * {
        padding: 0%;
        margin: 0%;
    }

    .wrapper {
        background-color: rgb(255, 255, 255);
        height: 100vh;
        display: grid;
        grid-template-rows: 10% 10% 70% 10%;
        gap: 2px;
        width: 100%;

    }

    .header,
    .footer,
    .menu,

    .content,
    .main,
    .content1 {
        border-style: solid;
        border-color: black;
        text-align: center;
        

    }

    .content_wrapper {
        display: grid;
        grid-template-columns: 20% 60% 20%;
        grid-template-rows: 1fr;
        gap: 2px;

    }
</style>

<body>
    <div class="wrapper">
        <div class="header">header"</div>
        <div class="menu">menu</div>
        <div class="content_wrapper">
            <div class="content">heheh</div>
            <div class="main">main</div>
            <div class="content1">content1</div>
        </div>
        <div class="footer">footer"</div>
    </div>

</body>

</html>
