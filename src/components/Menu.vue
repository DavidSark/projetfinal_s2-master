
<template>
 <div class="w-screen h-max bg-white rounded-t-3xl border-2 border-gradient-to-r from-baby-blue to-blue-electric">
     <div class="flex justify-between items-center p-2">
        <RouterLink to="/apropos"><Info></Info></RouterLink>
        <button><Home></Home></button>
        <button><Ajout></Ajout></button>
        <button><Discussion></Discussion></button>
        <button><Profile></Profile></button>
    </div>
 </div>
</template>


<script>
import Info from './icones/Info.vue'
import Home from './icones/Home.vue';
import Ajout from './icones/Ajout.vue';
import Discussion from './icones/Discussion.vue';
import Profile from './icones/Profile.vue';

export default {
  components: {
    Info,
    Home,
    Ajout,
    Discussion,
    Profile,
  },
};
</script>
