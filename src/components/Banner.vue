<template>
    <Div id="main-banner">
        <h1>Make Your Burger</h1>
    </Div>
</template>
<script>
    export default{
        name: "Banner"

    }
</script>

<style scoped>

  #main-banner {
    background-image: url('/public/img/burger.png');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
  }

</style>