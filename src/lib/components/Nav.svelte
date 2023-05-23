<script>
    let navToggle = false
    function toggleNavbar()
    {
        if (navToggle === false)
        {
            navToggle = true
        }
        else
        {
            navToggle = false
        }
    }
</script>

<div>
<button class=" bg-slate-500 px-3 py-2" on:click={toggleNavbar}>togglecheck</button>
<p class="{!navToggle ? "hidden" : "block"}">im showing if true</p>
</div>