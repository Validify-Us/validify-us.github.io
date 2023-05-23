<script>
	import Card from "$lib/components/Card.svelte";
    import rocket from "$lib/assets/rocket.png"
    import blockchain from "$lib/assets/blockchain.png"
    import people from "$lib/assets/people.png"
    import automation from "$lib/assets/automation.png"

</script>

<div class="p-8 flex justify-center items-center">
    <div class="flex flex-col md:grid md:grid-rows-2 grid-flow-col gap-10">
        <Card cardtitle="Made for speed" carddesc="with our ai systems youll never have to worry about slow computing again!" cardlogo={rocket}/>
        <Card cardlogo={blockchain} cardtitle="blockchain the right way" carddesc="our platform brings blockchain standards back to what they used to be!"/>
        <Card cardlogo={automation} cardtitle="automation to the max" carddesc="automate all of your needs to save time and catch errors before production"/>
        <Card cardlogo={people} cardtitle="Devops made easy" carddesc="catch errors , automatically report bugs and get all of your users stats all in one place!"/>
    </div>
</div>
