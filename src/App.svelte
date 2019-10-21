<script>
    import '../node_modules/materialize-css/dist/css/materialize.css';
    import '../node_modules/materialize-css/dist/js/materialize.js';

    import { Router, Link, Route } from "svelte-routing";

    import Navbar from './layout/Navbar.svelte';
</script>

<style>

</style>

<Router>
    <Navbar />
    <div class="container">
        <Route path="/" component={Home}></Route>
        <Route path="/about" component={About}></Route>
    </div>
</Router>
