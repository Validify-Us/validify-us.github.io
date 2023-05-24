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

    import navlogo from '$lib/assets/navicon.png'
    import closelogo from '$lib/assets/close-logo.png'
</script>


<div>
    <div class="flex items-center p-8 justify-between">
        <a href="/" class=" text-3xl font-bold text-[#5f00e3]">Validify</a>
        <ul class="hidden md:flex gap-4">
            <a class="hover:text-[#5f00e3] duration-300 ease-in-out capitalize hover:font-[600]" href="/">home</a>
            <a class="hover:text-[#5f00e3] duration-300 ease-in-out capitalize hover:font-[600]" href="#">contact us</a>
            <a class="hover:text-[#5f00e3] duration-300 ease-in-out capitalize hover:font-[600]" href="/team"> our team</a>
        </ul>
        <img class=" {navToggle ? "hidden" : "block"} md:hidden w-[4rem] hover:cursor-pointer" on:click={toggleNavbar} src={navlogo} alt="nav icon">
        <img class="{!navToggle ? "hidden" : "block"} md:hidden w-[3rem] hover:cursor-pointer" on:click={toggleNavbar} src={closelogo} alt="nav icon">

    </div>
    <div class="{!navToggle ? "hidden" : "flex"} bg-[#350a70] p-8 w-[100%] h-max justify-center items-center gap-4 md:hidden shadow-lg">
        <ul class="flex flex-col justify-center items-center text-center text-white">
            <a class=" hover:text-[#5f00e3] duration-300 ease-in-out capitalize hover:font-[600]" href="/">home</a>
            <a class="hover:text-[#5f00e3] duration-300 ease-in-out capitalize hover:font-[600]" href="#">contact us</a>
            <a class="hover:text-[#5f00e3] duration-300 ease-in-out capitalize hover:font-[600]" href="/team"> our team</a>
        </ul>
    </div>
    

</div>
