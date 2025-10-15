<script setup>
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <h1 class="section-title">Explainer Video</h1>
    </el-row>

    <el-row justify="center">
  <el-col :xs="24" :sm="30" :md="16" :lg="12" :xl="10">
    <el-container class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
      <iframe 
        src="//player.bilibili.com/player.html?bvid=BV1V8WazxE7p&autoplay=0" 
        scrolling="no" 
        border="0" 
        frameborder="no" 
        framespacing="0" 
        allowfullscreen="true"
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
      </iframe>
    </el-container>
  </el-col>
</el-row>
  </div>
</template>

<style scoped>

.video-container{
  margin: 20px 0px 0px 0px;
}

iframe, video {
  aspect-ratio: 16 / 9;
  width: 100%;
}

</style>
