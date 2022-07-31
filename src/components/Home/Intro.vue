<template>
  <section class="scene-intro" id="intro">
    <div class="static-container">
      <h1 class="title">
        <span class="iuri">Soluhunt</span>
        <span class="func">.is()</span>
      </h1>

      <TextBlock>
        <p class="-purple">Soluhunt</p>
        <p class="-gray">Sophisticated simplicity</p>
      </TextBlock>
    </div>
  </section>
</template>

<script>
import TextBlock from '../TextBlock.vue'
export default {
  name: 'IntroScene',
  components: { TextBlock },
}
</script>
