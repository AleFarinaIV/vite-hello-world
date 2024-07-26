<script>
export default {
  
}
</script>

<template>
    <div class="container">
        <p>La mia prima app con Vite!</p>
    </div>
</template>

<style scoped>

    .container {
        display: flex;
        justify-content: center;
        margin-top: 20px;
    }

    p {
        color: rgb(53, 144, 28);
        font-size: 48px;
        font-weight: bold;
    }

    p:hover {
        color: rgb(64, 255, 0);
        transition: color 0.3s ease-in-out;
        cursor: pointer;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
    }

</style>
