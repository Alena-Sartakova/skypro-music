<template>
 <div class="bar">
    <div class="bar__content">
      <div class="bar__player-progress"></div>
      <div class="bar__player-block">
        <div class="bar__player player">
          <!-- Player controls -->
          <div class="player__controls">
            <div class="player__btn-prev">
              <svg class="player__btn-prev-svg">
                <use xlink:href="#icon-prev"></use>
              </svg>
            </div>
            <div class="player__btn-play _btn">
              <svg class="player__btn-play-svg">
                <use xlink:href="#icon-play"></use>
              </svg>
            </div>
            <div class="player__btn-next">
              <svg class="player__btn-next-svg">
                <use xlink:href="#icon-next"></use>
              </svg>
            </div>
            <div class="player__btn-repeat _btn-icon">
              <svg class="player__btn-repeat-svg">
                <use xlink:href="#icon-repeat"></use>
              </svg>
            </div>
            <div class="player__btn-shuffle _btn-icon">
              <svg class="player__btn-shuffle-svg">
                <use xlink:href="#icon-shuffle"></use>
              </svg>
            </div>
          </div>
          
          <!-- Current track info -->
          <div class="player__track-play track-play">
            <div class="track-play__contain">
              <div class="track-play__image">
                <svg class="track-play__svg">
                  <use xlink:href="#icon-note"></use>
                </svg>
              </div>
              <div class="track-play__author">
                <a class="track-play__author-link" href="http://">Ты та...</a>
              </div>
              <div class="track-play__album">
                <a class="track-play__album-link" href="http://">Баста</a>
              </div>
            </div>
          </div>
        </div>
        
        <!-- Volume controls -->
        <div class="bar__volume-block volume">
          <div class="volume__content">
            <div class="volume__image">
              <svg class="volume__svg">
                <use xlink:href="#icon-volume"></use>
              </svg>
            </div>
            <div class="volume__progress _btn">
              <input class="volume__progress-line _btn" type="range" name="range">
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.bar {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  background: rgba(28, 28, 28, 0.5);
}

.player__controls {
  display: flex;
  padding: 0 27px 0 31px;
}

.player__btn-play-svg {
  width: 22px;
  height: 20px;
  fill: #d9d9d9;
}

.volume__content {
  display: flex;
  align-items: center;
  justify-content: end;
}
</style>