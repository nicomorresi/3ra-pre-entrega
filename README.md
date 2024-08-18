* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


/* Estilos Generales */

body {
    background-color:black;
}

header {
    text-align: center;
}


header nav {
    text-align: center;
}

header nav ul li {
    list-style: none;
}


header nav ul li a {
    text-decoration: none;
    color: tomato;
}

/* Estilos de mobile */

header {
    display: flex;
    justify-content: center;
    align-items: center;
}

header nav ul {
    display: flex;
    gap: 25px;
}
.header-home {
    background-color: black;
}
.header-ubicacion {
    background-color: black;
}
.header-servicios{
    background-color: black;
}
.header-contacto{
    background-color: black;
}
.header-horarios{
    background-color: black;
}

/* Estilos de Home */
/* Header */

main {
    color: whitesmoke;
    margin-top: 50px;
    text-align: center;
    padding: 10px;
}

/* Estilos de Footer */

footer {
    text-align: center;
    color: whitesmoke;
    margin-top: 50px;
}

/* estilos de home */

.main-home {
    color: burlywood;
    margin-top: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.main-home img {
    width: 480px;
    margin-top: 15px;
}

.main-home ul {
    text-align: center;
}



/* estilos de contacto */

.main-contacto {
    color: burlywood;
}

/* estilos de servicios */

.main-servicios {
    color: burlywood;
    margin-top: 70px;
    display: flex;
    flex-direction: column;
    gap: 20px;
}
--------------------------
.main-servicios img {
    width: 60%;
    margin-top: 15px;
}
--------------------------

.main-servicios ul {
    color: darkorange;
    text-align: center;
}

.main-servicios {
    display: grid;
    grid-template-columns: (2, 1fr);
    grid-template-rows: (2, 1fr);
}

main .main-servicios {
    flex-direction: row;
}

main .main-servicios {
    margin-top: 20px;
}

main .main-servicios div img {
    width: 65px;
}


/* estilos de ubicacion */

.main-ubicacion {
    color: burlywood;

}

/* estilos de horario */
.main-horarios {
    color: burlywood;
}

/* mq */


@media screen and (min-width: 768px) and (max-width: 1023px) {
    header {
        justify-content: space-around;
    }

    body {
        background-color: gray;
    }
}

@media  and (max-width: 767px) {
    header {
        justify-content: space-around;
    }

    body {
        background-color:black;
    }
}
# 3ra-pre-entrega
