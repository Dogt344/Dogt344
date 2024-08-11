<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EJERCICIOS</title>
    <style>
        body {
            padding: 0px;
            margin: 0px;
        }

        .headerPrincipal {
            background-color: rgb(0, 0, 0);
            padding-top: 0;
            text-align: center;
        }

        .HeaderTitle {
            height: 35px;
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            background-color: rgb(0, 0, 0);
            gap: 0px;
            color: aliceblue;
        }

        .Title1, .Title2 {
            padding-left: 10px;
            margin: 0px;
            display: inline-block;
        }

        .container {
            width: 100%;
            text-align: center;
            margin-top: 20px;
        }

        .Saludo {
            font-family: 'Courier New', Courier, monospace;
            font-size: 35px;
            text-align: center;
            text-decoration: none;
            border-bottom: 1px solid;
            padding-bottom: 3px;
            display: inline-block;
            margin: 0 auto;
        }

        .TiposdeConocimientos {
            display: grid;
            padding: 0 20px;
            padding-top: 20px;
            grid-template-columns: 2fr;
        }

        .Conocimientos {
            background-color: aqua;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
        }

        .Tecnologias {
            text-align: center;
        }
    </style>
</head>
<body>
    <header class="headerPrincipal"> 
        <div class="HeaderTitle">
            <p class="Title1">EJERCICIOS</p>
            <p class="Title2">HTML</p>
        </div>
    </header>

    <section>
        <div class="container">
            <h2 class="Saludo">Mi Portafolio</h2>
        </div>
    </section>

    <section class="TiposdeConocimientos">
        <div class="Conocimientos">
            <div class="Tecnologias"> 
                <h2>ANGULAR</h2>
            </div>
            <div class="Tecnologias">
                <h2>REACT</h2>
            </div>
            <div class="Tecnologias">
                <h2>VUE</h2>
            </div>
            <div class="Tecnologias"> 
                <h2>ANGULAR</h2>
            </div>
            <div class="Tecnologias">
                <h2>REACT</h2>
            </div>
            <div class="Tecnologias">
                <h2>VUE</h2>
            </div>
        </div>
    </section>
</body>
</html>
