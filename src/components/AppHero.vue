<script>
export default {

}
</script>

<template>
    <div class="container">
        <img src="../assets/drago_shenron.jpg" alt="DuragoShenron">
    </div>
</template>

<style scoped>

   .container {
        text-align: center;
        margin: 70px auto;
    }

    img {
        width: 50%;
    }

    img:hover {
        box-shadow: 0 0 80px rgba(255, 68, 0, 0.5);
        transition: transform 0.3s ease-in-out;
        transform: scale(1.1);
        cursor: pointer;
    }

</style>