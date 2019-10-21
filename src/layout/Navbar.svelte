<script>
    import { Link } from "svelte-routing";
</script>

<!--From https://materializecss.com/navbar.html-->
<nav>
    <div class="nav-wrapper">
        <Link to="/" class="brand-logo">Svelte Tutorial</Link>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
            <li><Link to="/">Home</Link></li>
            <li><Link to="/about">About</Link></li>
        </ul>
    </div>
</nav>
