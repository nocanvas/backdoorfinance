<template>
  <div class="layout">
    
    <slot/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
  font-family: 'arial', helvetica, sans serif;
  width: 100%;
  margin: 0;
  background: transparent;
  color: #0c0a34;
}

h1 {
 
}

h2 {
 
}


.wrapper {width: 800px; margin: 20px auto; text-align: center;}

.list_container {text-align: center; width: 300px; margin: 10px auto;}

.list_container ul {list-style: none; margin: 0; padding: 0;}

.surf {width: 600px; margin: 0 auto;}

.small {font-size: 10px;}

@media only screen and (max-width: 800px) {
 
 .wrapper {width: 90%; margin: 20px auto; text-align: center;}
.surf {width: 90%; }

img {width: 100%; height: auto;}

body {font-size: 20px;}


}


</style>
