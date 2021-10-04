<template>
    <div class= "container-fluid barra">
    <b-navbar class= "colorNegro" toggleable="lg" type="dark ">
        <b-navbar-brand href="#">
            <img class= "logo" src="https://i.ibb.co/5Y4qxx6/Logo-Devance.png" alt="Devance-Logo" border="0" height="60" width="    60">
            <img src="https://i.ibb.co/pXH1bYd/Screenshot-1-removebg-preview-2.png" alt="Devance" border="0" height="60">
        </b-navbar-brand>

        <b-navbar-toggle class="colorBoton1 colorNegroLetra" target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>


        <!-- Right aligned nav items -->

        <b-col cols="9" class= "container-fluid">
        </b-col>

        <b-navbar-brand class= "button-drop" >

            <b-button size="l" class="my-2 colorNegroLetra my-sm-0 rounded-pill colorBoton1 colorNegroLetra" type="submit">Hazte Cliente</b-button>
            <b-button size="l" class="my-2 colorNegroLetra my-sm-0 rounded-pill colorBoton1 colorNegroLetra" type="submit">Iniciar Sesión</b-button>


        </b-navbar-brand >
        </b-collapse>
    </b-navbar>
    </div>
</template>

<style>

.barra{
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    padding-left: 0px !important;
    padding-right: 0px !important;
    
}
.colorNegro{
    background-color: #343330;

}
.colorNegroLetra{
    color: #343330 !important;
}

.colorBoton1{
    background-color: #FFA737 !important;
    border: 0px !important;
    margin-left: 5px;
    margin-right: 5px;
    
}
.logo{
    margin-left: 20px;
   
}
.colorBoton1:hover{
    background-color: #DC851F !important;
}
.button-drop {
    text-align: right;
}
</style>