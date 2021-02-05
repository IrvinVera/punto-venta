<template>
    <div class="divLogin container-fluid">
        <div class="row no-margin">
            <div class="col-7 col-izquierda">
                    <div class="col-12 columnaInterna12">
                    </div>
            </div>
            <div class="col-5 col-derecha">
                <v-row justify="space-around">
                    <form class="col-6 class-form">
                        <div class="col-12 ">
                             <v-row justify="space-around">
                                <v-icon class="icon"
                                x-large
                                color="grey darken-2"
                               style="font-size: 200px"
                                >
                                mdi-account
                                </v-icon>
                            </v-row> 
                        </div>
                        <div class="col-12">
                            <v-text-field label="Usuario"></v-text-field>
                        </div>
                        <div class="col-12 ">
                            <v-text-field
                            label="Contraseña"
                            type="password"
                            ></v-text-field>
                        </div>
                        <div class="col-12 ">
                            <v-row align="center" justify="space-around">
                                <v-btn depressed color="primary" @click="ingresar()"> Ingresar </v-btn>
                            </v-row>
                        </div>

                    </form>
                </v-row> 
            </div>
        
        </div>
    </div>
</template>

<script>
export default {
    name: 'divLogin',
        methods:{
            ingresar(){
                alert("ad");
            }
        },
}
</script>

<style scoped>

.divLogin{
    height: 100%;
     width: 100%;
     padding: 0;
     
}

.columnaInterna12{
     height: 100%;
       background-color:lightskyblue;
         margin: 0;
}

.no-margin{
    margin: 0;
}

.row{
    height: 100%;
    width: 100%;
}



.col-derecha{

    background-color: white;

}

.col-izquierda{

    background-color: white;
    padding: 0;

}
.class-form{
    margin-top: 100px;
}

/* .imagen{
    width: 100%;
    height: 100%;
    
} */


/* 
.imagen{
height: 100%;

background-image: url('../../public/img/imagenVenta2.png');
} */

/* .cont-img{
    
} */

/* .divLogin{
    height: 100%;
}



.col-izquierda{
 height: 100%;
}

.col-derecha{
     height: 60%;
    background-color: white;

} */



</style>