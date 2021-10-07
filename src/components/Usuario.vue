<template>
<div class= "a">
    <div class = "mi-cuenta  ">
        <div class= "contenedor">
           
            <div class= "texto text-center">Mi Cuenta</div>
           <div class= "cuadro-info ">
               <div class = "contenido">
                   <div class= "text ">Nombre de cuenta:</div>
                   <div class= "text ">Tipo de cuenta:</div>
                   <div class= "text ">Balance:</div>
               </div>
            </div> 
            

            
        </div>
    </div>
     <div class= "row">
        <div class= "row botones">

        <b-button size="lg" class="colorNegroLetra  boto rounded-pill colorBoton1 colorNegroLetra" type="submit">Realizar transferencia</b-button>
        <b-button size="lg" class="colorNegroLetra  boto rounded-pill colorBoton1 colorNegroLetra" type="submit">Ver facturas asociadas</b-button>
        </div>
   
        <img src="https://i.ibb.co/Fk1DH5J/pngwing-com-1.png" alt="pngwing-com-1" border="0">
    </div>
</div>
</template>


<style media = "screen">


.mi-cuenta{
margin-top: 50px;
width: 56.62148070907195%;
height: 36.39207507820647%;
min-height: 40.39207507820647vh;
justify-content: center;
margin-left: 50px;
float: left;
background: #343330;
border-radius: 25px;
}
.text{
    margin-bottom: 2%;
    margin-top: 2%;
    margin-left: 3%;
    color:#000000;

   
    font-family: arial,san-serif;   
    font-size: 100%;
}
.botones{
    padding-left: 200px ;
    padding-right: 50px ;
    padding-top: 50px ;
    margin: 50px;
    justify-content: center;
    max-width: 100vh;
    
}
.boto{
    padding-top: 100px ;
    padding: 20px 28px;
    max-width: 50px;
   margin-bottom: 50px;
   margin-top: 30px;
   
}
.cuadro-info{

position: absolute;
width: 52.62148070907195%;
height: 30.39207507820647%;
/*min-height: 33.39207507820647vh;*/
margin-left: 2%;
background: #F5F9F8;
border: 1px solid #000000;
box-sizing: border-box;
border-radius: 25px;
}
.texto{
    color: aliceblue;

   
    font-family: arial,san-serif;   
    font-size: 100%;

}
@media screen and (max-width: 543px ){
    .mi-cuenta  {
    height: 40vh;
    width: 70%;
    }
}
@media screen and (max-width: 543px ){
    .cuadro-info {
    height: 20%;
    width: 70%;
    
    }
}


@media screen and (min-width: 1043px) {
  .texto {
    font-size: 50px;
    
  }
}
@media screen and (min-width: 1043px) {
  .text {
    font-size: 40px;
    
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 1043px) {
  .texto , .text{
    font-size: 30px;
  }
}
</style>