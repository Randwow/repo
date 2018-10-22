<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="Стили для блочной вёрстки.css">
</head>

<body>
    <center>
        <p1 class="p1"> Табличная вёрстка </p1>
        <div>
            <table>
                <tr class="hide">
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                </tr>
                <tr>
                    <td rowspan="3" colspan="3">1</td>
                    <td rowspan="3" colspan="3">2</td>
                    <td rowspan="2" colspan="2">5</td>
                    <td rowspan="2" colspan="2">6</td>
                    <td rowspan="2" colspan="2">7</td>
                </tr>
                <tr></tr>
                <tr>
                    <td rowspan="2" colspan="2">8</td>
                    <td rowspan="2" colspan="2">9</td>
                    <td rowspan="2" colspan="2">10</td>
                </tr>
                <tr>
                    <td rowspan="3" colspan="3">3</td>
                    <td rowspan="3" colspan="3">4</td>
                </tr>
                <tr>
                    <td rowspan="2" colspan="2">11</td>
                    <td rowspan="2" colspan="2">12</td>
                    <td rowspan="2" colspan="2">13</td>
                </tr>
            </table>
            <p1 class="p1"> Блочная вёрстка </p1>
    </center>
    </div>
    <br>

    <div class="container">
        <div class="quartet left ">
            <div class="half left cell ">
                <div class="p2">1</div>
            </div>
            <div class="half left cell">
                <div class="p2">2</div>
            </div>
            <div class="half left cell">
                <div class="p2">3</div>
            </div>
            <div class="half left cell">
                <div class="p2">4</div>
            </div>
        </div>
        <div class="quartet left">
            <div class="part left cell">
                <div class="p2">5</div>
            </div>
            <div class="part left cell">
                <div class="p2">6</div>
            </div>
            <div class="part left cell">
                <div class="p2">7</div>
            </div>
            <div class="part left cell">
                <div class="p2">8</div>
            </div>
            <div class="part left cell">
                <div class="p2">9</div>
            </div>
            <div class="part left cell">
                <div class="p2">10</div>
            </div>
            <div class="part left cell">
                <div class="p2">11</div>
            </div>
            <div class="part left cell">
                <div class="p2">12</div>
            </div>
            <div class="part left cell">
                <div class="p2">13</div>
            </div>
        </div>
    </div>
Стили для Блочной вёрстки 

  * {
    box-sizing: border-box;
  }
  body 
  {
  background-color: rgb(22, 193, 236)
  } 
  .container {
  width: 900px;
  height: 450px;
  margin: 0 auto;
  background:#E4E6E7;
  border: 5px solid white;
  }
  .half {
  width: 50%;
  height: 50%;
  }
  .cell {
    border: 3px solid white;
    padding: 0.5rem;
    background-color: #324768;
    color: white;
    text-align: center;
    font-size: 30px;
  } 

    .left {
    float: left;
    }
    .part
    {
    width: 33.33%;
    height: 33.33%;
    }
    .quartet{
    width: 50%;
    height: 100%;
    }
    .p2{  
    height: 100%;
    transform: translateY(calc(100% - 60%));
    }



</body>

</html>