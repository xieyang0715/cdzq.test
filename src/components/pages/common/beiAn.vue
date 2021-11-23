<template>
  <div class="bottom_beian">
    <div class="beian">
      <a target="_blank" href="http://beian.miit.gov.cn/">
        <img src="@/assets/pic/ghs.png" alt />
        <p>蜀ICP备2021029095</p>
      </a>
    </div>
  </div>
</template>
<script>
export default {
  name: "",
  props: {},
  components: {},
  data() {
    return {};
  },
  computed: {},
  methods: {},
  created() {},
};
</script>
<style>
.bottom_beian {
  position: fixed;
  bottom: 0px;
  text-align: center;
  width: 100%;
  background-color: #f3f3f3;
  line-height: 40px;
  padding: 5px 0 20px 0;
}
.beian p {
  display: inherit;
  text-align: center;
  color: #939393;
  padding: 0;
  margin: 0;
  line-height: 20px;
}
.beian a {
  display: inline-flex;
  text-align: center;
}
</style>