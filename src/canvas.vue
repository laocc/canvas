<template>
    <canvas :style="canvasCSS"
            :width="width"
            :height="height"
            :canvas-id="canvasId"></canvas>
</template>

<script>
import canvas from './canvas';

module.exports = canvas;
// export default canvas;
</script>
