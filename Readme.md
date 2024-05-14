<html lang="es">
<head>
<html lang="es">
<head>
<script>
        function actualizarCantidad(numeroFila) {
            var nuevaCantidad = prompt("Ingrese la nueva cantidad:");
            if (nuevaCantidad !== null && !isNaN(nuevaCantidad) && nuevaCantidad !== "") {
                document.getElementById('cantidad' + numeroFila).textContent = nuevaCantidad;
            } else {
                alert("Por favor, ingrese un número válido para la cantidad.");
            }
        }
    </script>
</head>
<body>
<h2>Material Branding</h2>
<table>
  <thead>
    <tr>
      <th>Referencia</th>
      <th>Descripción Artículo</th>
      <th>Cantidad</th>
      <th>Foto</th>
      <th>Actualizar Cantidad</th>
 </tr>
  </thead>
  <tbody>
  <tr><h3>TENSABARRIERS</h3></tr> 
  <td>300000173</td>
      <td>PORTACARTELES TENSABARRIER DINA3</td>
     <td id="cantidad1">10</td>
<td><button onclick="window.open"><a href="Fotos/B1.JPG" target="_blank">B1</a></button></td>
<td><button onclick="actualizarCantidad(1)">Actualizar</button></td>
    <tr>
      <td>300000174</td>
      <td>PORTACARTELES TENSABARRIER DINA4</td>
      <td id="cantidad2">1</td>
     <td><button onclick="window.open"><a href="Fotos/B3.JPG" target="_blank">B3</a></button></td>
     <td><button onclick="actualizarCantidad(2)">Actualizar</button></td>
</tr>
    <tr>
        <td>000000000030000076.2</td>
        <td>TENSABARRIERS AMARILLOS</td>
        <td id="cantidad3">131</td>
      <td><button onclick="window.open"><a href="Fotos/B4.JPG" target="_blank">B4</a></button></td>
    <td><button onclick="actualizarCantidad(3)">Actualizar</button></td>
</tr>
    <tr>
        <td>000000000030000076.3</td>
        <td>TENSABARRIERS AMARILLOS NUEVOS (USADOS)</td>
        <td id="cantidad4">93</td>
        <td><button onclick="window.open"><a href="Fotos/B5.JPG" target="_blank">B5</a></button></td>
   <td><button onclick="actualizarCantidad(4)">Actualizar</button></td> 
</tr>
    <tr>
        <td>VY202</td>
        <td>MATERIAL PARA DESTRUIR (TENSABARRIER Y MEDIDOR)</td>
     <td id="cantidad5">51</td>
<td></td>
        <td><button onclick="actualizarCantidad(5)">Actualizar</button></td>
    </tr>
    <tr>
        <td>VYTENSA21</td>
        <td>TENSABARRIERPARA RECICLAR</td>
<td id="cantidad6">26</td>
        <td><button onclick="window.open"><a href="Fotos/B6.JPG" target="_blank">B6</a></button></td>
<td><button onclick="actualizarCantidad(6)">Actualizar</button></td>
    </tr>
    <tr>
        <td>VYTENSA22</td>
        <td>TENSABARRIERS RECICLADOS (PINTADOS)</td>
<td id="cantidad7">7</td>
        <td><button onclick="window.open"><a href="Fotos/B7.JPG" target="_blank">B7</a></button></td>
<td><button onclick="actualizarCantidad(7)">Actualizar</button></td>    
</tr>
<table>
  <h3>TOTEMS</h3>
<tr>
    <th>Referencia</th>
    <th>Descripción Artículo</th>
    <th>Cantidad</th>
    <th>Foto</th>
    <th>Actualizar Cantidad</th>
</tr>
<tr>
<td>000000000030000039B.39B</td>
      <td>TOTEM PARA VINILAR</td>
<td id="cantidad8">3</td> 
     <td><button onclick="window.open"> <a href="Fotos/A11.JPG" target="_blank">A11</a> </button></td>
  <td><button onclick="actualizarCantidad(8)">Actualizar</button></td>
</tr>
    <tr>
      <td>000000000030000051.1</td>
      <td>TOTEM BAG DROP</td>
<td id="cantidad9">6</td>
      <td><button onclick="window.open"><a href="Fotos/A12.JPG" target="_blank">A12</a></button></td>
 <td><button onclick="actualizarCantidad(9)">Actualizar</button></td>
    </tr>
    <tr>
        <td>000000000030000051.10</td>
        <td>TOTEM TRASERAS CHECKIN</td>
<td id="cantidad10">1</td>
        <td><button onclick="window.open"><a href="Fotos/A2.JPG" target="_blank">A2</a></button></td>
<td><button onclick="actualizarCantidad(10)">Actualizar</button></td>
    </tr>
    <tr>
        <td>000000000030000051.11</td>
        <td>TOTEM SELF-CHECK-IN TRIANGULARES</td>
       <td id="cantidad11">12</td>
   <td><button onclick="window.open"><a href="Fotos/A3.JPG" target="_blank">A3</a></button></td>
   <td><button onclick="actualizarCantidad(11)">Actualizar</button></td> 
</tr>
    <tr>
        <td>000000000030000051.3</td>
        <td>TOTEM PREMIUM TIMEFLEX</td>
        <td id="cantidad12">3</td>
     <td><button onclick="window.open"><a href="Fotos/A13.JPG" target="_blank">A13</a></button></td>
   <td><button onclick="actualizarCantidad(12)">Actualizar</button></td>
 </tr>
    <tr>
        <td>000000000030000051.7</td>
        <td>TOTEM CHECK-IN ESTRECHO</td>
       <td id="cantidad13">1</td>
       <td><button onclick="window.open"><a href="Fotos/A8.JPG" target="_blank">A8</a></button></td>
    <td><button onclick="actualizarCantidad(13)">Actualizar</button></td>
    </tr>
    <tr>
        <td>000000000030000051.9</td>
        <td>TOTEM TRASERAS PREMIUM</td>
      <td id="cantidad14">2</td>
       <td><button onclick="window.open"><a href="Fotos/A1.JPG" target="_blank">A1</a></button></td>
    <td><button onclick="actualizarCantidad(14)">Actualizar</button></td>
    </tr>
    <tr>
        <td>30000166</td>
        <td>TOTEM EMBARQUE PREFERENTE</td>
       <td id="cantidad15">5</td>
       <td><button onclick="window.open"><a href="Fotos/A9.JPG" target="_blank">A9</a></button></td>
    <td><button onclick="actualizarCantidad(15)">Actualizar</button></td>
</tr>
    <tr>
        <td>000000030000166.01</td>
        <td>TOTEM EMBARQUE PREFERENTE ITALIANO</td>
       <td id="cantidad16">1</td>
       <td><button onclick="window.open"><a href="Fotos/A6.JPG" target="_blank">A6</a></button></td>
    <td><button onclick="actualizarCantidad(16)">Actualizar</button></td>
</tr>
    <tr>
        <td>VY0021</td>
        <td>TOTEM MADRID</td>
        <td id="cantidad17">1</td>
       <td><button onclick="window.open"><a href="Fotos/A5.JPG" target="_blank">A5</a></button></td>
    <td><button onclick="actualizarCantidad(17)">Actualizar</button></td>
    </tr>
    <tr>
        <td>VYCK 103</td>
        <td>TOTEM EMBARQUE PREFERENTE ANTIGUO (SIN CARTEL)</td>
        <td id="cantidad18">1</td>
        <td><button onclick="window.open"><a href="Fotos/A4.JPG" target="_blank">A4</a></button></td>
    <td><button onclick="actualizarCantidad(18)">Actualizar</button></td>
    </tr>
    <tr>
        <td>VYCK 119</td>
        <td>TOTEM ESTRECHO MOBILE</td>
      <td id="cantidad19">1</td>
     <td><button onclick="window.open"><a href="Fotos/A7.JPG" target="_blank">A7</a></button></td>
    <td><button onclick="actualizarCantidad(19)">Actualizar</button></td>
    </tr>
    <tr>
        <td>VYCK 122</td>
        <td>TOTEM FACIAL RECOGNITION</td>
      <td id="cantidad20">0</td>
        <td><button onclick="window.open"><a href="Fotos/A10.JPG" target="_blank">A10</a></button></td>
    <td><button onclick="actualizarCantidad(20)">Actualizar</button></td>
    </tr>
</table>
<table>
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Tamaño</th>
      <th>Impresión</th>
      <th>Cantidad</th>
      <th>Foto</th>
      <th>Actualizar Cantidad</th>
 </tr>
  </thead>
  <tbody>
  <tr><h3>CARTELES</h3></tr> 
  <td>MyBag blancos</td>
      <td>A3</td>
<td>1 cara</td>
     <td id="cantidad21">4</td>
<td><button onclick="window.open"><a href="Fotos/C4.JPG" target="_blank">C4</a></button></td>
<td><button onclick="actualizarCantidad(21)">Actualizar</button></td>
    <tr>
      <td>MyBag Amarillo</td>
      <td>A3</td>
    <td>1 cara</td>
      <td id="cantidad22">2</td>
     <td><button onclick="window.open"><a href="Fotos/C5.JPG" target="_blank">C5</a></button></td>
     <td><button onclick="actualizarCantidad(22)">Actualizar</button></td>

    <tr>
        <td>MyBag Amarillo</td>
      <td>A3</td>
    <td>doble cara</td>
        <td id="cantidad23">7</td>
      <td><button onclick="window.open"><a href="Fotos/C5.JPG" target="_blank">C5</a></button></td>
    <td><button onclick="actualizarCantidad(23)">Actualizar</button></td>

    <tr>
        <td>MyBag formulario aduanas</td>
      <td>A3</td>
    <td>1 cara</td>
        <td id="cantidad24">1</td>
        <td><button onclick="window.open"><a href="Fotos/C3.JPG" target="_blank">C3</a></button></td>
   <td><button onclick="actualizarCantidad(24)">Actualizar</button></td> 

    <tr>
        <td>Cartel Last Minute</td>
      <td>A3</td>
    <td>doble cara</td>
     <td id="cantidad25">1</td>
<td><button onclick="window.open"><a href="Fotos/C7.JPG" target="_blank">C7</a></button></td>
        <td><button onclick="actualizarCantidad(25)">Actualizar</button></td>

    <tr>
        <td>Cartel Customer Service horario de atención</td>
      <td>A4</td>
    <td>1 cara</td>
<td id="cantidad26">2</td>
        <td><button onclick="window.open"><a href="Fotos/C10.JPG" target="_blank">C10</a></button></td>
<td><button onclick="actualizarCantidad(26)">Actualizar</button></td>

    <tr>
        <td>Cartel Customer Service A21 </td>
      <td>A4</td>
    <td>1 cara</td>
<td id="cantidad27">7</td>
        <td><button onclick="window.open"><a href="Fotos/C11.JPG" target="_blank">C11</a></button></td>
<td><button onclick="actualizarCantidad(27)">Actualizar</button></td>    
</tr>
<tr>
<td>Cartel check in ORY</td>
      <td>A4</td>
    <td>1 cara</td>
<td id="cantidad28">5</td>
<td></td>
<td><button onclick="actualizarCantidad(28)">Actualizar</button></td>    
  
<tr>
<td>Cartel Exit Only</td>
      <td>A4</td>
    <td>1 cara</td>
<td id="cantidad29">1</td>
<td><button onclick="window.open"><a href="Fotos/C8.JPG" target="_blank">C8</a></button></td>
<td><button onclick="actualizarCantidad(29)">Actualizar</button></td>    

<tr>
<td>Cartel Objetos Olvidados</td>
      <td>A4</td>
    <td>1 cara</td>
<td id="cantidad30">4</td>
<td><button onclick="window.open"><a href="Fotos/C12.JPG" target="_blank">C12</a></button></td>
<td><button onclick="actualizarCantidad(30)">Actualizar</button></td>

<tr>
<td>Cartel Grupo 1</td>
      <td>A3/td>
    <td>1 cara</td>
<td id="cantidad11">31</td>
<td><button onclick="window.open"><a href="Fotos/C13.JPG" target="_blank">C13</a></button></td>
<td><button onclick="actualizarCantidad(31)">Actualizar</button></td>

<tr>
<td>Cartel Grupo 2</td>
      <td>A3/td>
    <td>1 cara</td>
<td id="cantidad32">7</td>
<td><button onclick="window.open"><a href="Fotos/C9.JPG" target="_blank">C9</a></button></td>
<td><button onclick="actualizarCantidad(32)">Actualizar</button></td>

<tr>
<td>Cartel Grupo 3</td>
      <td>A3/td>
    <td>1 cara</td>
<td id="cantidad33">24</td>
<td><button onclick="window.open"><a href="Fotos/C14.JPG" target="_blank">C14</a></button></td>
<td><button onclick="actualizarCantidad(33)">Actualizar</button></td>

<tr>
<td>Cartel Grupo 1+2</td>
      <td>A3/td>
    <td>1 cara</td>
<td id="cantidad34">28</td>
<td><button onclick="window.open"><a href="Fotos/C16.JPG" target="_blank">C16</a></button></td>
<td><button onclick="actualizarCantidad(34)">Actualizar</button></td>

<tr>
<td>Cartel Biometria</td>
      <td>A3/td>
    <td>1 cara</td>
<td id="cantidad35">28</td>
<td><button onclick="window.open"><a href="Fotos/C1.JPG" target="_blank">C1</a></button></td>
<td><button onclick="actualizarCantidad(35)">Actualizar</button></td>

<tr>
<td>Cartel Grups 1+2/Group 3</td>
      <td>A3/td>
    <td>doble cara</td>
<td id="cantidad36">10</td>
<td><button onclick="window.open"><a href="Fotos/C2.JPG" target="_blank">C2</a></button></td>
<td><button onclick="actualizarCantidad(36)">Actualizar</button></td>

<tr>
<td>Cartel Premium Flex</td>
      <td>A3/td>
    <td>doble cara </td>
<td id="cantidad37">0</td>
<td><button onclick="window.open"><a href="Fotos/C6.JPG" target="_blank">C6</a></button></td>
<td><button onclick="actualizarCantidad(37)">Actualizar</button></td>

<tr>
<td>Cartel Grupo 3 Poliespan</td>
      <td>A3/td>
    <td>doble cara</td>
<td id="cantidad38">10</td>
<td></td>
<td><button onclick="actualizarCantidad(38)">Actualizar</button></td>

<tr>
<td>Cartel FAMILIES + PMR</td>
      <td>A4/td>
    <td>doble cara</td>
<td id="cantidad39">3</td>
<td><button onclick="window.open"><a href="Fotos/C17.JPG" target="_blank">C17</a></button></td>
<td><button onclick="actualizarCantidad(39)">Actualizar</button></td>

<tr>
<td>Cartel FAMILIES + PMR</td>
      <td>A4/td>
    <td>doble cara</td>
<td id="cantidad40">2</td>
<td><button onclick="window.open"><a href="Fotos/C17.JPG" target="_blank">C17</a></button></td>
<td><button onclick="actualizarCantidad(40)">Actualizar</button></td>


