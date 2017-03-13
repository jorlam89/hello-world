# hello-world
just another repository
<!DOCTYPE html>
<html>
<head>
<style>
           * {
  margin: 0;
  padding: 0;
}

body {
  background: whiter;  
}

.container-fluid {
  overflow-wrap: break-word;
}

  header {
    wihtd: 100%;
    height: 50px;
}

    .navegar {
      background:orange;
      top:-20px;
      position: absolute;
      left:0;
      right:0;
      wihtd: 100%;
      margin: 20px auto;
      text-align: center;
      position: fixed;
}

      #icono {
        margin: 3px;
        width: 60px;
        height: 60px;
        border-radius: 50%;
}

      .well {
        text-align:center;
        /*border:2px solid red;*/
        margin:3px 20px 3px 10px;
        padding:5px 10px 5px 10px;        
        display: inline-block;
}

        .well:hover {
          background: #2980b9;  
}

      .navegar a {
        color: white;
        font-weight: bold;
        text-decoration: none;
}

 .cuerpo {
  verflow-wrap: break-word;
}

    #wrapper {
      text-align:center;
      background:white;
      height:0; /* altura cero */
      background-size:100%;
      /*display: block;*/
      padding-bottom: 40%; /* (altura/anchura)*100 */ 
}

      #wrapper h1 {
        font:normal 60pt Arial;
        color:#FFFFFF;
        margin: 15px;
        text-shadow: 0 1px 0 #ccc, 
          0 2px 0 #c9c9c9, 
          0 3px 0 #bbb,
          0 4px 0 #b9b9b9,
          0 5px 0 #aaa,
          0 6px 1px rgba(0,0,0,.1),
          0 0 5px rgba(0,0,0,.1),
          0 1px 3px rgba(0,0,0,.3),
          0 3px 5px rgba(0,0,0,.2),
          0 5px 10px rgba(0,0,0,.25),
          0 10px 10px rgba(0,0,0,.2),
          0 20px 20px rgba(0,0,0,.15); 
}

      #wrapper h3 {
        font-weight: bold;
        color: white;
        text-shadow: 5px 5px 5px #aaa;
}

      #wrapper p {
        font-weight: bold;
        color: white;
        text-shadow: 5px 5px 5px #aaa;
}

    .autor {
      text-align: center;
      verflow-wrap: break-word;
}

      #abaut {
        font-weight: bold;
}

      .autor p {
        font-weight: bold;
}

    .experiencia {
      verflow-wrap: break-word;
      text-align:center;
}

      #portfolio {
        font-weight: bold;
}

      .imgabaut {
        width: 300px;
        height: 300px;
        margin: 5px;
        border-radius: 10px;
}

    .fondocont {
      background:orange;
}

      .contactos{
        verflow-wrap: break-word;
        text-align:center;  
}

      #contact {
        font-weight: bold;
        color: white;
}

      .contactos p {
        font-weight: bold; 
}

        .botonred {
          font-weight: bold;
          text-decoration: none;
          background: black;
          margin: 3px 20px 3px 10px;
          border: 2px solid orange;
          border-radius: 8px;
          padding: 3px 3px 3px 3px;
          verflow-wrap: break-word;
          display: inline-block;
}

          .botonred a {
            text-decoration: none;
            color:orange;
}

  #foot p {
    font-weight: bold;
    background: black;
    color: white;
    text-align:center;
} 
</style>
</head>
<body>
<div class="container-fluid" >
  <header>
    <nav class="navegar"><img id="icono" src="http://estaticos.muyinteresante.es/uploads/images/article/566560d25bafe8a163dc683a/inteligencia-robots_0.jpg" alt="JRSOFTWARE ©"></img>
      <div class="well" id="autor">
        <a href="#home">
          JRSOFTWARE ©
        </a>
      </div>
      <div class="well">
        <a href="#abaut">
          ABAUT
        </a>
      </div>
      <div class="well">
        <a href="#portfolio">
          PORTFOLIO
        </a>
      </div>
      <div class="well">
        <a href="#contact">
          CONTACT
        </a>
      </div>
   </nav>
 </header>
 <div clase="cuerpo">
   <div class="jrsoft" id="wrapper">
     <h1 id="home">JRSOFTWARE ©</h1>
     <h3>TRANSFORMING DREAMS CODING</h3>
     <p>Make the impossible possible by developing software to suit you.</p>
   </div>
   <hr>
   <div class="autor">
     <h1 id="abaut">ABAUT</h1>
     <p>Systems Engineer, passionate about the digital world, software development, artificial intelligence and data science.</p>
     </div>     
   <hr>
   <div class="experiencia">
     <h1 id="portfolio">PORTFOLIO</h1>
     <div id="fotos">
       <img class="imgabaut" src="http://estaticos.muyinteresante.es/uploads/images/article/566560d25bafe8a163dc683a/inteligencia-robots_0.jpg" alt="Inteligencia artificial"></img>
       <img class="imgabaut" src="http://inmerzo.com/wp-content/uploads/2013/02/dise%C3%B1o-web-inmerzo1.png" alt="Desarrollo web"></img>
       <img class="imgabaut" src="http://centricug.com/wp-content/uploads/2016/12/services_banner.png" alt="Sitios Web"></img>
      <img class="imgabaut" src="https://www.study.monash/__data/assets/image/0010/363097/Data-Science-Education-at-Monash-Monash-University.jpg" alt="Data Science"></img>
     </div>
   </div>
   <hr>
   <div class="fondocont">
     <div class="contactos">
     <h1 id="contact">CONTACT</h1>
     <p>Contact me and follow me is the social networks</p>
     <div class="botonred">
       <a  target="_blank" href="https://www.facebook.com/jorge.a.regino">
         FACEBOK
       </a>
     </div>
     <div class="botonred">
       <a target="_blank" href="https://twitter.com/jorlam89">
         TWITTER
       </a>       
     </div>
     <div class="botonred">
       <a target="_blank" href="https://plus.google.com/104439522618445333071">
         G+
       </a>       
     </div>
   </div>
   </div>
  </div>
</div>
<footter id="foot"><p>JRSOFTWARE © 2017. All Rights Reversed</p></footter>
</body>
</html>
