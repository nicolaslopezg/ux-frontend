<template>
  <div class="facturas">
    <h1>QUE PASA LARVA</h1>

    <ul class="card-wrapper mx-auto">
      <li class="card">
        <img class ="imagen" src='https://i0.wp.com/colegiorudolf.cl/wp-content/uploads/2021/02/Lista-de-suscriptores-de-email-marketing.jpg' width="auto" height="auto" alt=''>
        
      </li> 
    </ul>

  

    


  </div>
</template>

<script>
export default {
  name: 'facturas',
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
  margin-bottom: 50px;
  background-color: #fff;
  border-radius: 0.5rem;
  box-shadow: 0.05rem 0.1rem 0.3rem -0.03rem rgba(0, 0, 0, 0.45);
  max-height: 700px;
  background-image: linear-gradient(
    var(--card-gradient),
    rgb(250, 241, 216) max(9.5rem, 27vh)
  );
  overflow: hidden;
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
  
  max-width: 70vw;
  width: 120ch;
  
}

</style>
