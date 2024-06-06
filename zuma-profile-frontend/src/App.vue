<template>
 <div id="app">
 <nav>
 <ul>
 <li><RouterLink to="/">Home</RouterLink></li>
 <li><RouterLink to="/about">About</RouterLink></li>
 <li><RouterLink to="/services">Services</RouterLink></li>
 </ul>
 </nav>
 <RouterView />
 </div>
</template>

<script>
export default {
 name: 'App'
}
</script>
<style>
nav ul {
 list-style-type: none;
 padding: 0;
}
nav ul li {
 display: inline;
 margin-right: 10px;
}
</style>