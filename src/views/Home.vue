<template>
  <div class="home">
    <HelloWorld msg="MEAT DEVS"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>

<style>
  body
{background-image: url(../assets/sugar-steak-with-bourbon5.png);
background-size:auto;
background-repeat:no-repeat;
} 

</style>
