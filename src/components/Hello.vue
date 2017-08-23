<template>
  <div class="hello">
    <!-- First Container -->
    <div class="container-fluid bg-1 text-center">
      <h3 class="margin">Who Am I?</h3>
      <img src="bird.jpg" class="img-responsive img-circle margin" style="display:inline" alt="Bird" width="350" height="350">
      <h3>I'm an adventurer</h3>
    </div>

    <!-- Second Container -->
    <div class="container-fluid bg-2 text-center">
      <h3 class="margin">What Am I?</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
      <a href="#" class="btn btn-default btn-lg">
        <span class="glyphicon glyphicon-search"></span> Search
      </a>
    </div>

    <!-- Third Container (Grid) -->
    <div class="container-fluid bg-3 text-center">    
      <h3 class="margin">Where To Find Me?</h3><br>
      <div class="row">
        <div class="col-sm-4">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <img src="birds1.jpg" class="img-responsive margin" style="width:100%" alt="Image">
        </div>
        <div class="col-sm-4"> 
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <img src="birds2.jpg" class="img-responsive margin" style="width:100%" alt="Image">
        </div>
        <div class="col-sm-4"> 
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <img src="birds3.jpg" class="img-responsive margin" style="width:100%" alt="Image">
        </div>
      </div>
    </div>

    <!-- Footer -->
    <footer class="container-fluid bg-4 text-center">
      <p>copyright@2017</a></p> 
    </footer>

  </div>
</template>

<script>
export default {
  name: 'hello'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
