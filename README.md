# primer-desarrollo-web
<!DOCTYPE html>
<html>

<head> 
    <title>Mi Web</title>
</head>
<body>
    <!--H es para encabezados-->

    <h1>Esto es un encabezado</h1>
    <h2>Encabezado h2</h2>
    <h3>Encabezado h3</h3>
    <h4>Encabezado h4</h4>
    <h5>Encabezado h5</h5>
    <h6>Encabezado h6</h6>

    <!-- P es para parrafos  -->
    
    <p id="aprendiendohtml">Estamos aprendiendo html</p>

    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
    </p>

    <!-- Formato del texto -->

    <p>Lorem ipsum, <b>dolor sit amet consectetur adipisicing elit</b>. Accusantium quasi, quas obcaecati amet facilis laborum, cupiditate, <strong>perferendis beatae</strong> sed natus <i>rerum sapiente enim</i>. Reiciendis quas unde <mark>quaerat</mark> consequatur eaque sapiente?</p>
    <p>Aprendiendo <abbr title="Hypertext Markup Language">HTML</abbr> con Navis code</p>
    <blockquote>"Que la comida sea tu alimento y el alimento tu medicina"</blockquote>
    <hr>
    <p>Lorem ipsum dolor sit amet <br>consectetur adipisicing elit. Praesentium, necessitatibus?</p>
    <hr>

    <!-- Atributos -->

    <p title="HTML con 'Navis Code'">Parte 4 del curso HTML con Navis Code</p>

    <!-- Imagenes -->
    <img src="images/officework1.jpeg" alt="officework" width="300" title="officework" >
    <hr>

    <!-- Links, Vinculos o Enlaces -->
    
    <a href="http://www.google.com" target="_blank">Ir a Google</a>
    <br>
    <a href="images/officework1.jpeg">Click aqui para ver oficina en casa</a>
    <br>
    <a href="mailto:unusuario@mail.com">Link al correo</a>
    <br>
    <a href="#aprendiendohtml">Link anclado</a>

    <!-- Listas ordenadas-->
    <!-- Numeracion type= 1, I, i, A, a-->
    <ol type="I" start="7">
        <li>Elemento de lista ordenada</li>
        <li>Elemento de lista ordenada</li>
        <li>Elemento de lista ordenada</li>
        <li>Elemento de lista ordenada</li>
    </ol>
    <!-- Listas No Ordenadas-->
    <!-- La viñeta puede ser type= disc, circle, square-->
    <ul type= "square"> 
        <li>Elemento de lista No ordenada</li>
        <li>Elemento de lista No ordenada</li>
        <li>Elemento de lista No ordenada</li>
        <li>Elemento de lista No ordenada</li>
    </ul>

    <!-- Lista anidada-->
    <ol type="1">
        <li>Elemento en lista</li>
        <li>Elemento en lista</li>
            <ul type="square">
                <li>Lista anidada</li>
                <li>Lista anidada</li>
                <li>Lista anidada</li>
            </ul>
        <li>Elemento en lista</li>
        <li>Elemento en lista</li>
    </ol>
    <!-- Listas de Definicion-->
    <!-- Elementos DL, DT, DD-->
    <dl>
        <dt>Photoshop</dt>
        <dd>Software para edicion de imagenes propiedad de Adobe</dd>
        <dt>GIMP</dt>
        <dd>Software para edicion de imágenes propiedad de GNU</dd>
    </dl>

</body>
</html>
