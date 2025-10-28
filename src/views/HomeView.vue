<template >
  <h1 class="header title is-1"> &#x1F988; Ashley Tierney Portfolio </h1>
  <div class="home backdrop homepage-contain columns is-multiline ml-1 mr-1 p-1 ">

      <div class="images column is-one-quarter-desktop is-one-third-mobile is-one-third-tablet">
        <section class="block m-1 has-background-success-light"> 
          <img alt="portrait1" src="@/assets/portrait1.jpg" width="300" height="400"/>          
        </section>
      </div >

      <div class="info column is-three-quarters-desktop is-two-thirds-mobile is-two-third-tablet">
        <section class="section has-background-primary-light is-three-quarters">
          <h3 class="title is-4 has-text-primary-dark">About Me: </h3>
          <p></p>
            <p class="subtitle is-5 has-text-grey-darker"> An aspiring web developer, who is taking the time to go 
            back to school whilst working full time. 
            Committed to learning a variety of programming languages to stay competitive in the ever-evolving world of development. 
            Every day, I focus on sharpening my skills and expanding my knowledge to better prepare for real-world challenges. 
            My goal is to create responsive applications and web pages that align seamlessly with user needs.
             </p>
        </section>          
      </div>  
             
  </div>
   
  <div class="footer p-2 columns">
    <section class="column"> &#x1F988;  Developer in the making  &#x1F988; </section>
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

.header {
  text-align: center;
  font-size: 2em;
  padding: 10px;
  color: black;
}

.images {

  padding: 5px;
  background: rgba(10, 87, 45, 0.561);
}

.info {
  padding: 5px;
  
}

.footer {
  background: rgba(14, 39, 7, 0.562);
  color: white;
}
</style>
