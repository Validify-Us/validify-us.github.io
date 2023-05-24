<script>
	import Card from "$lib/components/Card.svelte";
    import rocket from "$lib/assets/rocket.png"
    import blockchain from "$lib/assets/blockchain.png"
    import people from "$lib/assets/people.png"
    import automation from "$lib/assets/automation.png"

</script>

<div class="p-8 flex justify-center items-center">
    <div class="flex flex-col md:grid md:grid-rows-2 grid-flow-col gap-10">
        <Card cardtitle="Fast and Easy to Get Started" carddesc="Automate Any Type of Workflow Quickly and Easily Using Our AI Tools" cardlogo={rocket}/>
        <Card cardlogo={blockchain} cardtitle="Blockchain/Web3 Security for Your Data and Reports" carddesc="Our Blockchain and NFT Standards Can Be Used to Secure And Control Access to Your Data, Metrics, and Reports Separately From Internal, Confidential, or Propietary Data and Code."/>
        <Card cardlogo={automation} cardtitle="Automate Your Automation Solutions" carddesc="Our AI Tools Will Analyze Your Toolsets and Help Generate Your Plugins and Integrations"/>
        <Card cardlogo={people} cardtitle="DevOps and Auditing Made Easy" carddesc="Our AI Tools Are Designed to Generate, Monitor, and Manage Your Automation Code and Scripts Reducing The Risk of Human Error, Miscommunications, and Downtime."/>
    </div>
</div>
