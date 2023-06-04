<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu portifolio</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.1/css/all.min.css" rel="stylesheet">
    <link rel="stylesheet" href="css/styleP.css">
    <style>
      *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Saira Extra Condensed', sans-serif;
}

html,body{
    height: 100%;
}


.parent{
    display: flex;
}

.sidebar{
    width:20%;
    height: 100%;
    position: fixed;
    background-color: #512679;
}

.sidebar-pos{
    position: absolute;
    top:50%;
    transform:translateY(-50%);
}

.img-sidebar{text-align: center;}

.img-sidebar img{
    width: 80%;
    height: 40%;
    border:8px solid #62318e;
    border-radius: 50%;
}

.menu{
    margin:20px 0;
    text-align: center;
}

.menu a{
    color: white;
    opacity: 0.4;
    font-size: 24px;
    display: block;
    margin-bottom: 20px;
    text-decoration: none;
}

.menu a.selected{
    opacity: 1;    
}

.content{
    position:absolute;
    left: 20%;
    width: 80%;
    height: 100%;
    overflow-y:auto;
    padding:0 3%;
}

section.descricao{
    padding: 2%;
    position: relative;
    top:65%;
    transform:translateY(-50%);
}

section.descricao h2{

    color:#343a40;
    font-size: 46px;
}

section.descricao h2 > span,
section.descricao h3 > span,
section.descricao h4 > span
{
    color:  #62318e;
}

section.descricao h3{
    margin-top: 40px;
    margin-bottom: 20px;
    color: #6c757d;
    font-size: 26px;
}

section.descricao h4{
    margin-top: 40px;
    color: #6c757d;
    font-size: 20px;
}


section.descricao p{
    color:#6c757d;
    font-size:20px;
    margin-top:50px 0;
}

.icons-social{
    margin-top:20px;
}

.icons-social a{
    text-decoration:none;
    color: white;
    background-color: gray;
    width:40px;
    height:40px;
    border-radius:20px;
    display: inline-block;
    margin:0 10px;
    text-align: center;
}

.icons-social i{
    line-height:40px;
}
      
    </style>
</head>
<body>
    <div class="parent">

        <div class="sidebar">
  
          <div class="sidebar-pos">
              <div class="img-sidebar">
                <img src="img/minhaFoto.jpg" />
              </div><!--img-->
  
              <div class="menu">
                <a class="selected" href="#">Sobre</a>
                <a href="#">Experiência</a>
                <a href="#">Projetos</a>
              </div><!--menu-->
          </div><!--sidebar-pos-->
  
        </div><!--sidebar-->
  
        <div class="content">
  
          <section class="descricao">

             <h2>Matheus <span>Pereira</span></h2>
             
            <h3>Quem eu sou?</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus vel delectus doloremque repellat nulla ex adserunt incidunt minima ratione beatae consequuntur, tempora sequi ipsa! Eius earum voluptates enim ab corrupti. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eos, expedita mollitia consectetur provident necessitatibus possimus eveniet voluptatem enim perferendis, consequuntur asperiores nostrum ipsum ullam officia deserunt modi autem voluptas! Beatae? Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            <h3>Com oque trabalho?</h3>
  
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus vel delectus doloremque repellat nulla ex adserunt incidunt minima ratione beatae consequuntur, tempora sequi ipsa! Eius earum voluptates enim ab corrupti. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eos, expedita mollitia consectetur provident necessitatibus possimus eveniet voluptatem enim perferendis, consequuntur asperiores nostrum ipsum ullam officia deserunt modi autem voluptas! Beatae? Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            <h3>Linguagem que ultilizo</h3>
  
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus vel delectus doloremque repellat nulla ex adserunt incidunt minima ratione beatae consequuntur, tempora sequi ipsa! Eius earum voluptates enim ab corrupti. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eos, expedita mollitia consectetur provident necessitatibus possimus eveniet voluptatem enim perferendis, consequuntur asperiores nostrum ipsum ullam officia deserunt modi autem voluptas! Beatae? Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              <h4>Francisco barbosa da silva · Pacajus- CE · CO 68270-000 · <span>(317) 585-8468 · NAME@EMAIL.COM</span></h4>
            
            <div class="icons-social">
              <a href=""><i class="fab fa-facebook-f"></i></a>
              <a href=""><i class="fab fa-instagram"></i></a>
              <a href=""><i class="fab fa-youtube"></i></a>
            </div><!--icons-social-->
         
          </section><!--descricao--->  
  
        </div><!--content-->
  
      </div><!--parent-->
      
  </body>
</html>
