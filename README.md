/*resetando*/
* {
    padding: 0;
    margin: 0;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

/*cabeçalho*/
h1,
p {
    text-align: center;
}

h1 {
    margin-top: 80px;
    margin-bottom: 20px;
    color: rgb(24, 174, 174);
}

/*galeria*/
.container {
    max-width: 1200px;
    margin: 0px auto;
    text-align: center;
}

.card {
    display: inline-block;
    width: 200px;
    margin: 25px;
    border: 2px solid rgb(24, 174, 174);
}

.card-imagem {
    height: 200px;
    background-size: cover
}

.card-1 .card-imagem {
    background-image: url(../img/1_comida.jpg)
}

.card-2 .card-imagem {
    background-image: url(../img/2_comida.jpg)
}

.card-3 .card-imagem {
    background-image: url(../img/3_comida.jpg)
}

.card-4 .card-imagem {
    background-image: url(../img/4_comida.jpg)
}

.btn {
    display: block;
    background-color: rgb(24, 174, 174);
    color: #000000;
    margin-top: 20px;
    text-decoration: none;
    padding: 10px;
    border: 2px solid transparent;
    font-weight: bold;
    transition: .5s;
    border-radius: 5px;
}

.btn:hover {
    background-color: #fff;
    color: rgb(24, 174, 174);
    border-color: rgb(24, 174, 174);
}

.card-descripition {
    padding: 20px 10px;
    border-radius: 5px;
}
