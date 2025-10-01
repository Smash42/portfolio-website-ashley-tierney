<template>
  <h1 class="header"> Ashley Tierney Portfolio</h1>
  <div class="home backdrop homepage-contain">
    <div class="images">
        <section> image Insert
        </section>
    </div >
    <div class="info">
        <section>
          <h3>About Me: </h3>
            <p> An aspiring web developer, who is taking the time to go 
            back to school whilst working full time. Diligently working on learning all different programming
            languages to better suit the development world.  
            Sharpening my skills and continuing my education everyday to prepare myself.
            Looking to create resposive apps and web pages to easily align with the consumer needs.     </p>
        </section>   
      </div>  
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
</style>
