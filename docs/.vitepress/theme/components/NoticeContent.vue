<script setup lang="ts" name="NoticeContent">
const namespace = "notice";
</script>

<template>
  <div :class="namespace">
    <p>微信公众号 👇</p>
    <img src="/img/qrCode.png" alt="QR Code" />
    <p class="">欢迎关注我的公众号！</p>
    <p class="">My name is Yan！</p>
  </div>
</template>

<style lang="scss" scoped>
.notice {
  img {
    width: 100%;
    height: 120px;
    object-fit: contain;
  }
  p {
    text-align: center;
    font-size: 14px;
    padding: 10px 0;
  }
}
</style>
