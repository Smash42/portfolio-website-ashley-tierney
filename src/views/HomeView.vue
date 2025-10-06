<template>
  <h1 class="header title is-2"> Ashley Tierney Portfolio</h1>
  <div class="home backdrop homepage-contain columns">
    <div class="images column is-one-third">
        <section class="block"> 
          Image Insert
        </section>
    </div >
    <div class="info column">
        <section class="section ">
          <h3 class="title is-4 has-text-primary-dark">About Me: </h3>
            <p class="subtitle is-5 has-text-grey-darker"> An aspiring web developer, who is taking the time to go 
            back to school whilst working full time. Diligently working on learning all different programming
            languages to better suit the development world.  
            Sharpening my skills and continuing my education everyday to prepare myself.
            Looking to create resposive apps and web pages to easily align with the consumer needs.     </p>
        </section>   
      </div>  
  </div>
  <div class="footer p-2 columns">
    <section class="column"> Developer in the making </section>
    <section class="column">  </section>

  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>
<style>
.backdrop {
    width: 100%;
    height: 100%;
    background: rgb(245, 255, 139);
}

.homepage-contain {
  display: flex;
  
}

.header {
  text-align: center;
  font-size: 2em;
  padding: 10px;
  color: black;
}

.images {
  flex:1;
  float: left;
  padding: 5px;
}

.info {
  flex:1;  
  padding: 5px;
}

.footer {
  background: rgba(123, 241, 192, 0.288);
}
</style>
