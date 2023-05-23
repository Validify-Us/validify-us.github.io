<script>
	import Cardlist from '$lib/components/Cardlist.svelte';

import pitch from '$lib/assets/pitch.png'
import user from '$lib/assets/user.png'
import stats from '$lib/assets/stats.png'
</script>

<div>
  <div class=" p-8 mt-10 flex items-center justify-center flex-col">
    <h1 class="md:text-[7rem] md:text-center text-7xl text-center font-bold  text-[#630bde]">We are Validify!</h1>
    <p class="mt-[5rem] md:text-2xl text-[1.2rem] capitalize text-center">our blockchain sloution will ensure maximum security for all of your buissness affairs</p>
    <div class="md:p-10 py-5">
      <div class="md:border md:border-[30px] md:rounded-[9rem] md:border-[#9e73d9]">
        <img class="w-[100%] md:border md:border-[20px] md:rounded-[6.2rem] md:border-[#b897e7] shadow-lg rounded-lg" src={pitch} alt="">
      </div>
    </div>

  </div>

  <div class="w-[100%] bg-[#630bde] p-8 flex flex-col md:flex-row md:justify-between items-center">
    <div class="p-5 md:p-10">
      <img class=" w-[100%] md:w-[60rem]" src={user} alt="">
    </div>
    <div class="p-8 w-[100%]">
      <h1 class="text-4xl md:text-[5rem] text-white font-bold capitalize md:mr-8">im scared</h1>
      <p class="text-white break-before-all md:text-2xl text-[0.8rem] mt-8">idk im really scared about getting anaphalxis again everything i eat scares the living shit out of me</p>
    </div>

  </div>
  <div class="w-[100%] p-8 flex flex-col md:flex-row md:justify-between items-center">

    <div class="p-10">
      <h1 class="text-4xl md:text-[5rem] font-bold capitalize md:mr-8">im scared</h1>
      <p class="break-before-all md:text-2xl text-[0.8rem] mt-8">idk im really scared about getting anaphalxis again everything i eat scares the living shit out of me</p>
    </div>
    <div class="p-10">
      <img class="w-[60rem]" src={stats} alt="">
    </div>

  </div>

  <div class="p-8 bg-[#630bde] w-[100%]">
    <Cardlist/>
  </div>
</div>