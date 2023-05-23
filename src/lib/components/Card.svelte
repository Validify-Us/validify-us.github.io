<script>
    export let cardtitle = "card title"
    export let carddesc = "card description"
    export let cardlogo = "card description"

</script>

<div class="p-8 w-[22rem] bg-white border-purple-500 border-[3px] shadow-xl rounded-3xl md:w-[40rem] hover:bg-[#0d0024] hover:text-white duration-300 ease-in-out md:hover:w-[45rem]">
    <div>
        <img class="w-[5.3rem]" src={cardlogo} alt="logo of card">
    </div>
    <div>
        <h1 class="text-1xl font-bold uppercase py-4">{cardtitle}</h1>
        <p class=" break-words">{carddesc}</p>
    </div>
</div>