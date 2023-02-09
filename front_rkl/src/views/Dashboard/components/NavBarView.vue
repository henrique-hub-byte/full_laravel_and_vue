<template>
    <div class="navbar">
        <h3 class="logo"><i class="fas fa-star icon"></i> Logo Marca</h3>
        <a href="" @click.prevent="logout" class="logout"><i class="fa fa-sign-out-alt"></i> Sair</a>
    </div>
</template> 

<script>
export default {
    name: 'NavBarView',
    methods: {
        logout(){
            this.$router.push({name:'login'});
        }
    }
}
</script>

<style lang="scss">
.navbar {
    
    .logo { 
        color: #fff;
    }

    .logout {
        color: #fff;
        float: right;
        text-decoration: none;
    }

     
}
</style>