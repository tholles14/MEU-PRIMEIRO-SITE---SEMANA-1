# MEU-PRIMEIRO-SITE---SEMANA-1
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sertanejo é vida!</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <div class="title">
        <img src="title.jfif" alt="imagem do estilo">
    
        <h1>SERTANEJO RAIZ</h1>
    </div>
    <hr>
    <h2>VEJAM 3 CANTORES DA ATUALIDADE:</h2>
    <hr>
    
    <div class="cards">
        <div class="marilia">
            <h2>Marília Mendonça</h2>
            <a href="https://www.youtube.com/user/mariliamendoncareal"><img src="mr.jpg" alt="Marilia Mendonça"></a>
            <br>
            <p>
                Marília Dias Mendonça é uma cantora, compositora e instrumentista brasileira. 
                Em 2015, lançou seu EP de estreia homônimo, porém Marília só ganhou destaque 
                após lançar seu primeiro DVD homônimo em 2016, que recebeu certificado de disco
                de tripla platina pelas 240.000 cópias vendidas.
            </p>
            <h3>Músicas para lembrar do(a) ex:</h3>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=2WsIm6pNlI4">Marília Mendonça - Estranho (Agora Que São Elas 2)</a></li>
                <li><a href="https://www.youtube.com/watch?v=sS2yCCi2Mek">Marília Mendonça - Eu Sei De Cor - DVD Realidade</a></li>
                <li><a href="https://www.youtube.com/watch?v=eCyMh-mZ1B0">Marília Mendonça - Infiel - Vídeo Oficial do DVD</a></li>
            </ul>
        </div>
        <div class="gustavo">
    
            <h2>Gustavo Lima</h2>           
            <a href="https://www.youtube.com/channel/UCXooz9whNJZBRTHi9AqdjPw"><img src="gl.jpg" alt="Gustavo Lima"></a>
            <br>
            <p>
                Gusttavo Lima, nome artístico de Nivaldo Batista Lima é um cantor,
                compositor, produtor musical e empresário brasileiro. Começou sua 
                carreira aos sete anos de idade, tocando no Trio Remelexo, formado 
                por seus irmãos mais velhos, Willian & Marcelo, e depois passou por 
                uma dupla sertaneja chamada Gustavo & Alessandro.
            </p>
            <h3>Músicas para sofrer o final de sema inteiro:</h3>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=HrpBSGaM_tc">Gusttavo Lima - Saudade Sua (Clipe Oficial)</a></li>
                <li><a href="https://www.youtube.com/watch?v=pgHrRi91-Mk">Gusttavo Lima - Eu Não Iria - DVD O Embaixador (Ao Vivo)</a></li>
                <li><a href="https://www.youtube.com/watch?v=1sqNI-Psmk8">Gusttavo Lima - Tudo Que Vai Um Dia Volta - DVD O Embaixador (Ao Vivo)</a></li>
            </ul>
        </div>
        <div class="zecristiano">
            <h2>Zé Neto & Cristiano</h2>
            
            <a href="https://www.youtube.com/channel/UCRRu9OXVYd5clj2Bs29gUVQ"><img src="zc.jpg" alt="Zé Neto & Cristiano"></a>
            <br>
            <p>
                Zé Neto & Cristiano é uma dupla sertaneja brasileira
                formada por José Toscano Martins Neto, o Zé Neto, e 
                Irineu Vaccari, o Cristiano. Ambos nascidos em São José
                do Rio Preto, no interior de São Paulo.
            </p>
            <h3>Músicas para arrastar o chifre no asfalto:</h3>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=FuQy4PReiSM">Zé Neto e Cristiano - LARGADO ÀS TRAÇAS</a></li>
                <li><a href="https://www.youtube.com/watch?v=rYKOuKaWEjg">Zé Neto e Cristiano - NOTIFICAÇÃO PREFERIDA</a></li>
                <li><a href="https://www.youtube.com/watch?v=vrnQPxnmFD8">Zé Neto e Cristiano - FERIDA CURADA</a></li>
            </ul>
        </div>
    </div>
    

</body>
</html>





*{
    box-sizing: border-box;
}


.title{
    text-align: center;
}
.marilia p{
    text-align: center;
}
.marilia{
    max-width: 301px;
    margin: auto;
    text-align: center;
    

    float: left;

    border: 1px solid;

    top: -200px;
}
.marilia h3{
    background-color: black;
    color: white;
}
.marilia img{
    margin-top: -1px;
    max-width: 300px;
}
.marilia:hover{
    background-color: rgb(93, 159, 235);
    box-shadow: 1px 10px 10px rgb(7, 53, 105);
}
.gustavo p{
    text-align: center;
}
.gustavo{
    float: right;
    max-width: 301px;
    margin: auto;
    text-align: center;

    

    border: 1px solid;

    top: -200px;
}
.gustavo h3{
    background-color: black;
    color: white;
}
.gustavo img{
    margin-top: -1px;
    max-width: 300px;
}
.gustavo:hover{
    background-color: rgb(93, 159, 235);
    box-shadow: 1px 10px 10px rgb(7, 53, 105);
}
.zecristiano p{
    text-align: center;
}
.zecristiano{
    float: center;
    max-width: 301px;
    margin: auto;
    text-align: center;

    border: 1px solid;

    top: -200px;
}
.zecristiano h3{
    background-color: black;
    color: white;
}
.zecristiano img{
    margin-top: -1px;
    max-width: 300px;
}
.zecristiano:hover{
    background-color: rgb(93, 159, 235);
    box-shadow: 1px 10px 10px rgb(7, 53, 105);
}
