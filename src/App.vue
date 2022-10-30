<template>
    <div class="App">
      <div class="header row navbar">
      <NavBar/>
    </div> 
    <div class="body row scroll-y routerview">
      <RouterView />
    </div> 
    <div class="footer row">
      My footer
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
export default {
    name: 'App',
    components: {
      NavBar
    }
    
    }

</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap');
.App{
  font-family: 'Indie Flower', cursive;
  font-size: 1.1250em;
  background-color: var(--dark1);
  height: 100vh;
}

@media screen { 
  
  /* start of screen rules. */ 
  
  /* Generic pane rules */
  body { margin: 0; background-color: var(--light1);}
  .row, .col { overflow: hidden; position: absolute; }
  .row { left: 0; right: 0; }
  .col { top: 0; bottom: 0; }
  .scroll-x { overflow-x: auto; }
  .scroll-y { overflow-y: auto; }

  .header.row { height: 75px; top: 0; background-color: var(--dark1); }
  .body.row { top: 75px; bottom: 50px; }
  .footer.row { height: 50px; bottom: 0; background-color: var(--dark1); }
  
  /* end of screen rules. */ 
}
</style>