# Pixel-Art-Maker-<!DOCTYPE html>
<html>
    <head>
        <title>Pixel Art Maker</title>
        <metacharset="utf-8">
        <lang="en">
        <link rel="stylesheet" href="PixelArtMaker.css">
        <link href="Project_Javascript_jQuery.css">
        <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Monoton">
        <script id="ud-grader-options">UdacityFEGradingEngine.turnOn();</script>
    </head>
    <body>
        <header  id="header" class="header">
            <h1>Lab: Pixel Art Maker</h1>
        </header> 
        <nav id="navbar"></nav>       
        <main id="main" class="main">  
            <h2>Choose Grid Size</h2>
            <form id="sizePicker" class="sizePicker"> 
                <label>Grid Height:(1-18)</label>
                <input class="input" type="number"  id="heightGrid" min="1" max="18" value="1"></input>  
                <label id="secondLabel">Grid Width:(1-18)</label>
                <input type="number" class="input"  id="widthGrid" min="1" max="18" value="1"></input>
                <input onclick ="makeGrid()" type="submit" id="submitButton" class="newGrid" value="Submit" >
                <input id="reset" type="button" value="Reset" class="newGrid" >
            </form>
            <h2>Pick A Color</h2>
                <input type="color" id="colorPicker" class="colorPicker">
        </main>  
            <h2>Design Canvas</h2> 
            <div id="canvas">      
            <table id="pixelCanvas" class="pixelCanvas"></table>
        </div>
        </div>
        <footer id="footer"></footer>
        <script src="PixelArtMaker.js"></script>
    </body>
</html>
