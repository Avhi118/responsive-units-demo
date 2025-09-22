<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive unit</title>
    <style>
        .percent {width: 20%; background-color: red; padding: 10px;}
        .en {font-size: 20px;}
        .en span {font-size: 2en; color: blue;}
        .ren {font-size: 1.sren; color: greenyellow ;}
        .vw {font-size: 8vw; color: blanchedalmond;}
        .vh {font-size: 35vh; color: aqua;}
        .vs {font-size: 50vs; color: orange;}
        .vmin {font-size: 5vmin; color: black;}
        .ch {width: 25ch;}
        .percent {width: 50%; background-color: skyblue; padding: 20px;}
    </style>
</head>
<body>
    <div class="percent">50% width(percentage)</div>
    <p class="en">This is a default 16px font.
    <span>2en (relative to parent)</span> </p>
    <p class="ren">1.sren (relative to root)</p>
    <h2 class="vw">8vw (viewerport width) </h2>
    <h2 class="vh">35vh (viewerport height) </h2>
    <h2 class="vs">50vs (viewerport strength) </h2>
    <p class="vmin">Sample text with 5min.(small scale)</p>
    <input class="ch" type="text" value="Input box 25ch wide">
    <div class="percent">88% width(percentage)</div>
</body>
</html>
