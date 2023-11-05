<template>
  <div class="MyCard">
    <div class="the-card_title">
      {{ cardTitle }}
    </div>
    <div class="the-card_body">
      <slot>
        <p>This is defoult card content</p>
      </slot>
    </div>
  </div>
</template>

<script>
export default {
  props: ["cardTitle"],
};
</script>

<style>
.MyCard {
  width: 200px;
  border: 1px solid #006f88;
  min-height: 200px;
  margin: 22px auto;
}
.the-card_title {
  background: #167db1;
  padding: 5px 11px;
  color: #fff;
}

.the-card_body {
  padding: 11px;
}

.the-card_body img {
  height: 111px;
}
</style>
