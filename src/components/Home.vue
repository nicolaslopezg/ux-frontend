<template>
  <div class="hello container-fluid text-center">
    

    <ul class="card-wrapper mx-auto">
      <li class="card">
        <img src='https://i.ibb.co/T1DWzJ4/business-people-shaking-hands-outside-of-office-building-521813417-5954fdc33df78cdc2970d5ac.jpg' width="auto" height="350" alt=''>
        
      </li>
      <li class="card text-center">
        <h3>¿Por qué confiar en nosotros?</h3>
        <p>Actualmente damos servicios a varias compañías, 
          las cuales a su vez atienden a una gran cantidad de 
          clientes, nos especializamos mayoritariamente en clientes los 
          cuales tienen sus operaciones en el ámbito bancaria, 
          pero a su vez también poseemos cliente fuera de este 
          espectro, por lo cual nos sentimos muy capaces a la hora de 
          atender diversas necesidades. </p>
      </li>
      
    </ul>

    <b-card class="clientes mx-auto">
              <b-card-text>
               Nuestros Clientes
              </b-card-text>
    </b-card>
    <div class="compañias">
      <div class="row">
        <div class= "col-sm">
          <b-card img-src="https://i.ibb.co/kMr2tjf/Banco-Internacional.png" img-width="300" img-height="300" img-alt="Card image" img-top>
              <b-card-text>
                Banco Internacional.
              </b-card-text>
          </b-card>
        </div>
        <div class= "col-sm">
          <b-card img-src="https://i.ibb.co/R2m0Zjn/san-logo.png" img-width="300" img-height="300" img-alt="Card image" img-top>
              <b-card-text>
                Banco Santander.
              </b-card-text>
          </b-card>
        </div>
        <div class= "col-sm">
          <b-card img-src="https://i.ibb.co/jwHXZfy/falabella.png" img-width="300" img-height="300" img-alt="Card image" img-top>
              <b-card-text>
                Falabella.
              </b-card-text>
          </b-card>
        </div>
      </div>
    </div>

    


  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.compañias{
  margin-bottom: 50px;
}
.clientes{
  
  max-width: 400px;
}
.transparente{
  opacity : 0.5;
}
.card {
  --card-gradient: rgba(0, 0, 0, 0.5);
  --card-gradient:rgba(248, 230, 180, 0.5);

  --card-blend-mode: overlay;
  margin-top: 50px;

  background-color: #fff;
  border-radius: 0.5rem;
  box-shadow: 0.05rem 0.1rem 0.3rem -0.03rem rgba(0, 0, 0, 0.45);

  background-image: linear-gradient(
    var(--card-gradient),
    rgb(250, 241, 216) max(9.5rem, 27vh)
  );
  overflow: hidden;
}
.img {
    border-radius: 0.5rem 0.5rem 0 0;
    width: 100%;
    object-fit: cover;
    
    max-height: max(10rem, 30vh);
    aspect-ratio: 4/3;
    mix-blend-mode: var(--card-blend-mode);
    
  }

/* Additional demo display styles */
* {
  box-sizing: border-box;
}



.card h3 {
  margin-top: 1rem;
  font-size: 1.25rem;
}

.card a {
  color: inherit;
}

.card-wrapper {
  list-style: none;
  padding: 0;
  margin: 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30ch, 1fr));
  
  max-width: 100vw;
  width: 120ch;
  
}

</style>
