<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 

`
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="Css/Style.css" rel="Stylesheet" type="text/css">
    <title>Document</title>
</head>

<body>
    <h1 class="name__nomb">Clase de Formularios</h1>
    <form class="form__form" action="example.php" method="post">
        <nav class="form__1">
        <div class="form__nomb">
            <label for="nombrep">Nombre del Producto</label>
            <input type="text" name="nombrep" id="nombrep" placeholder="Nombre">
        </div>


        <br>

        <div class="form__cant">
            <label for="cantidad">Cantidad</label>
            <input type="number" name="cantidad" id="cantidad" placeholder="Cantidad del Producto">
        </div>


        <br>



        <div class="form__prec">


            <label for="precio">Precio Unitario</label>
            <input type="number" name="precio" id="precio" placeholder="Precio Unitario">


        </div>


        <br>

 
        <div class="form__pretot">
            <label for="preciot">Precio Total</label>
            <input type="number" name="preciot" id="preciot" placeholder="Precio Precio Total">
        </div>
        <br>
        <div class="form__direc">
            <label for="direccion">Dirección de Envío</label>
            <input type="text" name="direccion" id="direccion" placeholder="Dirección de Envío">
        </div>
    </nav>
        <br>
        <nav class="form__subti">
            <h2 class="form__info">Información de Contacto</h2>
        </nav>
        <br>
        <div class="form__name">
            <label for="preciot">Precio Total</label>
            <input type="text" name="preciot" id="nombre" placeholder="Precio Total">
        </div>
        <br>
        <div class="form__email">
            <label for="email">Correo Electrónico</label>
            <input type="email" name="email" id="email" placeholder="Correo Electrónico">
        </div>
        <br>
        <div class="form__tel">
            <label for="telefono">Número de Teléfono</label>
            <input type="tel" name="telefono" id="telefono" placeholder="Número de Teléfono">
        </div>
        <br>
        <nav class="form__subti">
            <h1 class="form__subti2">Métodos de Pago</h1>
        </nav>
        <br>
        <div class="form__selec">
            <select name="metodo" id="metodo">
                <option value="tarjeta">Tarjeta</option>
                <option value="efectivo">Efectivo</option>
                <option value="nequi">Nequi</option>
            </select>
        </div>
        <br>
        <div class="form__fec">
            <label for="fecha">Fecha de Entrega</label>
            <input type="date" name="fecha" id="fecha">
        </div>
        <br>

        <textarea name="comentarios" id="comentarios" placeholder="Ingrese sus comentarios aquí" rows="10"
            cols="50"></textarea>
        <br>
        <br>
        <div class="form__selec">

        </div>
     <br>


        <input type="submit" value="Enviar">
    </form>
</body>

</html>

``

```HTML,CSS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="Css/Style.css" rel="Stylesheet" type="text/css">
    <title>Document</title>
</head>

<body>
    <h1 class="name__nomb">Clase de Formularios</h1>
    <form class="form__form" action="example.php" method="post">
        <nav class="form__1">
        <div class="form__nomb">
            <label for="nombrep">Nombre del Producto</label>
            <input type="text" name="nombrep" id="nombrep" placeholder="Nombre">
        </div>


        <br>

        <div class="form__cant">
            <label for="cantidad">Cantidad</label>
            <input type="number" name="cantidad" id="cantidad" placeholder="Cantidad del Producto">
        </div>


        <br>



        <div class="form__prec">


            <label for="precio">Precio Unitario</label>
            <input type="number" name="precio" id="precio" placeholder="Precio Unitario">


        </div>


        <br>

 
        <div class="form__pretot">
            <label for="preciot">Precio Total</label>
            <input type="number" name="preciot" id="preciot" placeholder="Precio Precio Total">
        </div>
        <br>
        <div class="form__direc">
            <label for="direccion">Dirección de Envío</label>
            <input type="text" name="direccion" id="direccion" placeholder="Dirección de Envío">
        </div>
    </nav>
        <br>
        <nav class="form__subti">
            <h2 class="form__info">Información de Contacto</h2>
        </nav>
        <br>
        <div class="form__name">
            <label for="preciot">Precio Total</label>
            <input type="text" name="preciot" id="nombre" placeholder="Precio Total">
        </div>
        <br>
        <div class="form__email">
            <label for="email">Correo Electrónico</label>
            <input type="email" name="email" id="email" placeholder="Correo Electrónico">
        </div>
        <br>
        <div class="form__tel">
            <label for="telefono">Número de Teléfono</label>
            <input type="tel" name="telefono" id="telefono" placeholder="Número de Teléfono">
        </div>
        <br>
        <nav class="form__subti">
            <h1 class="form__subti2">Métodos de Pago</h1>
        </nav>
        <br>
        <div class="form__selec">
            <select name="metodo" id="metodo">
                <option value="tarjeta">Tarjeta</option>
                <option value="efectivo">Efectivo</option>
                <option value="nequi">Nequi</option>
            </select>
        </div>
        <br>
        <div class="form__fec">
            <label for="fecha">Fecha de Entrega</label>
            <input type="date" name="fecha" id="fecha">
        </div>
        <br>

        <textarea name="comentarios" id="comentarios" placeholder="Ingrese sus comentarios aquí" rows="10"
            cols="50"></textarea>
        <br>
        <br>
        <div class="form__selec">

        </div>
     <br>


        <input type="submit" value="Enviar">
    </form>
</body>

</html>

``





