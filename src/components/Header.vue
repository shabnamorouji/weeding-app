<template>
    <div class="header" >
      <!-- <img src="../assets/banner.jpg"> -->
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-md">
          <a class="navbar-brand" href="#">Home</a>
          <a class="navbar-brand" href="#">Abut</a>
        </div>
      </nav>
      <h1>{{title}}</h1>
      <button type="button" class="btn btn-secondary btn-lg">Large button</button>

    </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
   title: String  
    
  }
}
</script>

<style scoped>
  .header{
    background:url("../assets/banner.jpg");
    color: #000;
    height: 850px;
    border-radius:0px 0px 200px 200px;
    background-repeat: no-repeat;
    background-size: cover;
    padding-top: 100px;
    
  }
  .navbar{
    margin-left: 250px;
    margin-right: 250px;
    height: 106px;
    border-radius: 100px;
    
  }
  button {
    margin-top: 431px;
    margin-left: 916px;
    width: 265px;
    height: 77px;
    background-color: white;
  }
  @media only screen and (min-width: 900px) {
      .header{
          height: 850px;
          padding-top: 100px;
         
      }
      .navbar{
        margin-left: 250px;
        margin-right: 250px; 
      }
  }


</style>
