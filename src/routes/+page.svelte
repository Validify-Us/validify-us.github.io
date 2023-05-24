<script>
	import Cardlist from '$lib/components/Cardlist.svelte';

import pitch from '$lib/assets/pitch.png'
import user from '$lib/assets/user.png'
import stats from '$lib/assets/stats.png'
import error from '$lib/assets/error.png'
</script>

<div>
  <div class=" md:p-[15rem] p-8 mt-10 flex items-center justify-center flex-col">
    <h1 class="md:text-[7rem] md:text-center md:text-7xl text-5xl text-center font-bold  text-[#630bde] capitalize break-words ">dont just secure it <span class="font-black text-[#35007a] hover:text-[7.1rem] hover:cursor-crosshair duration-300 ease-in-out hover:font-black hover:text-transparent hover:bg-clip-text hover:bg-gradient-to-r hover:from-[#6a00f5] hover:to-[#00f5d4]">validify </span>it!</h1>
    <p class="mt-[5rem] md:text-2xl text-[1.2rem] capitalize text-center">our blockchain sloution will ensure maximum security for all of your buissness affairs</p>
    <div class="md:p-10 py-5">
      <div class="md:border md:border-[30px] md:rounded-[9rem] md:border-[#9e73d9]">
        <img class="w-[100%] md:border md:border-[20px] md:rounded-[6.2rem] md:border-[#b897e7] shadow-lg rounded-lg" src={pitch} alt="">
      </div>
    </div>

  </div>

  <div class="w-[100%] bg-[#630bde] p-8 flex flex-col md:flex-row md:justify-between items-center">
    <div class="p-5 md:p-10">
      <img class=" w-[100%] md:w-[60rem]" src={error} alt="">
    </div>
    <div class="p-8 w-[100%]">
      <h1 class="text-4xl md:text-[3rem] text-white font-bold capitalize md:mr-8">Validify your Project Quality</h1>
      <p class="text-white break-before-all md:text-2xl text-[0.8rem] mt-8">Our expert trained AI models will analyze your test and quality metrics to generate customized reports to help identify possible risks and assure quality of your project updates, maintenance, and releases.</p>
    </div>

  </div>
  <div class="w-[100%] p-8 flex flex-col md:flex-row md:justify-between items-center">

    <div class="p-10">
      <h1 class="text-4xl md:text-[3rem] font-bold capitalize md:mr-8">Validify your Business Metrics</h1>
      <p class="break-before-all md:text-2xl text-[0.8rem] mt-8">Our AI models will learn your company's patterns and analyze your business metrics to identify opportunities for project workflow and process optimization.</p>
    </div>
    <div class="p-10">
      <img class="w-[60rem]" src={stats} alt="">
    </div>
  </div>
  
  <div class="w-[100%] p-8 flex flex-col md:flex-row md:justify-between items-center bg-[#630bde] text-white">
    <div class="p-10">
      <img class="w-[60rem]" src={user} alt="">
    </div>
    <div class="p-10">
      <h1 class="text-4xl md:text-[3rem] font-bold capitalize md:mr-8">Validify your Workforce</h1>
      <p class="break-before-all md:text-2xl text-[0.8rem] mt-8">Monitor and manage employee projects and skillsets. This data can even be obtained to verify skill and work experience of potential new employees who have completed work for other Validify customers.</p>
    </div>

  </div>

  <div class="p-8  w-[100%]">
    <Cardlist/>
  </div>
</div>