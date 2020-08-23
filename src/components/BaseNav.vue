<template>
    <nav class="nav-container">
        <div class="logo-text">
            <h3>BIIP</h3>
        </div>
        <ul>
            <li>
                 <font-awesome-icon :icon="['fas', 'home']" size="lg" />
            </li>
            <li class="profile-image">
                <img src="../assets/perfilPic.jpg">
            </li>
            <li>
                <font-awesome-icon :icon="['fas', 'comments']" size="lg" />
            </li>
        </ul>
    </nav>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    name:'BaseNav'
})
</script>

<style scoped>
    .nav-container{
        width: 100%;
        height: 80px;
        background-color: rgb(255, 255, 255);
        border-bottom: 1px solid rgba(0, 0, 0, 0.13);
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .nav-container ul{
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .nav-container ul li{
        list-style: none;
        margin-left: 5px;
        padding: 10px;
    }

    .profile-image{
        width: 25px;
        height: 25px;
    }

    .profile-image img{
        width: 100%;
        height: 100%;
        border-radius: 50%;
    }

    .logo-text{
        margin-left: 10px;
    }
</style>