<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table{
            border: 2px solid black;
            text-align: center;
            width: 300px;
            height: 600px;
            border-collapse: collapse;
        }
        td{
            border: 1px solid black;
        }
    </style>
</head>
    <body>
        <table style="border:1px solid black; text-align: center;">
            <tr>
                <td>1</td>
                <td>2</td>
                <td>3</td>
            </tr>
            <tr>
                <td colspan="2">4</td>
                <td colspan="1">5</td>
            </tr>
            <tr>
                <td>6</td>
                <td>7</td>
                <td>8</td>
            </tr>
            <tr>
                <td rowspan="2">9</td>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>12</td>
                <td>13</td>
            </tr>
            <tr>
                <td>14</td>
                <td>15</td>
                <td rowspan="2">16</td>
            </tr>
            <tr>
                <td colspan="2">17</td>
            </tr>
            <tr>
                <td>18</td>
                <td>19</td>
                <td>20</td>
        </table>        
    </body>
</html>