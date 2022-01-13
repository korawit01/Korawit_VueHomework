<template>
<div class="bg-gradient-to-r from-blue-500 to-indigo-500 text-white">
  <div class="grid grid-cols-1 place-items-center ">
    <h1 class="font-bold text-2xl pb-5">Portfolio</h1>
    <img class="pb-5" src="../assets/96A46649-8DB0-4B04-A067-FDE3820737E3.jpeg" width="350" height="350">
    <div>
      <p>Korawit Rittsit (Oum)</p>
      <p>22 year old</p>
    </div>
    --------------------------------------------------------------
    <div>
      <h2 class="font-bold text-xl">Skill</h2>
      <h3 class="font-medium text-lg">Computer language</h3>
      <ul class="border-2 pl-5"> 
        <li>java</li>
        <li>javascript</li>
        <li>html</li>
        <li>css</li>
        <li>sql</li>
        <li>xml</li>
        <li>xsl</li>
        <li>python</li>
      </ul>
      <h3 class="font-medium text-lg">Tool</h3>
      <ul class="border-2 pl-5"> 
        <li>Vue.js </li>
        <li>Git </li>
        <li>Azure</li>
        <li>Docker</li>
        <li>MS Visual Studio</li>
      </ul>
    </div>
    <button class="pt-10 pb-10">Contact</button>
  </div>
</div>
</template>

<script>
export default {
  name: 'Portfolio',
  props: {
  }
}
</script>
