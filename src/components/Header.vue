<template>
    <div class="header" >
      <!-- <img src="../assets/banner.jpg"> -->
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-md">
          <a class="navbar-brand tex-home" href="#">Home</a>
          <a class="navbar-brand tex-abut" href="#">Abut</a>
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
    padding-top: 50px;
    
  }
  .navbar{
    margin-left: 250px;
    margin-right: 250px;
    height: 70px;
    border-radius: 100px;
    
  }
  button {
    margin-top: 300px;
    margin-left: 570px;
    width: 200px;
    height: 60px;
    background-color: white;
  }
  .tex-home {
    padding-left: 880px;
  }
  .tex-abut{
    padding-right: 40px;
  }
  @media only screen and (min-width: 900px) {
      .header{
          height: 620px;
          padding-top: 50px;
         
      }
      .navbar{
        margin-left: 115px;
        margin-right: 115px; 
      }
  }
  @media only screen and (max-width:600px) {
    .header{
      height: 850px;
    }
  }


</style>
