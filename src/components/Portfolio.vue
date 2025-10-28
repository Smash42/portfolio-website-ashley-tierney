<template>
    <h1 class="title is-1 has-text-black"> Developer Portfolio</h1>
    <div class="portfolio m-2 p-2">
        <ul v-if = loading> Loading Repositories... </ul> 
        <ul v-else>
            <li v-for="repo in repos" :key="repo.id" class="block has-background-success-light">            
                <a :href="repo.html_url"><p class="link is-size-4 has-text-primary-dark">{{ repo.name }} </p></a>
                <div class="items">
                <p>Description: {{ repo.description }}</p>
                <p>Language: {{ repo.language }}</p>
                <p>Last Update: {{ new Date( repo.updated_at).toLocaleString() }} </p>
                </div>
            </li>
        </ul>
    </div>
    <div class="footer p-2 columns">
    <section class="column"> &#x1F988;  Developer in the making  &#x1F988; </section>
  </div>
</template>

<script>
export default {
data(){
    return {
        repos: [],
        loading: true,
    }
},
mounted() {
    fetch('https://api.github.com/users/Smash42/repos')
    .then(response => response.json())
    .then(data => {
        this.repos = data;
        this.loading = false;
    })
    .catch(error => {
        console.error('Error fetching repositories:', error);
        this.loading = false;
    });
    

}
}
</script>
<style>
.portfolio {
    background: rgb(245, 245, 139);
}

.block {
    margin: 10px;
    padding: 10px;
    border-radius: 5px;
    border: 2px solid rgb(0,0,0);
}
 a:hover{
    text-decoration: underline;
    text-decoration-style: double;
    color: rgb(245, 245, 139);
 }
 
 .items {
    text-align: left;
}

.footer {
  background: rgba(14, 39, 7, 0.562);
  color: white;
}


</style>