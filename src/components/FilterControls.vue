<template>
            <div class="centerblock__filter filter">
              <div class="filter__title">Искать по:</div>
              <div class="filter__button button-author _btn-text">
                исполнителю
              </div>
              <div class="filter__button button-year _btn-text">
                году выпуска
              </div>
              <div class="filter__button button-genre _btn-text">жанру</div>
            </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.centerblock__filter {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  margin-bottom: 51px;
}
.filter__title {
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  margin-right: 15px;
}

.filter__button {
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  border: 1px solid #ffffff;
  border-radius: 60px;
  padding: 6px 20px;
}

.filter__button:not(:last-child) {
  margin-right: 10px;
}

</style>