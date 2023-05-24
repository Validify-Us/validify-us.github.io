<script>
  import Footer from '$lib/components/Footer.svelte';
  import "../app.css";
	import Nav from "$lib/components/Nav.svelte";
  </script>
  

  <nav>
    <Nav/>
  </nav>

  <main>
    <slot />
  </main>

<footer>
  <Footer/>
</footer>
  