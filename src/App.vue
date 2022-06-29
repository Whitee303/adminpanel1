<template>
    <div id="Block">
        <div class="block-flex">
                <okno name="panel">
                    <div>
                       <button type="button"></button>
                    </div>
                </okno>
        </div>
    </div>
</template>
<script lang="ts">
import okno from '../../components/src/components/window.vue'

export default {
  name: 'App',
  components: {
    okno
  }
}
</script>

<style>
body {
    user-select: none;
    background-color: rgb(0, 0, 0);
}
#Block {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
.block-flex {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}
.button {
    position: relative;
    width: 7vw;
    height: 2vh;
}
.panel {
    position: relative;
    width: 27vw;
    height: 32vh;
}
</style>
