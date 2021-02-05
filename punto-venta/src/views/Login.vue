<template>
    <div class="divLogin container-fluid">
        <div class="row">
            <div class="col-6 col-izquierda">
            <!-- <v-img 
            class="imagen"
            :src="require('../../public/img/bg1.jpg')"
            ></v-img> -->
            </div>
            <div class="col-6 col-derecha">
                <v-row align="center" justify="space-around">
                    <form class="col-6">
                        <div class="col-12 ">
                            <v-text-field label="Usuario"></v-text-field>
                        </div>
                        <div class="col-12 ">
                            <v-text-field
                            type="password"
                            ></v-text-field>
                        </div>
                        <div class="col-12 ">
                            <v-row align="center" justify="space-around">
                                <v-btn depressed color="primary"> Ingresar </v-btn>
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
}
</script>

<style scoped>

.imagen{

height: 110%;
}

.divLogin{
    height: 100%;
    margin-top: 200px;
}

.row{
    height: 100%;
}

.col-izquierda{
 height: 60%;
background-color: violet;
}

.col-derecha{
     height: 60%;
    background-color: white;

}



</style>