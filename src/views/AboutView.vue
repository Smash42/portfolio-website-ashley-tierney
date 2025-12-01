<template>
  <div>
    <h1 class="title is-1 has-text-black">About the Developer</h1>

    <div class="about m-2 p-2">
      <div class="block has-background-success-light">
        <h2 class="title is-3 has-text-primary-dark">Welcome!</h2>
        <p class="is-size-5" >
          Hello! I'm Ashley Tierney, an aspiring web developer passionate about
          creating responsive and user-friendly web applications. 
        </p>
        <p class="is-size-5">
          Currently, I'm balancing full-time work while pursuing my studies in web
          development. My journey involves mastering various programming languages
          and frameworks to stay competitive in the ever-evolving tech landscape.
          </p>
      </div>
      <div class="block has-background-success-light">
       <p class="is-size-7">
          This site was created as part of a project exploring how Large Language
          Models such as ChatGPT can help build, edit, or enhance a web
          application.  
        </p>

        <p class="is-size-7">
          You can navigate the site to see auto-generated pages, API-fetched
          content, and examples of how AI can integrate directly into a
          development workflow.
        </p>

        <p class="is-size-7">
          The goal is to show that an AI assistant can help streamline coding,
          writing, design, and documentation—without replacing the developer’s
          creative direction!
        </p>
      </div>
    </div>

    <div class="footer p-2 columns">
      <section class="column">
        🧑‍💻 Learning, Building, Growing &#x1F988;
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutView",
};
</script>

<style scoped>
.about {
  background: rgb(245, 245, 139); /* same as portfolio section */
}

/* Match portfolio block style */
.block {
  margin: 10px;
  padding: 10px;
  border-radius: 5px;
  border: 2px solid rgb(0, 0, 0);
}

/* Match link hover style */
a:hover {
  text-decoration: underline;
  text-decoration-style: double;
  color: rgb(245, 245, 139);
}

.footer {
  background: rgba(14, 39, 7, 0.562);
  color: white;
}
</style>
