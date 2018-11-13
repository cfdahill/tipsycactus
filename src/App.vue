<template>
    <div class="everything">
        <header>
            <img src="./assets/images/tipsyLogo.png" alt="Tipsy Cactus logo" >
            Insert navbar here
        </header>
        <div class="main-content">
            <Home />
        </div>
        <footer>
            Footer
        </footer>
    </div>
</template>

<script>
import Home from './pages/Home';

export default {
    name: 'App',
    components: {
        Home
    }
}
</script>

<style>
    /* starting with css for phone, will do others afterwards */
    .everything {
            font-family: 'Barlow Condensed', sans-serif;
    }
    
    .main-content {
        width:90%;
        margin: auto;
    }
</style>

