<template>
  <div class="el-input el-input--suffix">
    <input
      :type="type"
      :readonly="readonly"
      :placeholder="placeholder"
      class="el-input__inner"
      v-model="inputValue"
    />
  </div>
</template>

<script>
export default {
  props: {
    value: [String, Number],
    readonly: Boolean,
    placeholder: String,
  },
  data() {
    return {
      type: "password",
      inputValue: "",
    };
  },
  mounted() {
    this.inputValue = this.value;
  },
  methods: {
    changeEye() {
      this.type = this.type == "text" ? "password" : "text";
    },
  },
  watch: {
    inputValue(val) {
      this.$emit("change", val);
    },
  },
};
</script>

<style scoped>
.eye {
  position: absolute;
  right: 5px;
  width: 16px;
  margin-top: 17px;
  cursor: pointer !important;
  display: inline;
}
</style>
