<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Mi Trading Platform</title>

<script src="https://unpkg.com/lightweight-charts/dist/lightweight-charts.standalone.production.js"></script>

<style>

body {
    margin:0;
    background:#0b1220;
    color:white;
    font-family:Arial;
}

header {
    padding:15px;
    text-align:center;
    background:#111827;
    font-size:24px;
}

#chart {
    height:500px;
    margin:20px;
}

.panel {
    text-align:center;
}

button {
    padding:12px 30px;
    margin:10px;
    font-size:18px;
    cursor:pointer;
    border-radius:5px;
}

.buy {
    background:green;
    color:white;
}

.sell {
    background:red;
    color:white;
}

</style>

</head>


<body>

<header>
📈 Mi Trading Simulator Pro
</header>


<div id="chart"></div>


<div class="panel">

<button class="buy" onclick="buy()">COMPRAR</button>

<button class="sell" onclick="sell()">VENDER</button>

<h3 id="balance">
Balance: $1000
</h3>

<p id="result"></p>

</div>



<script>


// Crear gráfico
const chart = LightweightCharts.createChart(
document.getElementById('chart'),
{
    layout:{
        background:{color:'#0b1220'},
        textColor:'white'
    },
    grid:{
        vertLines:{color:'#333'},
        horzLines:{color:'#333'}
    }
});


// Crear velas
const candleSeries = chart.addCandlestickSeries();


// Datos iniciales
let candles = [];

let time = Math.floor(Date.now()/1000)-1000;



let price = 100;



for(let i=0;i<50;i++){

let open = price;

let close = open + (Math.random()-0.5)*5;

let high = Math.max(open,close)+2;

let low = Math.min(open,close)-2;


candles.push({

time:time,
open:open,
high:high,
low:low,
close:close

});


price=close;
time+=60;

}


candleSeries.setData(candles);



// Movimiento del mercado

setInterval(()=>{


let last = candles[candles.length-1];


let open = last.close;

let close = open+(Math.random()-0.5)*5;


let candle={

time:time,
open:open,
high:Math.max(open,close)+2,
low:Math.min(open,close)-2,
close:close

};


candles.push(candle);

candleSeries.update(candle);

time+=60;


},2000);




// Balance demo

let balance=1000;


function buy(){

balance+=10;

document.getElementById("balance").innerHTML=
"Balance: $"+balance;

document.getElementById("result").innerHTML=
"Compra realizada";

}



function sell(){

balance-=10;

document.getElementById("balance").innerHTML=
"Balance: $"+balance;

document.getElementById("result").innerHTML=
"Venta realizada";

}


</script>


</body>
</html>
