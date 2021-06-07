+<html>

<head>
<TITLE>YOJAN --> CURSO HTML</TITLE>
 </head>
    
  <body bgcolor="BCEAFF"> 
       
 
  <center><p> </aling> prueba, curso html <b/r>
     esto es una prueba </p> 
    </center>
     <ol>

 <p> <li>Hola amigos</li> </p>
 <p><b><li>Hola amigos</li> </b></p>
 <p><big><li> Hola amigos </li></big></p>
 <p><i> <li>Hola amigos</li></i></p>
 <p><small><li> Hola amigos</li> </small></p>
 <p><strong><li> Hola amigos</li> </strong></p>
 <p><sub> <li>Hola amigos</li> </sub></p>
 <p><sup> <li>Hola amigos</li>  </sup></p>
 <p><ins><li> Hola amigos</li> </ins></p>
 <p><del> <li>Hola amigos</li> </del></p>

</ol>

 <hr/>
 <hr width="50px" />
 
 <ul>

 <li> <h1>En este aartado encontraremos el grandor de las letras  filo</h1> </li>
 <li><h2>En este aartado encontraremos el grandor de las letras</h2></li> 
<li><h3>En este aartado encontraremos el grandor de las letras</h3> </li>
<li><h4>En este aartado encontraremos el grandor de las letras</h4> </li>
<li><h5>En este aartado encontraremos el grandor de las letras</h5> </li>
<li> <h6>En este aartado encontraremos el grandor de las letras</h6> </li>

</ul>
<hr/>
<!-- ​comentario -->

<p align="center"> <h2>Yojan</h2> <br/>
    <hr width="10%"  /> anteriormente evidenciamos una clase de linea trasada como lo habiamos hecho mucho antes </center></p> 

<img  src="https://www.wamanadventures.com/blog/wp-content/uploads/2020/01/san_andres_colombia_.jpg" 
 height="150px" Width"50%" border"1px" alt=""/>

<p> </p><a href="https://www.wamanadventures.com/blog/wp-content/uploads/2020/01/san_andres_colombia_.jpg"_blank"> 
    pasaje 
</a> </p>

<table border="2">
    <tr>
<td bgcolor="green"> curso</td>
<td bgcolor="green"> titulo</td>
<td bgcolor="green"> titulo 2</td>
</tr>
<tr>
<td><font color="62FF00">Tecnologo </font><br /></td>
<td  colspan="2">Infraestructura de las comunicacines<br /></td>
</tr>
</table>


<h1><span>Tabla activdades</span></h1>
<table  border="1">
<tr>
<th>Tiempo</th>
<th>Lunes</th>
<th>Martes</th>
<th>Miercoles</th>
<th>Jueves</th>
<th>viernes</th>
</tr>
<tr>
<td></td>
<td class="selected"></td>
<td></td>
<td></td>
<td></td>
<td></td>
        
   
</table>



<h1> APRENDIZAJE SENA </h1>
<div style="background-color:rgb(22, 14, 92); color:white;
padding:20px;">
<p>Yojan Esteban Aguilar Tapiero </p>

</div>


<h2> Yojan Esteban 
<span style="color:red">Aguilar Tapiero</span></h2>




<!-- <form action="(URL Pagina)"></form> 
Este comando nos arrojaria a otra pagina despues de contestar todo -->

 <!--<form action="url" method="GET"> -->
 <!--<form action="url" method="POST"> --> 

     

<form>
    <input type="text" name="username" /><br />
    <input type="password" name="password" />
</form>
 <hr/>

 <input type="radio"  name="Genero" value="Mujer" /> Mujer
 <br />
 <input type="radio" name="Genero" value="Hombre" /> Hombre
 <br />


 
 <input type="checkbox"  name="Genero" value="1" /> Mujer
 <br />
 <input type="checkbox" name="Genero" value="2" /> Hombre
 <br />

<input type="submit"  value="Enviar" /> 





<span>informacion</span>
<form>
    <input name="Nombre" type="text" /><br/>
    <input name="Email" type="email" /><br/>
    <textarea name="Mensaje"></textarea>
    <input type="submit" value="Enviar" class="submit" />

</form>



<frame noresize = " noresize ">
<frameset cols = "25%, 50%, 25%">
 
<frame src = "a.htm" />
      
<frame src = "b.htm" />
      
<frame src = "c.htm" />
      
<noframes > ¡Marcos no compatibles! </noframes>
      
</frameset>
<!--este atributo no permite que un usuario pueda cambiar
lo ancho o las medidas de la pagina-->



<div class = "section">
<h1><span>Mis medios</span></h1>
 <inframe  height = "150" width = "300" src =
 "https://www.youtube. com" / embed / Q6_5InVJZ88"
 allowfullscreen frameborder ="0"></inframe>
</div>




  </body>
 
 </html>
 
 <!Doctype HTML>

 <html>
 <head>
<script>
function allowDrop(ev) {
 ev.preventDefault();
}
    
function drag(ev) {
ev.dataTransfer.setData("text", ev.target.id);
}
    
function drop(ev) {
 ev.preventDefault();
 var data = ev.dataTransfer.getData("text");
ev.target.appendChild(document.getElementById(data));
}
</script>
 </head>
 <body>
<header>
 <h1>aca se podria colocar algun titulo </h1>
<h3>y aca un subtitulo</h3>
</header>

<nav> 
<ul>
<li><a href="#">en esta parte</a></li>
<li><a href="#">podriamos agregar </a></li>
<li><a href="#">algun dato importante para asi ser sub-rayado</a></li>
</ul>
</nav>
<article>
<h1>aca colocariamos algo que quisieramos resaltar </h1>
<p>aca el relleno </p>
</article>
<article>
<h1>Hola soy Yojan</h1>
<section>
<h1>bodega</h1>
<p>(contenido para imagen)</p>
</section>
</article>
<article>
<h1> titulo de algo</h1>
<p> texto relacionado 
</p>
<aside>
<p>mas texto</p>

</aside>
</article>

<audio> src="audio.mp3" controls>
Elemento de audio no compatible con su navegador
</audio>

<audio controls autoplay>
    <source src="audio.mp3"  type="audio/mpeg">
    <source src="audio.ogg"  type="audio/ogg"
</audio>
   <!-- <audio controls autoplay> este se usa para que se 
       reproduzca automaticamente el audio, y  
       <audio controls autoplay loop> este se utiliza para que se
      reproduzca al momento de que el audio acabe-->

<video controls autoplay loop>
    <source src="video.mp4" type="video/mp4">
    <source src="video.mp4" type="video/ogg">
    
    video is not supported by your browser
</video>

CARGANDO...: <progress min="0" max="100" value="35">

</progress>

localStorage.wetItem("key1","value1");

//this will print ther value
alert(localStorage.getItem("key1"));

localStorage.removeItem("key1");

localStorage.clear();

<div id="box" ondrop="drop(event)"
   ondragover="allowDrop(event)"
   style="border:1px solid black; 
   width:200px; height:200px"></div>

   <img id="image" src="sample.jpg" draggable="true"
   ondragstart="drag(event)" width="150" height="50" alt="" />

   function drag(ev) {
    ev.dataTransfer.setData("text", ev.target.id); 
} 

function drop(ev) {
    ev.preventDefault();
    var data = ev.dataTransfer.getData("text");
    ev.target.appendChild(document.getElementById(data));
}

<img src="image.svg" alt="" height="300" />

<svg width="2000" height="2000"><circle cx="80" cy="80" 
    r="50" fill="blue"/>
</svg> 

<svg width="2000" height="2000">
    <rect width="300" height="100"
    x="20" y="20" fill="green" />
</svg>

    <svg width="400" height="410">
    <line x1="10" y1="10" x2="200" y2="100"
    style="stroke:#000000; stroke-linecap:round;
    stroke-width:20" />

    </svg>

    <svg width="2000" height="500">
        <polyline style="stroke-linejoin:miter;
        stroke:black;
        stroke-width:12; fill: none;"
        points="100 100, 150 150, 200 100" />
    </svg>

<svg height="500" width="1000">
    <ellipse cx="200" cy="100" rx="150" ry="70"
    style="fill:green" />
</svg>

    <svg width="2000" height="2000">
        <polygon points="100 100, 200 200, 300 0"
        style="fill:green; stroke:black;" />
    </svg>

<svg width="1000" height="250">
    <rect width="150" height="150" fill="orange">
    <animate attributeName="x" from="0" to="2" />
    </rect>
</svg>

<svg width="500" heifht="500">
    <path d="M 0 0 L200 200 L200 0 Z" style="stroke:#000;
    fill:none;" />
</svg>
 <canvas id="canvas1"
 width="400" height="300" ></canvas>

 <script>
     var can = document.getElementById("canvas1")
     var ctx = can.getContext("2d");
    
 </script>

var c=document.getElementById("canvas1");
var ctx=c.getContext("2d"); 
ctx.fillRect(20,20,100,100);

var canvas=document.getElementById("canvas1");  
var ctx=canvas.getContext("2d");
ctx.fillStyle ="rgba( 0, 200, 0, 1,)";
ctx.fillRect (36, 10, 22, 22);

ctx.font="bold 22px tahoma";
ctx.textAling="Iniciar";
ctx.fillText("start", 10, 30);

ctx.translate(100,150);
ctx.fillText("after translate", 10, 30);

ctx.fillStyle = "#FF0000";
ctx.fillRect(10, 10, 100, 100);

ctx.rotate((math.PI / 180) * 25); //rotate 25
degrees.

ctx.fillStyle = "#0000FF";
ctx.fillRect(10,10, 100, 100);

var canvas = document.getElementById('canvas1');
ctx =canvas.getContext('2d');
ctx.font="bold 22px tahoma";
ctx.textAling="start";
ctx.fillText("start", 10, 30);
ctx.translate(100, 150);
ctx.filltext("after translate", 0, 0);
ctx.rotate(1);
ctx.filltext("after rotate", 0, 0);
ctx.scale(1.5, 4);
ctx.filltext("after scale", 0, 20);

<form>
    <label> your name:</label>
    <input id="user" name="username" type="text" />

</form>

<form>
<label for="email">Correo Electronico:</label>
<input type="text" name="email"
placeholder="Email@Ejemlo.com" />

</form>

<form>
<label for="email">Introduce tu correo:</label>
<input type="text" name="email" autofocus/>

</form>

<form autocomplete="off">
<label for="e-mail">Introduce tu contraseña:</label>
<input name="Email" type="text" required />
<input type="submit" value="submit" />

</form>

<input id="mysearch" name="searchitem" type="search" />


<input id="car" type="text" list="colors" />
<datalist id="colors">
<option value="Red">
<option value="Green">
<option value="yellow">
            
</option>
</option>
</option>
</datalist>


<input id="email" name="email" type="email"
placeholder="Correo@ejemplo.com"/>
<br />
<input id="url" name="url" type="url"
placeholder="ejemplo.com" />
<br />
<input id="tel" name="tel" type="tel"
placeholder="123.456.789" />





 </body>

 </html>
