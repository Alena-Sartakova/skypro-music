<template>
 <div class="playlist__item">
    <div class="playlist__track track">
      <div class="track__title">
        <div class="track__title-image">
          <svg class="track__title-svg">
            <use xlink:href="#icon-note"></use>
          </svg>
        </div>
        <div class="track__title-text">
          <a class="track__title-link" href="http://">
            {{ trackTitle }} <span class="track__title-span">{{ trackSubtitle }}</span>
          </a>
        </div>
      </div>
      <div class="track__author">
        <a class="track__author-link" href="http://">{{ author }}</a>
      </div>
      <div class="track__album">
        <a class="track__album-link" href="http://">{{ album }}</a>
      </div>
      <div class="track__time">
        <svg class="track__time-svg">
          <use xlink:href="#icon-like"></use>
        </svg>
        <span class="track__time-text">{{ duration }}</span>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.track__title {
  display: flex;
  align-items: center;
  width: 447px;
}

.track__title-image {
  width: 51px;
  height: 51px;
  padding: 16px;
  background: #313131;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 17px;
}

.track__title-svg {
  width: 18px;
  height: 17px;
  fill: transparent;
  stroke: #4e4e4e;
}

.track__author {
  width: 321px;
  justify-content: flex-start;
}

.track__album {
  width: 245px;
}

.track__time-svg {
  width: 14px;
  height: 12px;
  margin-right: 17px;
  fill: transparent;
  stroke: #696969;
}
</style>