# Precedencia de operadores

<table style='width:100%'>
    <tr>
        <th>NIVEL</th>
        <th>OPERADOR</th>
        <th>DESCRIPCIÓN</th>
        <th>ASOCIATIVIDAD</th>
    </tr>
    <tr>
        <td rowspan="4" style='text-align: center;'>15</td>
        <td>()</td>
        <td>parentesis, llamada de función</td>
        <td rowspan='4' style='text-align: center;'>Izquierda a derecha</td>
    </tr>
    <tr>
        <td>[]</td>
        <td>asignación de arreglos</td>
    </tr>
    <tr>
        <td>.</td>
        <td>acceso a propiedades de objetos</td>
    </tr>
    <tr>
        <td>new</td>
        <td>asignación de memoria</td>
    </tr>
    <tr>
        <td rowspan="6" style='text-align: center;'>14</td>
        <td>++  --</td>
        <td>incremento y decremento</td>
        <td rowspan='6' style='text-align: center;'>Derecha a izquierda</td>
    </tr>
    <tr>
        <td>+ -</td>
        <td>más y menos unarios/td>
    </tr>
    <tr>
        <td>! ~</td>
        <td>negación y complemento</td>
    </tr>
    <tr>
        <td>delete</td>
        <td>desasignación de memoria</td>
    </tr>
    <tr>
        <td>typeof</td>
        <td>función para encontrar el tipo de variable</td>
    </tr>
    <tr>
        <td>void</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="3" style='text-align: center;'>13</td>
        <td>*</td>
        <td>multiplicación</td>
        <td rowspan='3' style='text-align: center;'>Izquierda a derecha</td>
    </tr>
    <tr>
        <td>/</td>
        <td>división</td>
    </tr>
    <tr>
        <td>%</td>
        <td>módulo</td>
    </tr>
    <tr>
        <td style='text-align: center;'>12</td>
        <td>+ -</td>
        <td>suma y resta</td>
        <td style='text-align: center;'>Izquierda a derecha</td>
    </tr>
    <tr>
        <td rowspan="2" style='text-align: center;'>11</td>
        <td>>></td>
        <td>corrimiento a la derecha</td>
        <td rowspan='2' style='text-align: center;'>Izquierda a derecha</td>
    </tr>
    <tr>
        <td><<</td>
        <td>corrimiento a la izquierda</td>
    </tr>
    <tr>
        <td rowspan="2" style='text-align: center;'>10</td>
        <td>< <=</td>
        <td>relacional menor y menor o igual</td>
        <td rowspan='2' style='text-align: center;'>Izquierda a derecha</td>
    </tr>
    <tr>
        <td>> >=</td>
        <td>relacional mayor y mayor o igual</td>
    </tr>
    <tr>
        <td rowspan="4" style='text-align: center;'>9</td>
        <td>==</td>
        <td>igualdad</td>
        <td rowspan='4' style='text-align: center;'>Izquierda a derecha</td>
    </tr>
    <tr>
        <td>!=</td>
        <td>desigualdad</td>
    </tr>
    <tr>
        <td>===</td>
        <td>operador de identidad</td>    
    </tr>
    <tr>
        <td>!==</td>
        <td>operador de no identidad</td>
    </tr>

</table>

<!-- #TODO: insertar imagen tabla de precendencia  -->