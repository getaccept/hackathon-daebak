<template>
  <div>hej</div>
</template>

<script lang="ts">
/// <reference types="@types/dom-mediacapture-record" />
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class VideoPlayer extends Vue {
  @Prop() private msg!: string;
  mediaRecorder: MediaRecorder = null;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
