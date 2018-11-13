<template>
    <div>
        <div class="happy-hour">
            <h1>Happy Hour</h1>
            <p>Every day, 2PM - 7PM</p>
            <p>$2 off all beers except the beers of the month</p>
        </div>
        <BeerList />
    </div>
</template>

<script>
import BeerList from '../components/Beerlist';
export default {
    name: 'Home',
    components: {
        BeerList
    }
}
</script>

<style scoped>
.happy-hour {
    background-image: url('../assets/images/barGlasses.jpg');
    background-repeat: no-repeat;
    background-size: 100% 100%;
    /* padding: 5%; */
    text-align: center;
    color: #000000;
}

.happy-hour:last-child {
        padding: 0px 1em 1em;
}

h1 {
        font-size: 45px;
        padding-top: 5px;
}

p {
    font-size: 28px;
    margin: 0em;
    font-weight: bold;
}
</style>


